## Overview

Chrome browser extension created to deface site naurok.com.ua

## Installation

### Get code

1. Open terminal (Ctrl+Alt+t).
2. Run command:
```
git clone git@github.com:VladSavitsky/nu.git ~/projects/nu
cd ~/projects/nu;
ls -la;
```
3. Review code.

### Add to browser

1. Open Chrome browser.
2. Type 'chrome://extensions' in address bar
3. Click 'Developer Mode' checkbox at the top left corner.
3. Click 'Load unpacked' button (right top corner).
4. Specify path to folder with this extension. Eg., ~/projects/nu.


## Development

### Reload extension

4. Open 'chrome://extensions' in browser.
5. Click reload-button at 'Deface Naurok' extension.
6. Open https://naurok.com.ua site or any subpage.
7. Refresh page (Ctrl+r, F5).


### Change CSS

1. Open ~/projects/nu/css/styles.css
2. Add/Update CSS rules.
3. Save changes.
4. [Reload extension](#reload-extension)

Read more:
* https://w3schoolsua.github.io/css/index.html


### Change Javascript

1. Open ~/projects/nu/js/content.js
2. Add/Update Javascript code.
3. Save changes.
4. [Reload extension](#reload-extension)

Read more:
* https://w3schoolsua.github.io/js/index.html



## CSS

* CSS class. Starts from dot. For example: '.homepage'.
* CSS Id. Starts with '#'. For example: '#mainpage'.
* Rule:
```
#homepage {
  color: red;
  border: 1px solid blue !important;
}
```
* CSS Rule weight:
  * https://canonium.com/articles/css-understanding-weight-selectors/
  * https://habr.com/ru/articles/137588/
  * https://htmlacademy.ru/blog/css/which-selector
  * https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity
  * https://www.digitalocean.com/community/tutorials/css-understanding-specificity-in-css


