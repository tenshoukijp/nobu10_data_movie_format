# 蒼天録 - MOVIE - フォーマット

蒼天録のムービーは MPEG ファイル。
フォーマットとしては、以下

- Stream #0:0[0x1e0]: Video: mpeg1video, yuv420p(tv), 320x240 [SAR 1:1 DAR 4:3], 2000 kb/s, 30 fps, 60 tbr, 90k tbn
- Stream #0:1[0x1c0]: Audio: mp2, 44100 Hz, stereo, s16p, 224 kb/s

縦横サイズやビットレート等は増やしたものを用意しても問題なく再生される。  
ただし、あまりなめらかにスケーリングが調整されないようだ。
