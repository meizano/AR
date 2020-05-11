# Convert 360 Spherical to Equirectangular
## Tools
1. Download [Hugin](http://hugin.sourceforge.net/download/)
2. Optional Download [FFMPEG](https://ffmpeg.org/download.html) for video stitching
3. Optional Download [MultiBlend](http://horman.net/multiblend/) for video stitching

## Steps
1. Install Hugin
2. Install FFMPEG
3. Extract MultiBlend to hugin\bin
4. Clone or download zip of [gear360pano](https://github.com/ultramango/gear360pano) then unpack it somewhere
5. Open Command Prompt (Windows Start, type CMD)
6. Change Current Directory to gear360pano directory (e.g. cd gear360pano)
7. Put all 360 image inside a directory inside 360pic
8. Type in Command Prompt for example: ```.\gear360pano.cmd .\krakatoa\*.jpg``` and press ENTER
9. you can see the output files inside html\data

## Reference:
* [Gear360Pano](https://github.com/ultramango/gear360pano)