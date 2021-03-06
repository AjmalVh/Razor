#Razor Syntax Definition - Sublime Text 2 and 3
##Syntax Definition for Razor (cshtml) in Sublime Text 2 and 3

###Overview
Having been unable to find a Razor Syntax Definition for Razor anywhere, I decided to do this myself. While it's not perfect, it works much better than nothing. For more information on [Razor](http://www.asp.net/web-pages/tutorials/basics/2-introduction-to-asp-net-web-programming-using-the-razor-syntax), check out this great quick [reference](http://haacked.com/archive/2011/01/06/razor-syntax-quick-reference.aspx) done by Phil Haack (@haacked). Tested on Windows and Mac. Work with both Sublime Text 2 and Sublime Text 3

###Installation

**With the Package Control plugin**:
The easiest way to install this plugin is through Package Control, which can be found at this site: http://wbond.net/sublime_packages/package_control   

Once you install Package Control, restart Sublime Text and bring up the Command Palette (``Command+Shift+P`` on OS X, ``Control+Shift+P`` on Linux/Windows). Select "Package Control: Install Package", wait while Package Control fetches the latest package list, then search for Razor when the list appears. The advantage of using this method is that Package Control will automatically keep Razor plugin up to date with the latest version.

#####Manual Installation
**Mac OS X**: clone this to: ~/Users/{User}/Library/Application Support/Sublime Text 2/Packages/User. It should automatically recognize the syntax based on the file extension. 

You can also download the .zip file then in Sublime Text 2 go to Preferences -> Browse Packages -> (Packages directory will be opened in finder) copy the .zip file contents over to the /User directory (may have to overwrite existing files).

**Windows**: clone this to: %APPDATA%\Sublime Text 2\Packages\User which expands to something like 
`C:\Users\username\AppData\Roaming\Sublime Text 2\Packages\User` on Windows Vista/7/8/8.1


###Extend/Improve
Like I said, it's far from perfect, mostly because I've never done this before. I'm pretty new to JSON and Regex, so if you can do better, by all means! Check out the [Sublime Text](http://docs.sublimetext.info/en/latest/reference/reference.html) reference site for details.
