# FirefoxCSS-Safari-theme
A Safari like them for Firefox 72+ MacOS

<p align="center">
  <img src="https://github.com/Pepitortue/FirefoxCSS-Safari-theme/blob/master/Showcase.png">
</p>
<p align="center">
  <img src="https://github.com/Pepitortue/FirefoxCSS-Safari-theme/blob/master/Showcase.gif">
</p>

## What is it
This is a Firefox theme for MacOS inspired by Safari. This theme is not meant to reproduce perfectly Safari.
This code contains a mix of code shared by people from r/FirefoxCSS and modifications I made.

## Installation
1. Copy the userChrome.css file into your Firefox profile directory.
To access this folder, go to about:profiles and click the "Open in Finder" button in front of the first "root directory" line. In the opened Finder window, open the "chrome" folder.
Restart Firefox.
2. Follow the same process with the userContent.css file
3. Restart Firefox

*Note : ShadowFox users only have to copy/paste the code at the end of their userChome.css and userContent.css files.*

### Additional
To enable the blur filter on the pop up URL menu, you need to set the `layout.css.backdrop-filter.enabled` to `true` in about:config

## TODO
* Pop up URL menu is not centered in the windows. Currently using @media keys.
* Pop up URL menu is invisible in about:newtab if URL bar is not selected. -> temporarily disabled the Darker Navbar when unhovered transition
* Strange behavior on tab overflox, pinned tabs borders are duplicated until their width is incremented by 1px. Unfortunately it is reseted everytime firefox is relaunched (but incrementation stay).

## Issues
This theme was tested with Firefox 72.0.2 on MacOS Catalina. Graphical differences might occur on other OS.
I will update the theme for every new Firefox release since this is my daily theme.
