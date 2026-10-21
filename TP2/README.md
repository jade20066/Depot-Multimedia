# Animation

[Sans titre.gif.log](https://github.com/user-attachments/files/33780509/Sans.titre.gif.log)

C:/Users/2489560/OneDrive - Collège Montmorency/Multimédia/krita-x64-5.3.3 (1)/krita-x64-5.3.3/bin/ffmpeg.exe -hide_banner -y -y -r 9 -start_number 0 -start_number_range 1 -i C:/Users/2489560/Pictures/image%04d.png -i C:/Users/2489560/Pictures/KritaTempPalettegen_%06d.png -lavfi [0:v][1:v]paletteuse=dither=sierra2_4a:diff_mode=none -f gif -loop 0 -gifflags +transdiff C:/Users/2489560/Pictures/Sans titre.gif
=====================================================
Input #0, image2, from 'C:/Users/2489560/Pictures/image%04d.png':
  Duration: 00:00:01.84, start: 0.000000, bitrate: N/A
  Stream #0:0: Video: png, rgba(pc, gbr/unknown/unknown), 500x700 [SAR 11811:11811 DAR 5:7], 25 fps, 25 tbr, 25 tbn
Input #1, image2, from 'C:/Users/2489560/Pictures/KritaTempPalettegen_%06d.png':
  Duration: 00:00:00.04, start: 0.000000, bitrate: N/A
  Stream #1:0: Video: png, rgba(pc, gbr/unknown/unknown), 16x16 [SAR 1:1 DAR 1:1], 25 fps, 25 tbr, 25 tbn
Stream mapping:
  Stream #0:0 (png) -> paletteuse
  Stream #1:0 (png) -> paletteuse
  paletteuse:default -> Stream #0:0 (gif)
Press [q] to stop, [?] for help
Output #0, gif, to 'C:/Users/2489560/Pictures/Sans titre.gif':
  Metadata:
    encoder         : Lavf62.3.100
  Stream #0:0: Video: gif, pal8(pc, gbr/unknown/unknown, progressive), 500x700 [SAR 1:1 DAR 5:7], q=2-31, 200 kb/s, 9 fps, 100 tbn
    Metadata:
      encoder         : Lavc62.11.100 gif
frame=    7 fps=0.0 q=-0.0 size=     768KiB time=00:00:00.77 bitrate=8089.0kbits/s speed=1.52x elapsed=0:00:00.51    
frame=   16 fps= 16 q=-0.0 size=    2304KiB time=00:00:01.77 bitrate=10616.8kbits/s speed=1.73x elapsed=0:00:01.02    
frame=   27 fps= 18 q=-0.0 size=    3840KiB time=00:00:03.00 bitrate=10485.8kbits/s speed=1.96x elapsed=0:00:01.52    
frame=   39 fps= 19 q=-0.0 size=    5632KiB time=00:00:04.33 bitrate=10647.1kbits/s speed=2.14x elapsed=0:00:02.02    
[out#0/gif @ 000001ff0089e540] video:7107KiB audio:0KiB subtitle:0KiB other streams:0KiB global headers:0KiB muxing overhead: 0.000275%
frame=   46 fps= 20 q=-0.0 Lsize=    7107KiB time=00:00:05.11 bitrate=11390.4kbits/s speed=2.23x elapsed=0:00:02.29    

