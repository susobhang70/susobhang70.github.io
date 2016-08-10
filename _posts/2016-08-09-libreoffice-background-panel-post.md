---
layout: post
title: "Properties Panels for Impress/Draw"
description: Description of features provided by the Slide/Page Properties Panels in LibreOffice 5.2+
headline: LibreOffice 5.2
category: Sidebar-documentation
tags: [Sidebar, LibreOffice, slide, page, background]
imagefeature: slidebgpanel.png
comments: true
share: true
published: true
---
LibreOffice 5.2 is out, and one of the key improvements to Impress and Draw has been the introduction of the Properties Panels to the sidebar - namely Slide Content Panel for Impress, and Page Content Panel for Draw.

These panels enable quick access to the slide/page size and background properties. Both these panels have the same underlying code and features, and only differ in labels depending on the Application Context. So this post aims at explaining all these features in the panel available to both Impress and Draw.

The entire enhancement report can be found <a href="https://bugs.documentfoundation.org/show_bug.cgi?id=89466">*here*</a>. The main credits for developing the panel go to bubli (**Katarina Behrens**), **Rishabh Kumar**, and jay (**Yousuf Jay Philips**). I have been making enhancements to the same after the panel got published.

<h2>Features</h2>
<ul>
    <li>
        Format dropdown to easily change Slide/Page format.
        <center><a href="{{ site.url }}/images/slidebg_format.png"><img src="{{ site.url }}/images/slidebg_format.png"></a></center>
    </li>
    <li>
        Quick option to change Orientation of the Slide/Page
        <center><a href="{{ site.url }}/images/slidebg_orientation.png"><img src="{{ site.url }}/images/slidebg_orientation.png"></a></center>
    </li>
    <li>
        Dropdown to change background of the slide/page. Currently 5 settings - None (no background), Color (Solid Fill), Gradient, Hatching, and Bitmap
        <center><a href="{{ site.url }}/images/slidebg_background.png"><img src="{{ site.url }}/images/slidebg_background.png"></a></center>
    <ul>
        <li>
            Color Setting
                <center>
                    <a href="{{ site.url }}/images/slidebg_color.png"><img src="{{ site.url }}/images/slidebg_color.png"></a>
                </center>    
        </li>
        <li>
            Gradient Setting - Make a gradient with two colors, which gives added customization compared to presets
                <center>
                    <a href="{{ site.url }}/images/slidebg_gradient.png"><img src="{{ site.url }}/images/slidebg_gradient.png"></a>
                </center>

        </li>
        <li>
            Hatching Setting
                <center>
                    <a href="{{ site.url }}/images/slidebg_hatching.png"><img src="{{ site.url }}/images/slidebg_hatching.png"></a>
                </center>

        </li>
        <li>
            Bitmap Setting
                <center>
                    <a href="{{ site.url }}/images/slidebg_bitmap.png"><img src="{{ site.url }}/images/slidebg_bitmap.png"></a>
                </center>

        </li>
    </ul>
    </li>
    <li>
        Insert Image as Bitmap - With option (pop-up) to set the image as background for all pages/slides
        <figure class="third">
            <a href="{{ site.url }}/images/slidebg_select_image.png"><img src="{{ site.url }}/images/slidebg_select_image.png"></a>
            <a href="{{ site.url }}/images/slidebg_setall.png"><img src="{{ site.url }}/images/slidebg_setall.png"></a>
            <a href="{{ site.url }}/images/slidebg_imagebg.png"><img src="{{ site.url }}/images/slidebg_imagebg.png"></a>
        </figure>
    </li>
    <li>
        Checkbox to toggle display background.
    </li>
    <li>
        Checkbox to toggle display objects.
    </li>
</ul>

A few other enhancements like a `Edit Master Slide` button to go to Master view of Page/Slide, `Close Master Slide` to close Master Slide, and context label changes are expected to be added in LibreOffice 5.3.