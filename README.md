## Summary

Uses the commandline/python-module javascript formatter from http://jsbeautifier.org/ to format the selected text, 
or the entire file if there is no selection. Plugin does not check to make sure the buffer has a ".js" file type, 
it just javascript formats the selection/file. Thus, use with caution if you are in an html file.

## Settings
JsFormat will uses whatever tab character settings are configured with the standard "translate_tabs_to_spaces" and "tab_size" sublime settings.

In addition, the following settings can be overridden in your user file settings (defaults shown below):

* "jsformat_max_preserve_newlines": 3
* "jsformat_preserve_newlines": true
* "jsformat_jslint_happy": false
* "jsformat_brace_style": "collapse"
* "jsformat_keep_array_indentation": false
* "jsformat_indent_level": 0

## Install
#### Git Clone
Clone this repository in to the Sublime Text 2 "Packages" directory, which is located where ever the 
"Preferences" -> "Browse Packages" option in sublime takes you.

#### Package Control
JsFormat is now included in the default repository channel for Package Control. It should show up in your install list
with no changes.

If it does not show up, or you are on an older version of Package Control:
Add https://github.com/jdc0589/JsFormat as a Package Control repository. JsFormat will show up in the
package install list.


## Key Binding

The default key binding is "ctrl+alt+f"

## Updates
* 12/3/2011 - Indentation character/count is now pulled from the current sublime settings
* 8/25/2011 - Added sublime-commands file. "Format: Javascript" now appears in the command palette
* 8/25/2011 - scrolls back to whatever line you were on prior to formatting the file (middle of screen) rather than leaving the view position at the top of the file after formatting.
            
### License
Copyright (C) 2012 Davis Clark

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.