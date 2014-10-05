---
layout: page
title: "Getting Started"
comments: false
sharing: false
footer: true
---

## Installing Packages

Packages are provided for Windows and Ubuntu/Debian Linux, or you can
install from the Python source.

### Windows

Download and run the
[Windows Installer](https://github.com/weecology/retriever/releases/download/v1.7.0/RetrieverSetup.exe).
This installer has been tested on Windows 7.

### Mac

Download the
[OS X App](https://github.com/weecology/retriever/releases/download/v1.7.0/retriever-app.zip).
Unzip the file and then double click on the App. Depending on your version of OS
X you may need to tell OS X that it is
[OK to install software from Anywhere](http://support.apple.com/kb/HT5290). After
installing the Retriever you may return this setting to its original value. The installer has been tested on OS X 10.7-10.9.

### Linux

[A Debian
package](https://github.com/weecology/retriever/releases/download/v1.7.0/python-retriever_1.7.0-1_all.deb)
is provided; If you're on a non-Debian based system, refer to the
instructions under Installing from Source.

## Installing from Source

To install the EcoData Retriever from source, you'll need:

-   Python version 2.7.1 or greater (not Python 3.x)
-   wxPython version 2.8 or greater; *Mac users need to use 2.9 or greater
-   xlrd

On Ubuntu, the following command will install all required dependencies:

    sudo apt-get install python-setuptools python-wxgtk2.8 python-xlrd

The following packages are optional:

-   PyMySQL (for MySQL)
-   sqlite3 (for SQLite)
-   pyscopg2 (for PostgreSQL)
-   pyodbc (for Microsoft Access - this option is only available on
    Windows)

To download and install the Retriever from source, use the following
commands (Windows users should use a Unix-like environment such as Git
bash or Cygwin):

1.  `wget https://github.com/weecology/retriever/archive/v1.7.0.tar.gz`
2.  `tar -xvzf retriever-src.tar.gz`
3.  `cd src`
4.  `sudo python setup.py install`

If you prefer to install the current master branch:

1.  `git clone git@github.com:weecology/retriever.git`
2.  `cd retriever`
3.  `sudo python setup.py install`

After installing, type `retriever` to launch.

## Using the Graphical User Interface

The first time you launch the EcoData Retriever, it will automatically
download all available Retriever scripts. You'll then be prompted to
choose a database system and enter your connection information. Once
this process is complete, you'll see the following screen:

![EcoData Retriever GUI](images/figure1.png)

You'll see each available dataset with citation information and a link
to the dataset website. Click on the box icon to start downloading the
data.

You can use the categories on the left to filter the data to show, for
example, only data from a specific taxonomic group (like Mammals in the
image above). You can also search for specific terms using Edit \> Find.

If you need to change the database management system that you are using
just select File \> Connection from the menu.

## Using custom scripts

You can also write your own scripts for datasets that aren't currently
included in the Retriever. Follow the [instructions for adding
datasets](scripting.html) and then place your custom script in either
the directory where you are running the Retriever or in a subdirectory
named \`\`scripts\`\`.
