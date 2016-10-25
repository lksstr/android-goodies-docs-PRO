---
title: Android Goodies PRO Documentation
tags: [getting_started, troubleshooting]
keywords:
sidebar: ag_sidebar
permalink: ag_index.html
folder: mydoc
---

# Android Goodies PRO Documentation

{{site.time}}
Pages: {{page.url}}
Pages: {{page.hello}}

[Android Goodies](https://www.assetstore.unity3d.com/#!/content/66662) is a collection of Android native methods that allow you to do different things like showing native dialogs, opening a certain location on the map sharing text and many more.

The plugin is in active development and new things will be added. Please [contact us](mailto:leskiv.taras@gmail.com) if you have any questions or requests)

## Supported Features

* App Interaction
  * [AGAlarmClock.cs](https://github.com/TarasOsiris/android-goodies-docs-PRO/wiki/AGAlarmClock.cs) - Methods to show all alarms, set alarm with all properties or set timer
  * [AGApps.cs](https://github.com/TarasOsiris/android-goodies-docs-PRO/wiki/AGApps.cs) - Open other apps, currently only has method to watch YouTube video in native app
  * [AGCalendar.cs](https://github.com/TarasOsiris/android-goodies-docs-PRO/wiki/AGCalendar.cs) - Class that allows to create calendar event with all required params or open calendar app on the provided date
  * [AGDialer.cs](https://github.com/TarasOsiris/android-goodies-docs-PRO/wiki/AGDialer.cs) - Dial or directly call phone number, check if user has phone app
  * [AGMaps.cs](https://github.com/TarasOsiris/android-goodies-docs-PRO/wiki/AGMaps.cs) - Open maps location, address, check if user has maps app
  * [AGSettings.cs](https://github.com/TarasOsiris/android-goodies-docs-PRO/wiki/AGSettings.cs) - Open any system settings screen
  * [AGShare.cs](https://github.com/TarasOsiris/android-goodies-docs-PRO/wiki/AGShare.cs) - Native share text, text+image, tweet, email, send SMS etc, check if user has twitter, sms, email app installed.
  * [AGGallery.cs](https://github.com/TarasOsiris/android-goodies-docs-PRO/wiki/AGGallery.cs) - Pick photo from gallery app, save picture to gallery.
* UI
  * [AGAlertDialog.cs](https://github.com/TarasOsiris/android-goodies-docs-PRO/wiki/AGAlertDialog.cs) - Showing native alert dialogs with buttons/radiobuttons/checkboxes
  * [AGDateTimePicker.cs](https://github.com/TarasOsiris/android-goodies-docs-PRO/wiki/AGDateTimePicker.cs) - Showing date/time picker
  * [AGProgressDialog.cs](https://github.com/TarasOsiris/android-goodies-docs-PRO/wiki/AGProgressDialog.cs) - Show spinner/horizontal progress bar
  * [AGLocalNotifications.cs](https://github.com/TarasOsiris/android-goodies-docs-PRO/wiki/AGLocalNotifications.cs) - Showing local notifications with info provided. Requires **android-support-v4.jar** in Android/Plugins folder.
  * [AGUIMisc.cs](https://github.com/TarasOsiris/android-goodies-docs-PRO/wiki/AGUIMisc.cs) - Showing toasts and immersive mode methods.
* Retrieving Info
   * [AGDeviceInfo.cs](https://github.com/TarasOsiris/android-goodies-docs-PRO/wiki/AGDeviceInfo.cs) - Various methods to get various info about device and apps (`android.os.Build`, `android.os.Build.Version`) and other
   * [AGEnvironment.cs](https://github.com/TarasOsiris/android-goodies-docs-PRO/wiki/AGEnvironment.cs) - Access to some `android.os.Environment` properties and methods
   * [AGNetwork.cs](https://github.com/TarasOsiris/android-goodies-docs-PRO/wiki/AGNetwork.cs) - Internet connectivity and wifi related methods
   * [AGTelephony.cs](https://github.com/TarasOsiris/android-goodies-docs-PRO/wiki/AGTelephony.cs) - Telephony related methods
* Hardware
  * [AGBattery.cs](https://github.com/TarasOsiris/android-goodies-docs-PRO/wiki/AGBattery.cs) - Get device battery charge level
  * [AGFlashLight.cs](https://github.com/TarasOsiris/android-goodies-docs-PRO/wiki/AGFlashLight.cs) - Enable and disable camera flashlight (as torch), check if device has flashlight
  * [AGGPS.cs](https://github.com/TarasOsiris/android-goodies-docs-PRO/wiki/AGGPS.cs) - Listen to GPS location changes, check if GPS enabled, get last known location.
  * [AGVibrator.cs](https://github.com/TarasOsiris/android-goodies-docs-PRO/wiki/AGVibrator.cs) - Check if device has vibrator, vibrate or vibrate pattern
* Storage
  * [AGFileUtils.cs](https://github.com/TarasOsiris/android-goodies-docs-PRO/wiki/AGFileUtils.cs) - Method to save Unity Texture2D to Android gallery

## Advantages

* Clean and flexible API
* No overriding of Unity default activity
* Full source code included
* Well-written docs

## Running the demo scene

To build and run the demo scene just connect your Android device switch target platform to Android in Unity build settings and run the example scene on device or emulator. No extra setup is required.

You will see the menu like this on device where you can start testing:

<img src="https://raw.githubusercontent.com/TarasOsiris/android-goodies-docs-PRO/master/images/demo-home.png">


{% include links.html %}
