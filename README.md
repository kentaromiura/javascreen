javascreen
==========

javascript snippet pretty render to png

Did you ever need to make a presentation using powerpoint, keynote or google docs?

I feel the need to put some short javascript example, but I feel like that opening a browser or any ide,
loading the snippet in it, print screen and cut only the part which interested me, was somewhat boring.

So, here javascreen!

javascreen is based on some opensource tools:

* @alexgorbatchev [SyntaxHighlighter](https://github.com/kentaromiura/SyntaxHighlighter)
* @kamicane [clint](https://github.com/kamicane/clint)
* [phantomjs](http://phantomjs.org/)
* @sgentle [phantomjs-node](https://github.com/sgentle/phantomjs-node)

INSTALL:
==========
This tool uses the phantomjs to node.js bridge, you need to have phantomjs installed.
I added the osx phantom executable to be sure that in the future the tool continue to work

to run you must have node.js ready and up to date, and npm installed.

then you can type:

npm install clint

npm install phantom

SYNTAX:
==========

./javascreen
  --help, -h           : general usage information.
  --source, -s         : javascript source.
  --destination, -d    : file to save.
  --viewportWidth, -x  : viewport width (default: 800)
  --viewportHeight, -y : viewport height (default: 600)


EXAMPLE:
==========
./javascreen -s javascreen -d javascreen.png -x 1280
./javascreen -s example.js
./javascreen -s example2.js -x 1280


