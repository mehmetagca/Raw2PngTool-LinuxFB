# Raw2PngTool-LinuxFB
Screenshot tool for Linux frame buffer that it converts from 16bit raw image(ARGB1555) to png(RGB888)

## Usage:
```
./iraw2png <width> <height> < <imgsrc.raw> > <imgdst.png>
```
  
##### Firstly, Take raw image from linux frame buffer
  ```
  cat /dev/fb0 > img.raw
  ```
  
  
##### Then, Give it to the script
  ```
  ./iraw2png_argb1555_to_rgb888 800 600 < img.raw > img.png
  ```
  
  
#### That is ok!
  
  
> *Source:* *https://www.cnx-software.com/2010/07/18/how-to-do-a-framebuffer-screenshot/*
