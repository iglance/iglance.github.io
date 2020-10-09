---
permalink: /release-notes/
title: "Release Notes"
excerpt: "iGlance is a free and open source macOS System Monitor"
---

### ▶️ v2.1 - 06.10.2020
##### New Features:
- Big Sur re-design

##### Bug Fixes:
- Fixed a bug that would cause the network speed to not have enough space when speed is above 10.00 MB/s
- Fixed a bug that would not show the app icon in the dock when minimizing the window
- Fixed a bug that would reset the app settings when new user settings are introduced
- Fixed a bug that would draw the menu bar icons in the wrong theme when having 'Auto-Appearance' activated

---
### ▶️ v2.0.9 - 29.06.2020
##### New features:
- Memory information matches now the information in the Activity Monitor app

##### Bug fixes:
- Fixed a bug that would cause the app to not start after login
- Fixed a bug that would cause the app to immediately crash after starting it
- Fixed a bug that would dismiss the battery notifications to fast
- Fixed a memory leak
- Fixed a bug that would cause option "Show disk space usage" to be always ticked when reloading the view (thank you @gary-lgy)

---
### ▶️ v2.0.8 - 26.04.2020
##### New features:

- It is now possible to export, import and reset the settings of the app under the app menu File (@Moneypulation)
- It is now possible to display the used and free disk space in the menu bar (@khorolets)

##### Bug fixes:

- Fixed a bug that would cause the app to display wrong system information on the dashboard
- Fix a bug that would cause the app to randomly crash
- Fixed a bug that would prevent the app from showing a popup for a new update

---
### ▶️ v2.0.7 - 21.04.2020
- This version provides a hot-fix for random crashes
- Fixed a bug that would not set the update interval correctly when changed

---
### ▶️ v2.0.6 - 20.04.2020
This updated includes critical bug fixes:

- Fixed a bug that would cause the cpu usage graph to spike to 100% while the actual usage is 0%
- Fixed a bug that would not correctly display the "Show network usage" checkbox
- Fixed a bug that would cause the network menu bar to display a bandwidth of zero while connected to a VPN
- Fixed a bug that would cause iGlance to freeze after the machine was sleeping

---
### ▶️ v2.0.5 - 16.04.2020
This update includes mostly bug-fixes
##### New features:

- It is now possible to export the most recent log file using Diagnostics > Save Logfile... in the app menu
- It is now possible to open the preferences of the app using iGlance > Preferences in the app menu or by pressing CMD + , while the iGlance window is active

##### Bug fixes:

- Fixed a bug that would show the wrong available memory in the menu of the memory menu bar item
- Fixed a bug that would cause the app to freeze after waking the machine from sleep
- Fixed a bug that would cause the cpu bar graph to be fully drawn while the machine is not under load

---
### ▶️ v2.0.4 - 01.04.2020
- added release notes
- fixed temperature indicator bug
- fixed app diagnostics menu
- system font is now used to render menu bar items

---
### ▶️ v2.0.3 - 29.03.2020
- The setting Advanced Logging is now saved when quitting the app.
- The app doesn't crash anymore when changing the network interface (e.g. when connecting to a VPN)

---
### ▶️ v2.0.2 - 29.03.2020
- Hotfix🔥: Fixed a bug that would cause the app to crash immediately after launch

---
### ▶️ v2.0.1 - 29.03.2020
- Hotfix🔥: App is now starting on machines that have no NVMe drive

---
### ▶️ v2.0 - 28.03.2020
This update is very exciting with many quality-of-life improvements and an all new design🎉

- New GUI
- App is now automatically updated using Sparkle
- AppMover asks to move the app into the Applications folder on startup
- The percentage of the battery can now be displayed in the menu bar
- When displaying the remaining chargin/discharging time, the current status of the battery while charging is displayed (Not Charging, Charging, Charged)
- The total transmitted data is now displayed in the network menu
- The app is now published under the GNU GPLv3 license

---
### ▶️ v1.4.3 - 20.01.2020
- Fixed a bug which crashed iGlance while the computer was sleeping (#67)
- Fixed a UI-bug where a label had the wrong description (#65)
- Percentage in the battery menu bar menu has no longer a leading zero when lower than 10% (#56)
- The app is now codesigned and notarized. This no longer requires special authorization to launch the app 🎉🎉
- 🔥Hotfix🔥: App is not crashing anymore on fan-less machines

---
### ▶️ v1.4.2 - 27.12.2019
##### New features:

- "Check for updates on wake up" can now be disabled
- The order of the upload and download network speed can now be changed
- Upper and lower battery notifications can now be disabled
- Currently used network interface is now automatically detected

##### Bug fixes:

- Fixed a bug where slow name resolution in the network caused the app to be not response

---
### ▶️ v1.4.1 - 22.10.2019
- Moved to Swift 5
- Network speed now displays the correct values when using 2 or 3 second update interval

---
### ▶️ v1.3.6 - 01.09.2019
- changed the cpu temperature sensor from cpu die sensor to cpu proximity sensor
- changed the method how network speed is read. This should (hopefully) fix the random crashing of the app

---
### ▶️ v1.3.5 - 23.07.2019
- Upload and download speed labels in the menu bar are now switched to more intuitive (upload is upper label, download is lower label)

---
### ▶️ v1.3.4 - 23.07.2019
- increased version to 1.3.4

---
### ▶️ v1.3.3 - 18.07.2019
- corrected path to create-dmg repo

---
### ▶️ v1.3.2 - 28.02.2019
- 🔥 Hotfix: Ticking the "Autostart on Boot" checkbox no longer throws an error.🔥