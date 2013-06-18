Atlas Book Sample
=================

This repository holds a basic project skeleton that can be built through O'Reilly Atlas. We fork this repository whenever you create a new project in the Atlas UI, which means that you can also just fork it directly on GitHub when starting a new book.

Follow this README to learn more about the basic skeleton of an Atlas book.


atlas.json
----------

An Atlas repository must have a file called `atlas.json` in the repository root. This file is used to hold project metadata, the most important being the files to build.


Content
-------









* The repo needs an atlas.json file with a list of files to build


Atlas doesn't enforce any strict rules upon your HTML, other than the compiled file needs to be valid HTMLBook.
* Each individual .html file needs to be a valid html document, otherwise the WYSIWYG won't work. This means we can't have one file with an opening tag, and another file with the corresponding closing tag. You can easily split chapters up into multiple files, but each file needs to be valid HTML.


* chapter files can go in any subfolder, as long as you reference it in the atlas.json file (see file)
