FFmpeg MOV edit list patch
--------------------------

Based on a patch posted to the [FFmpeg devel mailing list and newsgroup] (https://gist.github.com/ericdagenais/9955424)

2013-09-19 Eric Dagenais
* handles common QuickTime Player edits but not all possible edit list combos.
  see http://ffmpeg.org/pipermail/ffmpeg-devel/2009-February/065703.html
* fixes time offset and av-desync issues
* does not preserve mov rotation matrix from input video when encoding to
  output file

2009-02-18
* edit list patch ported from Xine posted to FFmpeg newsgroup by Krishna
  Gadepalli
  http://article.gmane.org/gmane.comp.video.ffmpeg.devel/84145/match=


FFmpeg README
-------------

1) Documentation
----------------

* Read the documentation in the doc/ directory in git.
  You can also view it online at http://ffmpeg.org/documentation.html

2) Licensing
------------

* See the LICENSE file.

3) Build and Install
--------------------

* See the INSTALL file.
