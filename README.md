JW Player Macro
===============

Play media files using [JW Player](http://www.longtailvideo.com/support/jw-player/28832/about-jw-player), an open-source embeddable media player for web sites, supporting many commonly-used audio and video formats. The player is easy to configure, customize and extend.

You can play video files attached to the current wiki page or to any of your wiki pages:

    {{jwplayer attachment="video.mp4" /}}
    {{jwplayer attachment="Space.Page@video.mp4" width="600" height="400" /}}

You can also play external videos such as those found on YouTube:

    {{jwplayer attachment="http://www.youtube.com/watch?v=1o9efYEmXKA" /}}

Finally, you can play video files from your server:

    {{jwplayer attachment="/path/to/video.mp4" /}}
    {{jwplayer attachment="$xwiki.getSkinFile('videos/sample.mp4')" /}}

Checkout the [documentation page](http://extensions.xwiki.org/xwiki/bin/view/Extension/JWPlayer+Macro) on extensions.xwiki.org for more information.
