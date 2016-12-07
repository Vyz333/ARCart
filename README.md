# WeShop:  You Augmented Reality Shopping Assistant

This project was made as part of the December 2016 Cal AR Hackathon

## Requirements
1. An installation of Android SDK (It comes with Android studio).
2. Android studio. https://developer.android.com/studio/install.html
3. An Android device with a camera.

## Installation

To optimize the time and resources of the lone software dev, the project
was setup upon modified sample files from vuforia-samples-core-android-6-1-17.zip
found in https://developer.vuforia.com/downloads/samples

The meat of changes can be found in the classes inside com/vuforia/samples/VuforiaSamples/app/ObjectRecognition
You can see the full list of changes in differences.diff

## Usage
We provided multiple ways of running/modifying the app:
### A. Run the precompiled APK
You can run the project using the pre-compiled weshop.apk at the root directory.
To do this:
1. in Android 4.0 or higher, go to Settings, scroll down to Security, and select Unknown sources. 
Selecting this option will allow you to install apps outside of the Google Play store.
2a. Then simply visit this site from your android device, download the .apk and run it.
2b. You can alternatively download the .apk to a computer, and use ADB to push it to your Android device
using a USB cable (see https://developer.android.com/studio/command-line/adb.html#move) 

### B. Clone files
1. Run: git clone https://github.com/Vyz333/ARCart/
2. Copy the WeShop folder to the same folder as your Android SDK e.g. "C://Users/<myuser>/AppData/Android"
3. Import the project folder into Android Studio.
4. Build and run.

### C. Unzip the files from Google Drive
1. Download the .7z from https://drive.google.com/file/d/0B9HskMq2rZr_UTNfcW50ZU85alE/view?usp=sharing
2. Find a program that decompresses .7z files
3. Use it to decompress weshop.7z
4. Place the decompressed folder in the same folder as your Android SDK e.g. "C://Users/<myuser>/AppData/Android"
5. Import the project folder into Android Studio.
6. Build and run.
