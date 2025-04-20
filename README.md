# Stardew Valley Wear OS Watchface
## Description
Stardew Valley themed watch face for Wear OS smartwatches made in Google's WFF via Samsungs Watch Face Studio.

## Features
![Stardew Valley DEMO GIF](https://github.com/user-attachments/assets/c67a0536-6ab4-4376-859a-cc5625465f78)

The watchface displays the following information:
- **Time**: Separate Versions for 12/24 hour format available for download.
- **Date**: The date/time area acts as a shortcut to open the calendar application on the watch.
- **Battery**: The energy bar shows the battery status of the smartwatch. The colour of the bar changes as you lose energy/battery. The exhaustion icon is displayed when the battery is below 15%. The battery area acts as a shortcut to open the battery settings on the watch (_only on the samsung versions_).
- **Day Progress**: The arrow moves according to the time of the day.
- **Steps**: The current number of steps (S) is displayed instead of a gold counter. The steps area acts as a shortcut to open the samsung health app on the watch (_only on the samsung versions_).
- **Temperature**: In addition to the step counter, there is a second counter showing the current temperature (T) (_only on the V34 Versions_). The temperature area acts as a shortcut to open the samsung weather app on the watch (_only on the samsung version_).
- **Notifications Counter**: If you have a unread notification, the journal icon is displayed.
- **Seasons icon**: The season icon doesn't change according to the current season. You can change the icon manually by customizing the watchface.
- **Temperature icon**: The temperature icon changes based on the actual weather (_only on the V34 version; on the V30 version, the festival icon is always displayed_)
- **Background**: Different backgrounds for day and night (based on sunset and sunrise times). (_only on the V34 version_)

## Versions
Every version has a separate 12/24 hour format version.
### V34 Samsung Version
- Designed only for Samsung Smartwatches with an SDK/API Level of 34+
- Additional Features:
  - Weather Features: Temperature and Weather icons
  - App shortcuts: Shortcuts to the samsung health and weather app.
### V34 Version
- Designed for all WearOS Smartwatches with an SDK/API Level of 34+
- Additional Features:
  - Weather Features: Temperature and Weather icons
### V30 Version
- Designed for all WearOS Smartwatches with an SDK/API Level of 30+

## Installation Guide
### What you need
- **Watch Face Studio**: Download and install Samsung Watch Face Studio on your PC (https://developer.samsung.com/watch-face-studio/download.html).
- **Watchface**: Download the correct version of the Watchface.

### How to pair your watch and send the watchface to your watch
- See more detailed Guide here: https://www.reddit.com/r/GalaxyWatch/comments/15jo3u4/tutorial_how_to_pair_your_galaxy_watch_with_watch/
- Enable Developer settings on your watch (Settings/About Watch/Software/ tap 7+ times Softwareversion)
- Enable WiFi and connect to the same WiFi as your PC (keep in mind, if you're connected to your phone it doesn't (always) stay connected to the WiFi)
- Go into Developer Developer and turn on "ADB debugging"
- Scroll further down, go to "Wireless Debugging" and turn it on. Even if your WiFi is turned on and connected, you may get errors. Simply tap/enable again until it's activated
- In Wireless Debugging, when it's finally activated you'll see the IP address and IP port of your watch. There you tap on "Pair device". It'll show you a new windows with your Wifi "Pairing Code" and below it shows you an IP address and IP port. The IP address is the same as your from your watch, but the IP Port is your "Pairing Port".
- On your PC in WFS press "Run on Device"
- Press the Plus button (+) at the top right to add a device (your watch)
- You have to enter 4 values: IP, IP port, Pairing code and Pairing port.
- The window "Connected Devices" should now show your watch. If not, you need to press "Scan devices" and it should be listed there!
- Select your device, let it transfer and it should be on your watch now! Enjoy!
