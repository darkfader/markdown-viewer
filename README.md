markdown-viewer
===============

Userscript to preview and print local markdown files using different themes.
Just drop your markdown-file in your browser and enjoy the nicely rendered text.

Markdown css files used to style the markdown are taken from [jasonm23](https://github.com/jasonm23/markdown-css-themes).
They are placed in the `docs` directory and served via github pages.

Only tested in Google Chrome with Tampermonkey atm!!

__Please note:__
To make the userscript work in Chrome/Tampermonkey you have to perform the following:

 * enable "Allow access to file URLs" for Tampermonkey in `chrome://extensions`
 * start Chrome with disabled _same origin policy_ (you should not do this), see [here](https://stackoverflow.com/a/6083677)

Taking these steps into account the userscript is rather unusable atm :(.

## Credits
 * [Markdown](https://daringfireball.net/projects/markdown/) was conceived by John Gruber.  
 * [showdown.js](http://markhuot.github.io/phocco/resources/showdown.js.html) by John Fraser is the JavaScript port of Markdown which converts your md-file to HMTL.  
 * [The CSS-files of jasonm23](https://github.com/jasonm23/markdown-css-themes) let the HTML look good. [Some changes](https://github.com/znegva/markdown-css-themes) were done by me.  
 * [Font Awesome by Dave Gandy](http://fontawesome.io) was used for the nice icons.
