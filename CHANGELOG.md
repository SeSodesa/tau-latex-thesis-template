# Changelog

This file lists the changes that have been made to this project along its
development. Note that as of version `2.0`, the changes should also be
discoverable via the Git tags of the project.

###### Version 2.2

* Added support for compiling the project with `lualatex`, in addition to
  `pdflatex`.

* Note that the package `axessibility` is not loaded if `lualatex` is used, as
  the accsupp branch of said package does not support `lualatex`.

###### Version 2.1

* Minor change in Finnish terminology in [`tauthesis.cls`](./tauthesis.cls).

###### Version 2.0

* Overhaul of the citation and glossary systems; more user control.
* Added support for APA 7 and IEEE style citations.
* Cleaned up tauthesis.cls.
* Published in GitHub for better issues handling mechanism.
* Added support for basic accessibility features:
  * Alt texts for images using \pdftooltip{...}{...}
  * Specifying mandatory document metadata
  * Alt texts for mathematics automatically in compatible environments

###### Version 1.6

* Overall cleaning, better bibliography sorting and examiner functionalities. Major performance and math font improvements!

###### Version 1.5

* Better sorting and display of the bibliography entries, unsorted and last name first.

###### Version 1.4

* Minor terminology fixes.

###### Version 1.3

* Some updates to appearance.
* Removed front matter entries from ToC.
* Fixed a problem with default document class options.

###### Version 1.2

* Updated the template to conform to new appearance guidelines.
* Increased the width of the glossary for it to take less space.
* Added compilation instructions to main.tex as well.
* Fixed encoding issues relating to listings fix for Scandinavian letters in code comments.

###### Version 1.1

* Replaced the glossaries package option xindy to automake. Now the template does not require Perl to be installed.
* Added instructions how to compile the thesis using this template into the conclusion text.

###### Version 1.0

* First published template.