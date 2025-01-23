---
id: 1124
title: Methodology
date: '2021-12-17T14:07:55-07:00'
author: 'Dominik Wujastyk'
layout: revision
guid: 'https://sushrutaproject.org/?p=1124'
permalink: '/?p=1124'
---

<div class="wp-block-image"><figure class="alignleft size-large">![](https://sushrutaproject.org/wp-content/uploads/2021/07/Screenshot-from-2021-07-01-12-10-57.png)</figure></div>In selecting a software environment, this project has adopted the so-called [Unix philosophy](https://en.wikipedia.org/wiki/Unix_philosophy). While interesting debates surround this concept, what it means for the Sushruta Project is that we have adopted simple, short, clear, modular, and extensible tools wherever possible, with a predilection for open-access software. Conversely, we have preferred not to use large “workbench” programs or “integrated development environments” (IDE) that aim to create a total work environment for all aspects of editorial work. This policy has enabled us to select best-of-class tools for each of the separate tasks we undertake, from manuscript transcription to collation, communication, document creation, version control, project management and web publication. We are also free from a dependence on a single source of program maintenance. If one of our tools no longer meets our need, we can swap out just that component of the workflow for an alternative. It also allows project members some flexibility in choosing how they wish to work. The downside of this choice is that the working environment has several components, and that someone in the project must maintain a certain level of software expertise to get all the parts to work together and to move data between the different programs. The existence of standards such as Unicode and the TEI are critical in making this work smoothly.

## Software tools currently in use

### Manuscript display

Whatever is provided with your operating system, or the photo display facilities in Dropbox or Nextcloud. Or Quick Palaeographer (see below).

### Manuscript transcription

[oXygen XML editor](https://www.oxygenxml.com/). Alternatives we have evaluated include [Atom](https://atom.io/), [emacs](https://www.gnu.org/software/emacs/), [jedit](http://plugins.jedit.org/plugins/?TEI), [xmlcopyeditor](https://xml-copy-editor.sourceforge.io/), [FairCopy](https://www.faircopyeditor.com/en/), etc. But oXygen consistently offers better stability, TEI support, online help and validation. oXygen is a commercial product, but academic licenses are relatively inexpensive.

### Manuscript collation and critical edition formatting

[SAKTUMIVA](http://saktumiva.org) by Charles Li. A platform for producing and publishing critical editions of Sanskrit texts. For documentation, see “[Reconstructing a Sanskrit text](https://chchch.github.io/sanskrit-alignment/docs/index.html)“: documentation of the alignment, collation and stemmatic methods in Saktumiva. For further discussion of the methodology behind Saktumiva, see Li [2017](https://www.sidestone.com/bookviewer/9789088904837): 305-310 and Li [2018](https://www.repository.cam.ac.uk/bitstream/handle/1810/284085/limits_of_the_real.pdf?sequence=1&isAllowed=y), ch.4.

### Palaeographical study

[Quick Palaeographer ](https://github.com/chchch/quick-palaeographer)by Charles Li. A browser-based tool for reading MS images and developing a catalogue of character shapes.

### File transfer

[Filezilla](https://filezilla-project.org/) for document transfer to Saktumiva.

### Document library

[Github](https://github.com/) provides our system for document sharing, collaborative editing, security, archiving and versioning. It is open to the public.

### Document writing and publishing

[LaTeX](https://www.latex-project.org/) for document preparation. Team members variously also use their favourite writing tools, including [LibreOffice](https://www.libreoffice.org/), [Geany](https://www.geany.org/), [Typora](https://typora.io/), and [Sublime text](https://www.sublimetext.com/). &lt;whisper&gt;Sometimes even [vi](https://en.wikipedia.org/wiki/Vi).&lt;/whisper&gt;. [Pandoc](https://pandoc.org/) is used to convert documents if necessary.

### Project management

[Qdpm](https://qdpm.net/) for project management.