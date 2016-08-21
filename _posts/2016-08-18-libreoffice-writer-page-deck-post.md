---
layout: post
title: "Page Deck for Writer"
description: Description of panels and their features present in the upcoming Page Deck for Writer
headline: LibreOffice 5.3
category: Sidebar-documentation
tags: [Sidebar, LibreOffice, page, deck]
imagefeature: WriterPageDeck/cover.png
comments: true
share: true
published: true
---
One of the major improvements, in the upcoming LibreOffice 5.3 (scheduled to release on January 30, 2017), is the Page Deck for Writer. The deck hosts four panels - Page Format Panel, Page Style Panel, Page Header Panel, and the Page Footer Panel - to bring you the most commonly used page properties. This post aims to describe all the aforementioned panels and the features they provide.

The entire enhancement report can be found <a href="https://bugs.documentfoundation.org/show_bug.cgi?id=83830" target="_blank">*here*</a>. I myself have been working on this, with the help of my mentors - bubli (**Katarina Behrens**), and jay (**Yousuf Philips**).

<h2>Page Format Panel</h2>
<ul>
    <li>
        Size dropdown to easily select standard page sizes.
        <center><a href="{{ site.url }}/images/WriterPageDeck/format1.png"><img src="{{ site.url }}/images/WriterPageDeck/format1.png"></a></center>
    </li>
    <li>
        Width and Height spinboxes to customize page size.
        <center><a href="{{ site.url }}/images/WriterPageDeck/format2.png"><img src="{{ site.url }}/images/WriterPageDeck/format2.png"></a></center>
    </li>
    <li>
        Orientation listbox to choose between Portrait and Landscape mode.
        <center><a href="{{ site.url }}/images/WriterPageDeck/format3.png"><img src="{{ site.url }}/images/WriterPageDeck/format3.png"></a></center>
    </li>
    <li>
        Margins listbox to select preset page margins. Available presets are - 
        <ul>
            <li>None</li>
            <li>Narrow (1.27 cm all around)</li>
            <li>Moderate (lr: 1.91cm, tb: 2.54cm)</li>
            <li> Normal 0.75" (2 cm all around) </li>
            <li> Normal 1" (2.54cm all around) </li>
            <li> Normal 1.25" (lr: 3:18cm, tb: 2.54cm) </li>
            <li> Wide (lr: 5.08cm, tb: 2.54cm) </li>
            <li> Mirrored (inner: 3.18cm, outer: 2.54cm, tb: 2.54cm, page layout: mirrored)</li>
        </ul>
        lr = left + right
        <br>
        tb = top + bottom
        <center><a href="{{ site.url }}/images/WriterPageDeck/format4.png"><img src="{{ site.url }}/images/WriterPageDeck/format4.png"></a></center>
    </li>
</ul>

<h2>Page Styles Panel</h2>
<ul>
    <li>
        Numbering dropdown to select numbering format of the pages. Corresponds to the 'format' option under Layout settings in Page Format Dialog.
        <center><a href="{{ site.url }}/images/WriterPageDeck/styles1.png"><img src="{{ site.url }}/images/WriterPageDeck/styles1.png"></a></center>
    </li>
    <li>
        Dropdown to change background of the page. Currently 5 settings - None (no background), Color (Solid Fill), Gradient, Hatching, and Bitmap
        <center><a href="{{ site.url }}/images/WriterPageDeck/styles2.png"><img src="{{ site.url }}/images/WriterPageDeck/styles2.png"></a></center>
    <ul>
        <li>
            Pattern Setting
        </li>
        <li>
            Color Setting
                <center><a href="{{ site.url }}/images/WriterPageDeck/styles2a.png"><img src="{{ site.url }}/images/WriterPageDeck/styles2a.png"></a></center>   
        </li>
        <li>
            Gradient Setting - Make a gradient with two colors, which gives added customization compared to presets
                <center><a href="{{ site.url }}/images/WriterPageDeck/styles2b.png"><img src="{{ site.url }}/images/WriterPageDeck/styles2b.png"></a></center>
        </li>
        <li>
            Hatching Setting
                <center><a href="{{ site.url }}/images/WriterPageDeck/styles2c.png"><img src="{{ site.url }}/images/WriterPageDeck/styles2c.png"></a></center>
        </li>
        <li>
            Bitmap Setting
                <center><a href="{{ site.url }}/images/WriterPageDeck/styles2d.png"><img src="{{ site.url }}/images/WriterPageDeck/styles2d.png"></a></center>
        </li>
    </ul>
    </li>
    <li>
        Layout Setting to select Page Layout - Right and Left, Mirrored, Only Left, and Only Right.
        <center><a href="{{ site.url }}/images/WriterPageDeck/styles3.png"><img src="{{ site.url }}/images/WriterPageDeck/styles3.png"></a></center>
    </li>
    <li>
        Columns setting to select frequently used page column layouts.
        <center><a href="{{ site.url }}/images/WriterPageDeck/styles4.png"><img src="{{ site.url }}/images/WriterPageDeck/styles4.png"></a></center>
    </li>
