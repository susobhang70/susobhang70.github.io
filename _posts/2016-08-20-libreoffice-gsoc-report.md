---
layout: post
title: "GSoC Final Report"
description: Summary of the entire work done on 'Review of Sidebar and it's functionality' for LibreOffice during GSoC 2016
headline: Google Summer of Code 2016
category: GSoC-Report
tags: [GSoC, report, Sidebar, LibreOffice]
imagefeature: gsoc_1.svg
comments: true
share: true
featured: true
published: true
---
As Google Summer of Code 2016 draws to a close, I'd like to summarize my work  for LibreOffice on the project - 'Review of Sidebar and it's functionality'. I had an awesome experience working with the LibreOffice community, under the mentorship of two amazing people - **Katarina Behrens** and **Yousuf Philips**.

This post aims at linking and listing out all the feature milestones developed during my project and the relevant commits, along with the goals missed and work to be done in the future.

##Milestones Achieved##
<ol>
    <li>
        <b>Writer Page Deck</b> - You can read the enhancement report <a href="https://bugs.documentfoundation.org/show_bug.cgi?id=83830" target="_blank"><i>here</i></a> and the blog post describing the feature <a href="/sidebar-documentation/libreoffice-writer-page-deck-post/" target="_blank"><i>here</i></a>.
        <h4>Commits</h4>
        <ul>
            <li><a href="https://cgit.freedesktop.org/libreoffice/core/commit/?id=8b99402338773150fc0c8c6f894eb610e056d79e" target="_blank">tdf#83830: Page Format Panel</a></li>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=0d66c76fc61c09df17b0a1bebbcc5270df267117' target="_blank">tdf#83830: Change Page Deck Icon and Tooltip</a></li>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=3e19a763b95c45c275d15356ff5531e855cfcb03' target="_blank">tdf#83830: Removal of Page Margin Panel</a></li>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=656513d15116a3c6feeadc6a3353a304e0b3ef2b' target="_blank">tdf#83830: Moved margin preset control to Format Panel</a></li>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=b461236af355d8f504064ac6cfe259b9f8a7b01e' target="_blank">tdf#83830: Page Header Panel &amp; Page Footer Panel</a></li>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=3881fffe4233ce3aa02051b205c114c1cb520d67' target="_blank">tdf#83830: Page Styles Panel</a></li>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=dd1528b81f4c90c1db8f8eeb38bacc727490c6b6' target="_blank">tdf#83830: Remove experimental status from Page Deck</a></li>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=be40d4e7102d79d1e3aac5771869585cd1545379' target="_blank">tdf#83830: Add None as Margin Preset in Format Panel</a></li>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=1420b5765b4b1261c50b11fe7d0355ca7ca692b7' target="_blank">tdf#83830: Adjust alignment of Writer Tab Panels</a></li>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=66636aeb7d2a6da8f409d17610f62be875e9bb64' target="_blank">Tweak pagesize listbox Optimal size</a></li>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=b9592bbea315e04da36a1a26e687490ea93c4cc6' target="_blank">tdf#83830: Writer page deck and panels changed to non-contextual</a></li>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=6f9f401c94f7381880659a7641396c8173fcce6f' target="_blank">tdf#83830: Tweaks to page header and footer panels</a></li>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=f8b734a4e2b235c12e86d84c7691e39d05786032' target="_blank">tdf#83830 Change 'Margin' to 'Margins' in Page Format Panel</a></li>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=451ad09dcb07487dfd0cec58d315595c46863bc4' target="_blank">tdf#83830: Numbering dropdown set to 6 lines, label adjustments</a></li>
            <li><a href='https://gerrit.libreoffice.org/28104' target="_blank">Use SpacingListbox in sw</a></li>
            <li><a href='https://gerrit.libreoffice.org/28218' target="_blank">tdf#83830: Use samecontentlistbox in Header/Footer Panel</a></li>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=3ac60abd6f487a32fa605c1761f5f7752f1125cb' target="_blank">tdf#83830: Limit width of color/gradient listbox to 150px</a></li>
        </ul>
    </li>
    <br>
    <li>
        <b>Slide/Page Properties Panel for Draw and Impress</b> - You can read the enhancement report <a href="https://bugs.documentfoundation.org/show_bug.cgi?id=89466" target="_blank"><i>here</i></a> and the blog post describing the features <a href="/sidebar-documentation/libreoffice-background-panel-post" target="_blank"><i>here</i></a>.
        <h4>Commits</h4>
        <ul>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=833088b18015381dc8f90e4e868f96b7e882334f' target="_blank">tdf#89466 Fix update of elements and add listener in slidebg</a></li>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=b0a9ba98ba83154680f8aea0fd0e58b85e2cfb04' target="_blank">tdf#86759 and tdf#89466: Enable Page Background Panel for Draw</a></li>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=82111a5f8206ce05fc762db14f4b066ce23d6f07' target="_blank">Add border padding to Slide Background Panel</a></li>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=b2bbebb34efc9b931b4bf0feaf1fdede7cad4f62' target="_blank">Set slide/page format dropdown size to 6 in Slide/Page panel</a></li>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=64ff7453408e578b95073db1740bfef4f500a2e4' target="_blank">tdf#89466 Add Master Slide and Close Master View button</a></li>
        </ul>
    </li>
    <br>
    <li>
        <b>Import Bitmap functionality in Area Content Panel</b> - You can read the enhancement report <a href="https://bugs.documentfoundation.org/show_bug.cgi?id=90078" target="_blank"><i>here</i></a>.
        <h4>Commit</h4>
        <ul>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=1bbf0612ea35c73adf0c2aabedf457f7d85acdc0' target="_blank">tdf#90078 Add import bitmap button to Area Panel</a></li>
        </ul>
    </li>
    <br>
    <li>
        <b>Shapes Deck - Default Shapes Panel for Draw</b> - You can read the enhancement report <a href="https://bugs.documentfoundation.org/show_bug.cgi?id=87643" target="_blank"><i>here</i></a>.
        <h4>Commits</h4>
        <ul>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=ab9708e179762f97bd1a0ee4c0d4b439f1dabfd5' target="_blank">tdf#87643: Default Shapes Panel for Shapes Deck</a></li>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=3ee3c29d03cf8c647f798d00b0a947042150449d' target="_blank">tdf#100886: Show Default ShapesPanel when Shape is selected</a></li>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=c878bfc8c90372217bfa41818825f4e047b794d8' target="_blank">Change background of shape thumbnails to dialog color</a></li>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=e8365711e817876ee45b282fc16977b55f4dbca8' target="_blank">Add spacing between shape groups in Default Shapes Panel</a></li>
        </ul>
    </li>
    <br>
    <li>
        <b>Media Playback Panel</b> - You can read the enhancement report <a href="https://bugs.documentfoundation.org/show_bug.cgi?id=87794" target="_blank"><i>here</i></a>.
        <h4>Commit</h4>
        <ul>
            <li><a href='https://gerrit.libreoffice.org/#/c/27363/' target="_blank">tdf#87794: Media Playback Panel</a></li>
        </ul>
    </li>
    <br>
    <li>
        <b>Styles Preview Checkboxfor Styles &amp; Formatting sidebar</b> - You can read the enhancement report <a href="https://bugs.documentfoundation.org/show_bug.cgi?id=93845" target="_blank"><i>here</i></a>.
        <h4>Commit</h4>
        <ul>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=0380a6408030ad9db85b4be81095219d5572749b' target="_blank">tdf#93845: Style Preview Checkbox for Styles &amp; Formatting sidebar</a></li>
        </ul>
    </li>
    <br>
    <li>
        <b>Miscellaneous Commits</b>
         <ul>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=f71a59b5836e03aac42f51ff4d36b73639a6f138' target="_blank">Add padding to sidebarparagraph controls</a></li>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=4244236d1bfc6426b7d81f0a9d13e473c091b345' target="_blank">Padding adjustment to Custom Animations Panel</a></li>
            <li><a href='https://cgit.freedesktop.org/libreoffice/core/commit/?id=af69de6344d94f4fe3f469d425fe8c0117ab33cd' target="_blank">Use PageNumberListBox in cui</a></li>
        </ul>
    </li>
