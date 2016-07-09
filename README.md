# textpad

A simple online notepad, no WYSIWYG, no fancy stuff, just write. The text will live in your browser until you decide to delete or download it as a .txt file.

##[Try it!](http://textpad.surge.sh)

##Why? 

Another browser text editor...I know, i know. Just because i can and want to!
 
1. I find myself copy/pasting alot of text online, copy proofing something i want to publish on social media/comment feeds, or paste inside html templates i'm building.
2. This little app also helps keep me focused when doing research online, taking notes without switching between a text editor and the browser.
3. Inspired by others, and i wanted to really build something using [LocalStorage](https://developer.mozilla.org/en-US/docs/Web/API/Storage/LocalStorage).

##Thanks to:

- FileSaver.js - [https://github.com/eligrey/FileSaver.js](https://github.com/eligrey/FileSaver.js)
- Smoke.js - [https://github.com/hxgf/smoke.js](https://github.com/hxgf/smoke.js)
- Countable.js - [https://github.com/RadLikeWhoa/Countable](https://github.com/RadLikeWhoa/Countable)

These have been minified and included in app.js, without them half of TextPad's features wouldn't be possible.

##ChangeLog:

###Ver 1.1.5 (09-07-2016)

- Minor code organization(app.js)
- Changes needed to match online version(index.html)
-- Info text == online version
-- Added link to online Disclaimer page(app name issues)
-- Added Github star button
- Removed xmlns attribute from inline svg(index.html)
- Removed nav width, now 100% window(app.css)
- Added new alert/dialog icons(app.css)

###Ver 1.1.0 (02-07-2016)

- Added ability to store user theme setting

###Ver 1.0.0 (30-05-2016)

- Inicial realease
