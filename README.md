# MarkdownNotes

MarkdownNotes is a self hosted tool for organizing notes, files, lists, ideas by using markdown syntax.

![MarkdownNote Screenshot](https://github.com/SSilence/markdownnotes/raw/master/screenshot_1.jpg "MarkdownNote Screenshot")

## requirements

* PHP Webspace (just 4 a small backend script, runs everywhere with PHP5+)
* all modern Browsers and on Internet Explorer 11+
* mobile Browsers

## installation 

1. Download latest stable release ZIP file from https://github.com/SSilence/markdownnotes/releases and unzip
2. Upload all files of this folder (IMPORTANT: also upload the invisible .htaccess files)
3. Make the directories data/files and data/pages writeable
4. If you are using MarkdownNotes on a subpath (e.g. http://example.com/markdownnotes) then add in .htaccess the line ``RewriteBase /markdownnotes/`` and add in index.html ``<base href="/markdownnotes">``
5. MarkdownNotes saves all data in files in the data dir. No database is necessary.

## screenshots

![MarkdownNote Screenshot](https://github.com/SSilence/markdownnotes/raw/master/screenshot_2.jpg "MarkdownNote Screenshot")

![MarkdownNote Screenshot](https://github.com/SSilence/markdownnotes/raw/master/screenshot_3.jpg "MarkdownNote Screenshot")

## credits

Copyright (c) 2019 Tobias Zeising, tobias.zeising@aditu.de  
https://www.aditu.de  
Licensed under the GPLv3 license

Special thanks to the great programmers of this libraries which will be used:

* Angular: https://angular.io/
* Clarity: https://vmware.github.io/clarity/
* ShowdownJS: https://github.com/showdownjs/showdown
* SimpleMDE: https://simplemde.com/
* highlightjs: https://highlightjs.org/
* ngx-clipboard: https://github.com/maxisam/ngx-clipboard
* ngx-file-drop: https://github.com/georgipeltekov/ngx-file-drop

Icon Source (design by Freepik.com): https://creativenerds.co.uk/freebies/80-free-wildlife-icons-the-best-ever-animal-icon-set/
