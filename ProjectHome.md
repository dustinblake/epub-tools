# About epub-tools #

epub-tools is a collection of open source (BSD) tools for generating and managing EPUB documents, including conversions from:

  * Word
  * RTF
  * DocBook
  * TEI
  * FictionBook

Developers are encouraged to try out the tools and implement them in their own projects.

_Last updated: December 14, 2010_

## What is EPUB? ##

EPUB is the name for the e-book standard documented by the [International Digital Publishing Forum](http://www.idpf.org/) (IDPF).  It is a packaged set of XML documents, metadata and other media that make up a digital book.

## Sub-projects ##

### docbook2epub ###

docbook2epub is a Python/XSLT application to convert a DocBook XML document to ePub.

**The current version is 1.0.4**

#### Requirements ####

  1. Python 2.4 or greater
  1. The [lxml Python library](http://codespeak.net/lxml/)
  1. The DocBook XSLT (version including the epub module, >= 1.74.2)
  1. setuptools

#### Download ####

Packaged zip versions are always available from the [downloads page](http://code.google.com/p/epub-tools/downloads/list).

You may also check out the latest version from source code via [subversion](http://code.google.com/p/epub-tools/source/checkout).

### EPUBGen ###

Contributed by Adobe

EPUBGen (rtf2epub, word2epub, fb2epub)

rtf2epub, word2epub and fb2epub are Java applications to convert their
respective file types to ePub.

The current version is 0.1.0

Requirements

  1. JDK 1.5 or greater
  1. (fb2epub additional requirements)
  1. Apache Commons FileUpload
  1. Apache Commons IO
  1. log4j

### tei2epub ###

tei2epub is a Python/XSLT application to convert a TEI XML document to ePub.

**The current version is 1.0b2**

As of version 1.0b, epubcheck is no longer included.

#### Requirements ####

  1. Python 2.4 or greater
  1. The [lxml Python library](http://codespeak.net/lxml/)

#### Download ####

Packaged zip versions are always available from the [downloads page](http://code.google.com/p/epub-tools/downloads/list).

You may also check out the latest version from source code via [subversion](http://code.google.com/p/epub-tools/source/checkout).

#### Limitations ####

  * Images, CSS and other media _may_ work, but this has not been tested.
  * Very large TEI documents may convert slowly. This issue is known but has not been completely addressed.