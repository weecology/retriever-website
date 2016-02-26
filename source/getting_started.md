---
layout: page
title: "Getting Started"
comments: false
sharing: false
footer: true
---

## Installing Packages

The Retriever can be installed using Python's `pip` or by downloading
self-contained installers for Windows, OS X, and Ubuntu/Debian Linux.

Installers are available on the [Download page](download).

If you have Python installed and want to use pip:

`pip install retriever`

This will only install the command line interface.

## Using the Graphical User Interface

For information on using the graphical version of the Retriever see the
[GUI documentation](http://retriever.readthedocs.org/en/latest/guidocs.html).

## Using the Command Line Interface

See the [command line interface documentation](http://retriever.readthedocs.org/en/latest/introduction.html#using-the-command-line).

## Using the R package

The
[ecoretriever R package](https://cran.r-project.org/web/packages/ecoretriever/)
allows the EcoData Retriever to be used directly from R. After installing the
Retriever, install the R package using:

```
install.packages("ecoretriever")
```

See the
[rOpenSci tutorial](https://ropensci.org/tutorials/ecoretriever_tutorial.html)
and the
[documentation](https://cran.r-project.org/web/packages/ecoretriever/ecoretriever.pdf)
for information on using the R package.

## Using custom scripts

You can also write your own scripts for datasets that aren't currently included
in the Retriever. Follow the
[instructions for writing and loading scripts](http://retriever.readthedocs.org/en/latest/scripts.html)
and then place your custom script in either the directory where you are running
the Retriever or in a subdirectory named `scripts`.
