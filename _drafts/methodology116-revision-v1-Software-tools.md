---
id: 893
title: 'Software tools'
date: '2021-07-16T20:50:03-06:00'
author: 'Dominik Wujastyk'
layout: revision
guid: 'https://sushrutaproject.org/?p=893'
permalink: '/?p=893'
---

<div class="wp-block-columns is-layout-flex wp-container-core-columns-is-layout-102 wp-block-columns-is-layout-flex"><div class="wp-block-column is-layout-flow wp-block-column-is-layout-flow" style="flex-basis:33.33%"><figure class="wp-block-image size-large">![](https://sushrutaproject.org/wp-content/uploads/2021/07/Screenshot-from-2021-07-01-12-10-57.png)</figure></div><div class="wp-block-column is-layout-flow wp-block-column-is-layout-flow" style="flex-basis:66.66%">In selecting a software environment, this project has adopted the so-called [Unix philosophy](https://en.wikipedia.org/wiki/Unix_philosophy). While interesting debates surround this concept, what it means for the Sushruta Project is that we have adopted simple, short, clear, modular, and extensible tools wherever possible, with a predilection for open-access software. Conversely, we have preferred not to use large “workbench” programs or “integrated development environments” (IDE) that aim to create a total work environment for all aspects of editorial work. This policy has enabled us to select best-of-class tools for each of the separate tasks we undertake, from manuscript transcription to collation, communication, document creation, version control, project management and web publication. We are also free from a dependence on a single source of program maintenance. If one of our tools no longer meets our need, we can swap out just that component of the workflow for an alternative. It also allows project members some flexibility in choosing how they wish to work. The downside of this choice is that the working environment has several components, and that someone in the project must maintain a certain level of software expertise to get all the parts to work together and to move data between the different programs. The existence of standards such as Unicode and the TEI are critical in making this work smoothly.

</div></div><div class="wp-block-columns is-layout-flex wp-container-core-columns-is-layout-103 wp-block-columns-is-layout-flex"><div class="wp-block-column is-layout-flow wp-block-column-is-layout-flow" style="flex-basis:100%"></div></div>- Manuscript image display: whatever is provided with your operating system, or the photo display facilities in Dropbox or Nextcloud.
- [oXygen XML editor](https://www.oxygenxml.com/) for manuscript transcription. (Alternatives include [Atom](https://atom.io/), [emacs](https://www.gnu.org/software/emacs/), [jedit](http://plugins.jedit.org/plugins/?TEI), [etc](https://wiki.tei-c.org/index.php/Editors).)
- [SAKTUMIVA](http://saktumiva.org) by Charles Li. A platform for producing and publishing critical editions of Sanskrit texts. “[Reconstructing a Sanskrit text](https://chchch.github.io/sanskrit-alignment/docs/index.html)“: documentation of the alignment, collation and stemmatic methods in Saktumiva.   
    For further discussion of the methodology behind Saktumiva, see Li [2017](https://www.sidestone.com/bookviewer/9789088904837): 305-310 and Li [2018](https://www.repository.cam.ac.uk/bitstream/handle/1810/284085/limits_of_the_real.pdf?sequence=1&isAllowed=y), ch.4.
- [Quick Palaeographer ](https://www.istb.univie.ac.at/caraka/)by Charles Li. A browser-based tool for reading MS images and developing a catalogue of character shapes.
- [Filezilla](https://filezilla-project.org/) for document transfer to Saktumiva.
- [Github](https://github.com/) for document security, storage and versioning.
- [LaTeX](http://panditproject.org) for document preparation. Also [LibreOffice](https://www.libreoffice.org/), [Geany](https://www.geany.org/), [Typora](https://typora.io/). &lt;whisper&gt;Sometimes even [vi](https://en.wikipedia.org/wiki/Vi).&lt;/whisper&gt;
- [qdpm](https://qdpm.net/) for project management.

## Tools and projects not currently selected

The Sushruta Project team has evaluated many software solutions for use in this project. The following is a list of the most technically relevant that we have evaluated positively but decided against at the present time.

- [Transkribus](https://readcoop.eu/transkribus/), a platform for the transcription and searching of historical documents. Transkribus is a mature program that offers powerful features for the diplomatic transcription of manuscripts. In some contexts it could help a project like ours to provide a standardized interface for a team of MS transcribers. It has many features and veers towards being a totalizing environment. At the time of writing (July 2021) the TEI export is not a good fit for use with Saktumiva.
- [T-Pen](http://t-pen.org/TPEN/), provides similar functionality to Transkribus: a team of inputters could use a convenient interface to transcript MSS diplomatically.
- [Edition Visualization Technology](http://evt.labcd.unipi.it/) is “a tool specifically designed to create digital editions from XML-encoded texts.” EVT reads a TEI-encoded critical edition (using parallel segmentation) and displays it with several useful add-on features. It can handle hot-linking between text and manuscript image. There is a [demo available of the text of Avicenna’s Logica](http://evt.labcd.unipi.it/demo/evt2-beta2/avicenna/index.html#/readingTxt?d=doc_1&p=C-112v&s=text-body-div&e=critical).
- [Textual Communities](https://textualcommunities.org/app/community/?id=5ae4492bb6bf889b25d8418f&route=view&document=5d437ea2e01ff5326602c0de&page=5d437e5b1d393e0000ee31b6), by Peter Robinson (University of Saskatchewan). Textual Communities offers a rich environment and toolset for transcribing and collating manuscripts and producing digital editions of pre-modern texts. In many ways it is similar to Saktumiva. But Textual Communities is more focussed on European-language sources and does not provide the specific Sanskrit-language features of Saktumiva. However, Textual Communities has social-network aspects that are important and it could certainly be used for an Indic-language project.
- [Ekdosis](https://ctan.org/pkg/ekdosis?lang=en), a LaTeX macro package for typesetting critical editions, similar in purpose to [EDMAC](https://github.com/wujastyk/edmac) (and derivatives). Ekdosis offers a rigorous syntax for manually entering one’s text and critical apparatus. But a benefit of this syntax is that output can be as a typeset PDF or as TEI XML with the apparatus expressed as parallel segmentation.
- [Textgrid](https://de.dariah.eu/en/web/guest/textgridlab), an [Eclipse](https://www.eclipse.org/ide/) environment developed under the aegis of the European [DARIAH](https://de.dariah.eu/en/home) consortium. No new release of Textgrid has appeared since 2018. Although the descriptions of Textgrid seem to offer promise, and it shows awareness of important international standards, the documentation is poor and the purpose of the software is opaque.