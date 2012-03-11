dpgconv
=======

A python script to transcode video files to DPG format suitable for Nintendo DS (tm)

Copyright 2007-2011 Anton Romanov <theli (a@t) theli.is-a-geek.org>

The software is released under the terms of 
[GPL v.2](http://www.gnu.org/licenses/gpl-2.0.html)

Original homepage: http://theli.is-a-geek.org/blog/static/dpgconv

This fork makes a small change to the code checking for mplayer and mencoder,
so that it works, even if mplayer emits "Symbol `ff_codec_bmp_tags' has different size in shared object, consider re-linking".
