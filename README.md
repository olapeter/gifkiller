gifkiller
=========

Opera / Chrome extension to suppress animated GIFs.

One of the features I miss the most from Presto Opera
is the F12 -> "Enable Animated Images" option.

Until someone working on Blink finds the time to fix
https://code.google.com/p/chromium/issues/detail?id=3690
there is a need to kill the animated GIFs.

Howto:

Turn on "Developer mode" in opera://extensions and
open the cloned repo from the "Load unpacked extension"
option.

Load http://twistedsifter.com/2012/04/50-animated-gifs-for-every-situation-ever/
to see blocked GIFs. Double-click to play.

TODO:
- add support for more animation types (APNG etc.)
- performance improvements
- have it run on all sites (currently only on http: )
