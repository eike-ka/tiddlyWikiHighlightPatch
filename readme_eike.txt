This is a patched tiddlywiki which adds gradle support to the highlightjs plugin.

To build it run

./tiddlywiki.js editions/highlightdemo --build index

The resulting file is

editions/highlightdemo/output/index.html

This can be opened to install the plugin to a tiddly wiki.

A commited generated file is in directory

build_eike/highlightdemo.html

To update the highlight plugin. e.g. to add additional languages:

- Go to the https://highlightjs.org/download/ page
- select languages to support
- Download the zip file
- Copy highlight.pack.js from zip file to file plugins/tiddlywiki/highlight/files/
- Open highlight.pack.js and search for the first hljs.registerLanguage
- Cut from here to the end of the file
- Replace the registerlanguages.pack.js files content with the cut data





