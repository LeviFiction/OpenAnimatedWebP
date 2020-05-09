# OpenAnimatedWebP
A PSP script that will hopefully, eventually, allow us to open animated webp images as a layered image

## Installation
To install this script, add it to the Scripts-Trusted folder of Corel's PaintShop Pro
Not ready to be used at all, still working out the basic format and logic

## Resources:
* https://developers.google.com/speed/webp/docs/riff_container
* https://wiki.python.org/moin/BitwiseOperators
* https://docs.python.org/2/library/struct.html
* https://mathiasbynens.be/demo/animated-webp

## Dependencies
### Libraries
* os
* struct

### Software
* Webp commandline tools - webpmux - webpinfo - dump_anim
https://developers.google.com/speed/webp/docs/precompiled

# To Do:
* ~Finish read code for basic file structure~
* ~Add code to simulate Open Image command (real open image crashes with animation file)~
* ~Check file for all appropriate fields~
* ~Create blank image the size of the canvas~
* ~Use dump_anim to create individual PNG images~
* Import each frame on its own layer at the appropriate offset, with encoding data as layer name
* Save as PSPImage
* Work on Animated WebP image exporter
