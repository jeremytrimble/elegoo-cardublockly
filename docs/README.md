# Overview
I uploaded this `elegoo-cardublockly` after trying to convert some of the Arduino examples for the Elegoo car kit into Blockly.  It's a format that my nephew is familiar with and might help introduce other coding concepts.

# Setup
In order to get these examples working in a familiar, [Blockly](https://code.google.com/blockly) format, install two applications.  One is the official Arduino application and another is an open-source, stand-alone application.  The latter is used to drag/drop the blockly elements, which depends on elements defined in the former.

## Arduino IDE
Download and install the latest Arduino IDE.
You'll find links to download for your operating system [here]](https://www.arduino.cc/en/Main/Software)

> If you are using **Windows**, be careful not to download the **Windows _App_**.  You'll probably want to use the first link in the downloads section.

## ArduBlockly
Once you have the Arduino IDE installed, you'll need ArduBlockly, from [_Embedded Log_](https://ardublockly.embeddedlog.com/)

The previous page has a link to download the latest release.  Their releases are _actually_ hosted on GitHub - [Direct Link](https://github.com/carlosperate/ardublockly/releases)
> ...just wanted to add that disclaimer in case someone isn't familiar :wink:

## Elegoo Documentation
This repository contains a slimmed-down, English-only version of the official Elegoo documenationa and code samples.  For a complete set of documenation, go to the [Elegoo Downloads](https://www.elegoo.com/download/) page and search for _"Elegoo Smart Robot Car Kit V3.0"_.

# Usage
To make full use of these examples, you'll need to download them to your desktop.  You can clone the repository but might be easier to download a zip file.  If you want to download a zip file, go to the GitHub page and click the **`Download Zip`** button.

> This repository only contains a few clones of the Elegoo examples.  The point was not to re-create the entire library, but to provide some examples for getting started.

## Step-By-Step
1. Open the ArduBlockly IDE
2. Click the **`Open`** button, in the top, right corner
 - _Alternatively, you can go to the `File > Open...` menu option._
3. Locate the XML document for the lesson.  For example, if you are on `Lesson 1 Make The Car Move` and want to find the `auto_go` example, look in the files you unzipped earlier.  Check the `Lesson 1` > `auto_go` folder for `auto_go.xml`.

> **For example**
> ```
> // on Mac or Linux
>  ~/Documents/Arduino/elegoo-cardublockly/Lesson 1/auto_go/auto_go.xml
>  
> // on Windows
 My Documents\Arduino\elegoo-cardublockly\Lesson 1\auto_go\auto_go.xml
> 
> ```

4.  Once you open the file, you should see an equivalent program represented by Blockly elements.

You should also see similar Arduino code appear in the `Arduino Code` panel as well.


That's about it - **GOOD LUCK!**
# Additional Links
I created a YouTube playlist with set of thorough instructional videos, from the [Smart Robots Review](https://www.youtube.com/channel/UCg-ImO83_pfK5EbagezLoAw) channel.  The playlist is [Elegoo Smart Car](https://www.youtube.com/playlist?list=PL8fVedNXdacElj4Taa3VsgnBl6v9Otvq2)
 - [Smart Robots Review](https://www.youtube.com/channel/UCg-ImO83_pfK5EbagezLoAw) (YouTube Channel)
 - [Elegoo Smart Car](https://www.youtube.com/playlist?list=PL8fVedNXdacElj4Taa3VsgnBl6v9Otvq2) (Playlist)
 