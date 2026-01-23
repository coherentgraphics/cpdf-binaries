(CPDF 2.9 BETA)
===============

CPDF 2.9 Beta binaries can be downloaded here: https://coherentpdf.com/beta/Cpdf-2.9-beta-binaries.zip

Not a substitute for stable v2.8.1/v2.8.2, for which see the following instructions:

cpdf-binaries
=============

**Download the "master" zip from https://github.com/coherentgraphics/cpdf-binaries/archive/master.zip. Do not download
a versioned tag.**

PDF Command Line Tools binaries for Linux, Mac, Windows.

Cpdf is distributed under the AGPL - see LICENSE.md. If you are unable to abide
by the terms of the AGPL, you will need a commercial license.

For commercial licenses, email
[contact@coherentgraphics.co.uk](mailto:contact@coherentgraphics.co.uk) or
visit [https://www.coherentpdf.com/](https://www.coherentpdf.com/)

Cpdf may be available in your package manager:

| Operating system    | Command
| ------------------- | -------
| Windows Winget      | `winget install cpdf`
| Windows Chocolatey  | `choco install cpdf`
| MacOS               | `brew install cpdf`
| Linux Fedora        | `dnf install cpdf`
| Linux RHEL          | `dnf install cpdf` (must have 'EPEL' repository configured)
| Linux Centos Stream | `dnf install cpdf` (must have 'EPEL' repository configured)
| Linux Ubuntu        | `apt-get install cpdf` (must have 'universe' repository configured)
| Linux Debian        | `apt-get install cpdf`
| Linux Arch          | AUR package `cpdf`
| Linux Gentoo        | `emerge app-text/cpdf`
| Linux NixOS         | `nixshell -p OCamlPackages.cpdf`
| Linux Alpine        | apk add cpdf

Keep up to date by joining the very low volume cpdf-announce mailing list:

https://groups.google.com/g/cpdf-announce/

Functionality
---

* Quality Split and Merge, keeping bookmarks. Extract pages. Split on Bookmarks.
* Encrypt and Decrypt (including AES 128 and AES 256 encryption)
* Scale, rotate, crop and flip pages. Scale pages to fit.
* Copy, Remove and Add bookmarks
* Stamp logos, watermarks, page numbers and multiline text. Transparency.
* Embed TrueType fonts when adding text
* Supports Unicode UTF8 text input and output
* Make PDF-based presentations
* Put multiple pages on a single page
* List, copy, set, or remove annotations
* Read and set document information and metadata
* Add and remove file attachments to document or page.
* Thicken hairlines, blacken text, make draft documents
* Reconstruct malformed files
* Detect missing fonts, low resolution images
* Export and import PDF files in JSON format
* Build table of contents
* Convert text to PDF
* Draw on PDF files with graphics and text
* Create and process PDF/UA-1 and PDF/UA-2 files
* Process images to, for example, reduce resolution
* Rasterize PDF files

Documentation
---

PDF Manual:

[http://www.coherentpdf.com/cpdfmanual272.pdf](http://www.coherentpdf.com/cpdfmanual.pdf)

Examples:

[http://www.coherentpdf.com/usage-examples.html](http://www.coherentpdf.com/usage-examples.html)

Website:

[http://www.coherentpdf.com/](http://www.coherentpdf.com)


To Install
---

The program cpdf (or cpdf.exe for Windows) is a single executable with no
dependencies. Copy it to somewhere suitable on your platform.

The last version of cpdf compatible with Windows XP is v2.2.1.

MacOS: The executable is codesigned, but not notarized. If it refuses to run
the first time, go to System Preferences --> Security & Privacy and click
"Allow anyway". Instructions:

[https://www.coherentpdf.com/mac.html](https://www.coherentpdf.com/mac.html)


C/C++/Python/.NET/Java API
---

An API version of these tools is available:

C/C++ source: [https://github.com/johnwhitington/cpdflib-source](https://github.com/johnwhitington/cpdflib-source)

C/C++ binaries: [https://github.com/coherentgraphics/cpdflib-binary](https://github.com/coherentgraphics/cpdflib-binary)

Python: [https://github.com/coherentgraphics/python-libcpdf](https://github.com/coherentgraphics/python-libcpdf)

Java: [https://github.com/coherentgraphics/jcpdf](https://github.com/coherentgraphics/jcpdf)

.NET: [https://github.com/coherentgraphics/dotnet-libcpdf](https://github.com/coherentgraphics/dotnet-libcpdf)


Coherentpdf.js
---

A JavaScript implementation for node and the browser is available:

[https://github.com/coherentgraphics/coherentpdf.js](https://github.com/coherentgraphics/coherentpdf.js)


Support
---

Raise an issue in this github repository, or email
contact@coherentgraphics.co.uk

For commercial licenses, email
[contact@coherentgraphics.co.uk](mailto:contact@coherentgraphics.co.uk) or
visit [https://www.coherentpdf.com/](https://www.coherentpdf.com/)
