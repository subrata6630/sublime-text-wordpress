##Sublime Text WordPress Package

Sublime Text WordPress Package is a collection of WordPress snippets and autocompletions for Sublime Text

### Features

Autocomplete for:

    WP version : 4.2.2

    Functions    : 2506
    Filters      : 1105
    Actions      : 533
    Classes      : 245
    Constants    : 502
    Capabilities : WordPress Core Capabilities


### Notes

Deprecated functions have been removed

On some cause the first "tab" deletes all parameters instead of having to tab through each one:

- First Tab --> Select all parameters
- Each Tab There after --> Selects each individual parameter or block

Actions or Filter add two version of the completion only this not is dynamic name

Example of completion file for Hooks:
```
        {
            "trigger": "add_action-activated_plugin\tWP Action",
            "contents": "add_action( 'activated_plugin', ${1:\\$function_to_add}${2:, ${3:10}${4:, ${5:2}}} );"
        },
        {
            "trigger": "activated_plugin\tWP Action Name",
            "contents": "activated_plugin"
        },
```
This first trigger use add_action- for get all actions and continue by name of the action, returns everything you need to create.
The second trigger simply use the name and return this name.

Include Akismet v3.1.2, Default themes for completions

Defaults Themes Versions:

	classic        : v1.6
	default        : v1.7.2
	twentyten      : v1.9
	twentyeleven   : v2.1
	twentytwelve   : v1.7
	twentythirteen : v1.5
	twentyfourteen : v1.4
	twentyfifteen  : v1.2

### Snippets

In the process, there are now those of the original package

### Tips

Tested on Sublime Text v3092


###  Install instructions

- Remove or Disabled original package
- Add repository via Package Control: Add Repository

### Issues & Featured Requests

You found some issue, please create an issue to solve it.

Snippets of time are not updated, but will be updated, removing or adding (if considered appropriate any user can create a featured request to add)