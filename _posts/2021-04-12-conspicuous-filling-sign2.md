---
id: 658
title: 'NAK 5-333 and the so-called conspicuous filling sign'
date: '2021-04-12T11:34:34-06:00'
author: 'Dominik Wujastyk'
layout: post
guid: 'https://sushrutaproject.org/?p=658'
permalink: /2021/04/12/conspicuous-filling-sign2/
categories:
    - 'Textual notes'
---

In one of the Nepalese manuscripts on which this project is based, the fifteenth-century Nepalese MS, [MS Kathmandu NAK 5-333](https://www.panditproject.org/entity/102310/manuscript), there are mysterious characters at a few places. For example, on folio 371v:

<div class="wp-block-image"><figure class="aligncenter size-large">![](https://sushrutaproject.org/wp-content/uploads/2021/04/image-1024x165.png)<figcaption>Fol. 371v</figcaption></figure></div>they are the two similar characters on the fifth line from the top, in this enlargement:

<div class="wp-block-image"><figure class="aligncenter size-large">![](https://sushrutaproject.org/wp-content/uploads/2021/04/oo1.png)<figcaption>Fol. 371v</figcaption></figure></div>and another example

<div class="wp-block-image"><figure class="aligncenter size-large">![](https://sushrutaproject.org/wp-content/uploads/2021/04/oo2.png)<figcaption>Fol. 371r</figcaption></figure></div>Here, the surrounding word is pāke.

On folio 385v we have a line of them across the bottom side of a string-hole space:

<div class="wp-block-image"><figure class="aligncenter size-large">![](https://sushrutaproject.org/wp-content/uploads/2021/04/image-2.png)<figcaption>Fol. 385v</figcaption></figure></div>And on 396r we have another line in the same setting below a string-hole:

<div class="wp-block-image"><figure class="aligncenter size-large">![](https://sushrutaproject.org/wp-content/uploads/2021/04/image-3.png)<figcaption>Fol. 396r</figcaption></figure></div><div class="wp-block-image"><figure class="aligncenter size-large">![](https://sushrutaproject.org/wp-content/uploads/2021/04/image-4.png)<figcaption>F. 407r, not below a string-hole.</figcaption></figure></div>These symbols are not letters, since they don’t contribute to the surrounding text, but interrupt it. I have wondered whether they are the scribe expressing that his archetype has a string-hole at this place, perhaps, but I don’t see the symbols often enough for that. They occur rather rarely, every ten folios or so. The scribe uses other signs to mark missing or illegible akṣaras in his exemplar. He uses other signs to mark section or chapter endings. He uses other signs to fill up an unwanted space (like contemporary “this page deliberately empty”) or as an end-of-line hyphen. He uses other signs for exuberant decoration:

<div class="wp-block-image"><figure class="aligncenter size-large">![](https://sushrutaproject.org/wp-content/uploads/2021/04/image-5.png)<figcaption>NEWA FLOWER U+1145A</figcaption></figure></div>After posting a query about this symbol to the [INDOLOGY](http:/indology.info) forum on 11 April 2021 \[[archive link](https://list.indology.info/pipermail/indology/2021-April/054500.html)\], Prof. Birgit Kellner kindly sent us her observations of this and similar symbols in early Bengali-script manuscripts and permitted us to share them as [a blog post on this site](https://sushrutaproject.org/2021/04/12/kellner/). That the sign occurs in our fifteenth-century Nepalese MS shows that the sign was known by scribes beyond the Bihar/Bengal area.

For a general study of this (p. 265) and similar signs, see <span class="zp-InText-zp-ID--2579494-TVADSHUR--wp658 zp-InText-Citation loading" rel="{ 'pages': 'np', 'items': '{2579494:TVADSHUR}', 'format': '%a% (%d%, %p%)', 'brackets': '', 'etal': '', 'separator': '', 'and': '' }"></span>.

## Unicode representation

Following the Unicode Newa script encoding <span class="zp-InText-zp-ID--2579494-I5HZFUX3--wp658 zp-InText-Citation loading" rel="{ 'pages': 'np', 'items': '{2579494:I5HZFUX3}', 'format': '(%a%, %d%, %p%)', 'brackets': '', 'etal': '', 'separator': '', 'and': '' }"></span> , we initially considered provisionally encoding this filling character as

```
<g ref="#thaayjaayekaa">
```

 which is in fact defined in the unicode standard as follows:

```
  <encodingDesc>
            <charDecl>
                <glyph xml:id="thaayjaayekaa">
                    <localProp name="thaayjaayekaa" value="NEWA GAP FILLER"/>
                    <mapping type="PUA">U+1144E </mapping>
                </glyph>
            </charDecl>
        </encodingDesc>
```

This NEWA GAP FILLER character U+1144E displays as:<sub>![](https://sushrutaproject.org/wp-content/uploads/2021/07/Screenshot-from-2021-07-20-07-00-47.png) </sub>The Unicode standard notes that this FILLER character can be represented by a variety of different visual glyphs. Further useful discussion and examples in the context of the Unicode standard are given by <span class="zp-InText-zp-ID--2579494-QSXITKUF--wp658 zp-InText-Citation loading" rel="{ 'pages': 'np', 'items': '{2579494:QSXITKUF}', 'format': '%a% (%d%, %p%)', 'brackets': '', 'etal': '', 'separator': '', 'and': '' }"></span>. See especially figures 42, 43 and 50.

But none of these representations is quite the same as our “conspicuous filler” glyph. So we have decided, rather, to encode it locally as,

```
<g ref="#newa-old-gap-filler"/>
```

This is correctly interpreted by [Saktumiva](https://saktumiva.org) and a custom character is provided in the font used by Saktumiva, [Pedantic Indic](https://chchch.github.io/PedanticIndic/#devanagari).

## Bibliography

<div class="zp-Zotpress zp-Zotpress-InTextBib wp-block-group zp-Post-658" id="zp-InTextBib-zotpress-6135e86eac89dc004a596c01031678c5"> <span class="ZP_ITEM_KEY" style="display: none;">{2579494:TVADSHUR};{2579494:I5HZFUX3};{2579494:QSXITKUF}</span> <span class="ZP_STYLE" style="display: none;">chicago-author-date</span> <span class="ZP_SORTBY" style="display: none;">creator</span> <span class="ZP_ORDER" style="display: none;">asc</span> <span class="ZP_TITLE" style="display: none;"></span> <span class="ZP_SHOWIMAGE" style="display: none;"></span> <span class="ZP_SHOWTAGS" style="display: none;"></span> <span class="ZP_DOWNLOADABLE" style="display: none;"></span> <span class="ZP_NOTES" style="display: none;"></span> <span class="ZP_ABSTRACT" style="display: none;"></span> <span class="ZP_CITEABLE" style="display: none;"></span> <span class="ZP_TARGET" style="display: none;"></span> <span class="ZP_URLWRAP" style="display: none;"></span> <span class="ZP_FORCENUM" style="display: none;">0</span> <span class="ZP_HIGHLIGHT" style="display: none;"></span> <span class="ZP_POSTID" style="display: none;">658</span><div class="zp-List loading"><div class="zp-SEO-Content"></div></div></div>