</ul>

<h2>Page Header Panel and Page Footer Panel</h2>
<p>Both these panels provide similar functionalities, so I'll be describing them in one go</p>
<ul>
    <li>
        Checkbox to enable header (or footer).
        <figure class="half">
            <a href="{{ site.url }}/images/WriterPageDeck/hf1a.png"><img src="{{ site.url }}/images/WriterPageDeck/hf1a.png"></a>   
            <a href="{{ site.url }}/images/WriterPageDeck/hf1b.png"><img src="{{ site.url }}/images/WriterPageDeck/hf1b.png"></a>
        </figure>
    </li>
    <li>
        Margins setting to set the left and right margins of the header (or footer).
        <center><a href="{{ site.url }}/images/WriterPageDeck/hf2a.png"><img src="{{ site.url }}/images/WriterPageDeck/hf2a.png"></a>   <a href="{{ site.url }}/images/WriterPageDeck/hf2b.png"><img src="{{ site.url }}/images/WriterPageDeck/hf2b.png"></a></center>
    </li>
    <li>
        Dropdown to change the spacing of the header (or footer) from the top (or bottom) of editable area of the document.
        <center><a href="{{ site.url }}/images/WriterPageDeck/hf3a.png"><img src="{{ site.url }}/images/WriterPageDeck/hf3a.png"></a>   <a href="{{ site.url }}/images/WriterPageDeck/hf3b.png"><img src="{{ site.url }}/images/WriterPageDeck/hf3b.png"></a></center>
    </li>
    <li>
        The Margins and Spacing presets are similar, and currently 8 presets are present:
        <ul>
            <li>None</li>
            <li>Extra Small (0.16 cm)</li>
            <li>Small (0.32 cm)</li>
            <li>Small Medium (0.64 cm)</li>
            <li>Medium (0.95 cm)</li>
            <li>Medium Large (1.27 cm)</li>
            <li>Large (1.9 cm)</li>
            <li>Extra Large (2.54 cm)</li>
        </ul>
    </li>
    <br>
    <li>
        Setting to set same content for headers or footers on different pages of the document. There are four settings which are available -
        <ul>
            <li>All Pages - Sets the same header or footer on all the pages of the document</li>
            <li>First Page - Sets a common header or footer to all pages except the first page of the document</li>
            <li>Left and Right Page - Sets separate headers or footers for Left and Right sided pages.</li>
            <li>First, Left and Right - First page has a unique header (or footer), followed by separate headers (or footers) for Left and Right sided pages</li>
        </ul>
        <center><a href="{{ site.url }}/images/WriterPageDeck/hf4a.png"><img src="{{ site.url }}/images/WriterPageDeck/hf4a.png"></a>   <a href="{{ site.url }}/images/WriterPageDeck/hf4b.png"><img src="{{ site.url }}/images/WriterPageDeck/hf4b.png"></a></center>
    </li>
</ul>