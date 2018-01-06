# _{Webcam_fun}_

#### _{3 different ways of manipulating webcams.}, {1/5/2018}_

#### By _**{Chris Underwood}**_

## Description

_{3 different ways of manipulating webcams but you can only do 1 of the three at any time. The default set up is #3 the green screen.
  1) Redscreen which currently defaults to red but could be set to any color. This feature gives the entire screen an over saturation.
  2) RGBsplit takes the red blue and green pixles and pulls them apart a certain number of pixles so you can multiple individual colored shadows on the screen. Global alpha can be used to create a delayed shadow.
  3) The last is green screen like in the movies. Basically you can use the slide bars on the screen to "eliminate" color in the webcam feed.
  4) commenting out all of the three options just gives you a bigger unaltered camera feed on your desktop.

  There is also an option to take a phone of the altered feed and to download the photo by clicking on a photo.}_

## Setup/Installation Requirements


* download the files to a folder of your choice
* migrate to that folder via the console
* type npm install & hit enter
* type npm start & hit enter
* Open a window in the browser of your choice to localhost:3000

_{To use the other options go into scripts.js, paintToCanvas function, comment out the line that begins with pixels = greenScreen, and uncomment either pixels = redEffect or pixels = rgbSplit. With rbgSplit you can also uncomment the globalAlpha line.}_

## Known Bugs

_{The slider controls only works for the green screen option. }_

## Support and contact details

_{cunderwoodmn [at] gmail {dot} com}_

## Technologies Used

_{vanila_js, webcam, navigator.mediaDevices.getUserMedia}_

### License

Copyright (c) <2018> <Chris Underwood>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Copyright (c) 2018 **_{Chris Underwood}_**