</ol>

##Milestones Unfinished##
<ol>
    <li>
        <b>More Shapes Panel for Shapes Deck</b> - You can read the detailed enhancement report <a href="https://bugs.documentfoundation.org/show_bug.cgi?id=87643" target="_blank"><i>here</i></a>. This is a work in progress, and I was stuck at how to load the categories of shapes into LibreOffice, folder wise, similar to the Gallery. The draft of the work done can be found <a href="https://gerrit.libreoffice.org/#/c/27181/" target="_blank"><i>here</i></a> (please mail/ping if you cannot access the patch).
    </li>
</ol>

##Milestones Missed##
If given more time, I'd have certainly given a shot at finishing the following proposed features:
<ol>
    <li>
        <b>Document-level measurement</b> - Add easy means of changing measurement in the Slide/Page content panel and Page tab - Tools > Options > LibreOffice Writer/Impress/Draw > General > Settings’ Unit of Measurement drop down menu (related - <a href="https://bugs.documentfoundation.org/show_bug.cgi?id=98453" target="_blank"><i>tdf#98453</i></a>). Add pixel measurement to the list (<a href="https://bugs.documentfoundation.org/show_bug.cgi?id=86856" target="_blank"><i>tdf#86856</i></a>).
    </li>
    <br>
    <li>
        <b>Grid & Guidelines for Impress/Draw</b> (<a href="https://bugs.documentfoundation.org/show_bug.cgi?id=98820" target="_blank"><i>tdf#98820</i></a>)
    </li>
    <br>
    <li>
        <b>Alignment and arrangement section for Impress/Draw</b> (<a href="https://bugs.documentfoundation.org/show_bug.cgi?id=93561" target="_blank"><i>tdf#93561</i></a>)
    </li>
    <br>
    <li>
        <b>Find and Replace Modal Dialog to Sidebar</b> (<a href="https://bugs.documentfoundation.org/show_bug.cgi?id=95405" target="_blank"><i>tdf#95405</i></a>)
    </li>
</ol>