Atlas Book Sample
=================

This repository holds a basic project skeleton that can be built through O'Reilly Atlas. We fork this repository whenever you create a new project in the Atlas UI, which means that you can also just fork it directly on GitHub when starting a new book.

Follow this README to learn more about the basic skeleton of an Atlas book.


atlas.json
----------

An Atlas repository must have a file called `atlas.json` in the repository root. This file is used to hold project metadata, the most important being the files to build.


Content
-------

The Atlas build system tries not to enforce strict rules on the way you write your content. That being said, here's a few things to keep in mind:

* You can write in normal HTML, Markdown, or Asciidoc. Allowed file extensions are: `.html`, `.md`, `.markdown`, `.asc`, and `.asciidoc`

* Markdown and Ascidoc will be compiled into HTMLBook..... MORE

* Each file must be or compile to valid HTML. The content `<p>Hello` is not a valid file, but `<p>Hello</p>` is.

* You can have files in any subfolder, as long as you specify the relative path to the folder in the `files` array.

