# YouTube Channel Subtitles

This repository contains [channel](https://youtube.com/@SenpaiSilver) subtitles for my videos. 
The folder for the subs repository follows the simple format of:

    <youtube video id> - <title>/<two letter language code>.ass
    <youtube video id> - <title>/<two letter language code>.srt

Other folders can be created outside of the format for a variety of tools and other resources.  
Feel free to provide your subtitles by opening a [pull request](https://github.com/SenpaiSilver/yt-channel-subtitles/pulls) for corrections or translations.

## Some conversion might be needed

When it comes to making sure the subtitles are styled with the defaults from YouTube it becomes necessary to dumb them down a bit by converting them from `ass` to `srt`:

    ffmpeg -i subs.ass output.srt

Manual editing might be needed to remove some elements, tags and additionnal styling.

## Tools

[Aegisub](https://github.com/Aegisub/Aegisub) is used for editing the YouTube generated subs and fix them.
