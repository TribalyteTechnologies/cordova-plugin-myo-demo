# cordova-plugin-myo-demo
Sample application to demonstrate the usage of the <a href="https://github.com/TribalyteTechnologies/cordova-plugin-myo">cordova-plugin-myo project</a>.

<!---
## Sample app for Android
<a href="https://play.google.com/store/apps/details?id=com.tribalyte.app.myoplugindemo">
  <img alt="Android app on Google Play"
       src="https://developer.android.com/images/brand/en_app_rgb_wo_60.png" />
</a>
-->

## Installation
0. (Prerequisite) If you haven't already, download and install the [Android SDK Build Tools](https://developer.android.com/tools/revisions/build-tools.html) and the [Cordova CLI](http://cordova.apache.org/docs/en/edge/guide_cli_index.md.html#The%20Command-Line%20Interface_installing_the_cordova_cli)
1. Clone this repository in your computer:<br>
```git clone https://github.com/TribalyteTechnologies/cordova-plugin-myo-demo.git```
2. Go to the project root folder:<br>
```cd cordova-plugin-myo-demo```
3. Add the cordova-plugin-myo:<br>
```cordova plugin add https://github.com/TribalyteTechnologies/cordova-plugin-myo.git```
4. Add the Android platform:<br>
```cordova platform add android```
5. Connect a compatible Android device and launch the application:<br>
```cordova run android```
6. Make sure the Bluetooth interface of the mobile device is on.
7. Make sure the Myo device is on (put it on or shake it until the light starts blinking).

## Features
* Connect the Myo device using the attach buttons or the scan dialog available in the GUI
* Check the information of the connected Myo
* Make the Myo vibrate
<br><br>
![Application screenshot](screenshot.png?raw=true "Application screenshot")

# License
The MIT License (http://www.opensource.org/licenses/mit-license.html)

Copyright (c) 2014 Tribalyte Technologies S.L. (http://www.tribalyte.com/)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
