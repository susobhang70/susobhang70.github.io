---
layout: post
title: "Media Playback Panel"
description: Description of the features provided by the Media Playback Panel
headline: LibreOffice 5.3
category: Sidebar-documentation
tags: [Sidebar, LibreOffice, media, panel, playback]
imagefeature: MediaPlayback/cover.png
comments: true
share: true
published: true
---
If you've ever complained about the media playback toolbar taking up your precious screen space at the bottom, this one's for you! The upcoming LibreOffice 5.3 will host the new Media Playback Panel in the Properties Deck.

The controls mainly draw inspiration from the ones in the Media toolbar at the bottom, and I'll be describing the same in this post. This is a contextual panel, only showing up when a media item is selected.

The entire enhancement report can be found <a href="https://bugs.documentfoundation.org/show_bug.cgi?id=87794" target="_blank">*here*</a>. I myself have been working on this, with the help of my mentors - bubli (**Katarina Behrens**), and jay (**Yousuf Philips**).

#Features#
<ul>
    <center><a href="{{ site.url }}/images/MediaPlayback/panel.png"><img src="{{ site.url }}/images/MediaPlayback/panel.png"></a></center>
    <li>
        The Playback Toolbox housing 4 buttons to control media state:
        <ul>
            <li>Play: Play Media</li>
            <li>Pause: Pause Media</li>
            <li>Stop: Stop the playing Media (default selected when Media is not playing)</li>
            <li>Loop: Sets the media playback on repeat</li>
        </ul>
    </li>
    <li>Seek slider: Slider to seek Media item at a particular time.</li>
    <li>Time Status Box: Displays the elapsed and total time of currently playing and selected Media item.</li>
    <li>Volume Slider: Slider to increase or decrease volume of Media item according to need.</li>
    <li>Mute button: One click button or unmute selected Media item.</li>
</ul>