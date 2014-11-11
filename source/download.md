---
layout: page
title: "Download"
comments: false
sharing: false
footer: true
---

## Windows

[Windows Executable](https://github.com/weecology/retriever/releases/download/v1.7.0/RetrieverSetup.exe)

## Ubuntu/Debian

[Ubuntu/Debian Package](https://github.com/weecology/retriever/releases/download/v1.7.0/python-retriever_1.7.0-1_all.deb)

## Mac

1\. Download the
[OS X App](https://github.com/weecology/retriever/releases/download/v1.7.0/retriever-app.zip)  
2\. Double click retriever-app.zip to unzip the file  
3\. Move the retriever.app file into the Applications folder  
4\. If you want to use the Retriever from the command line or from R you need to
add it to your path. You can do this by copying and pasting the following
command into the terminal, pressing enter, and entering your password when
asked:  
```
sudo -s 'echo "/Applications/retriever.app/Contents/MacOS" > /etc/paths.d/retrieverapp'
```

## Python Package Index

The retriever can also be installed using `pip`:

`pip install retriever`

On its own this only supports the command line interface. The GUI will only run
if you [install wxPython](http://wxpython.org/download.php) separately.

## Source

[Source Tarball](https://github.com/weecology/retriever/archive/v1.7.0.tar.gz)

## Development

[Master branch on GitHub](https://github.com/weecology/retriever)
