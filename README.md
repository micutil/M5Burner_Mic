# M5Burner_Mic
[日本語README](READMEjp.md)
### Download [here (2020/3/22)](http://micutil.com/download/M5Burner_Mic.zip), both Mac and Win versions are included.<br>
![M5Burner_Mic Icon](images/m5burnermic128.png)

M5Burner by Micono<br>
(Mac and Windows version)

M5Stack is an application that can basically do the same as M5Burner ([https://m5stack.com/download](https://m5stack.com/download)) that transfers the official firms or program to M5Stack. You can load and transfer firms and programs in the firmwares folder at the same level as the M5Burner_Mic application.

## Update

v1.3.3 (2020/3/22)

- Since the firmwares folder cannot be selected automatically on the Mac version, it now displays a selection dialog at startup.


v1.3.2 (2020/3/22)

- Added some farms (RoVoCoMo2 v2.2, UIFlow v1.4.4...)

v1.3.2 (2019/9/26)

- Added "4M Default" and "Fire Default" Partition Schemes on some farmwares.
- Removed some firmwares.

v1.3.1

- Bundled RoVoCoMo2 and RSTester
- Fixed the prisets of Odroid-GO firmwares

v1.3.0

- Bundled several firmwares. (Odroid-GO firmware, UIFlow 1.3.2...)

v1.2.0

- Modified preset menu to be divided into each json file.
- You can use any json file or the folder containing json files by dropping it on the window or the icon of M5Burner_Mic.
- When you drop a **bin file** into the window or the icon of M5Burner_Mic then, the configuration file for installation **be built into the firmwares folder** and added to the preset menu, so you click the start button You can just install it.

v1.1.0

- Added simple serial monitor function.
- Bundled some M5Stack related official firmwares.
- Bundled SetWiFi_Mic

## Bundled firmwares and programs

(2020/3/22)

- UIFlow v1.4.4, v1.4.5, v1.4.5.1 (M5Stack, M5Stick, M5StickC)
- RoVoCoMo2 (M5Stack, M5Stack fire, Odroid-GO)

(2019/9/13)

- UIFlow v1.2.3, v1.3.1beta, v1.3.2, v1.3.5beta, v1.4.0beta (M5Stack, M5Stick, M5StickC)
- Faces-Kit-v1.0.0
- M5Camera v1.0.0, QRScan-v1.0.0, Esp32Cam-Nopsram v1.0.1
- Odroid-GO firmware [v180728](https://wiki.odroid.com/odroid_go/firmware_update_oldfw), [v181001](https://wiki.odroid.com/odroid_go/firmware_update)
- [RoVoCoMo2](https://github.com/micutil/M5Stack_RoVoCoMo2), [RSTester](https://github.com/micutil/M5Stack_RSTester)

(2019/5/17)

- M5Stack related official firmwares (M5Bala, M5Cam, M5Cloud, M5Fire, M5Flow, M5GO, M5Unit, FACES_Kit)
- SD-Menu (M5Stack) ([tobozo/M5Stack-SD-Updater](https://github.com/tobozo/M5Stack-SD-Updater))
- SD-Menu (**Odroid-GO**):2019/5/17 ([tobozo/M5Stack-SD-Updater](https://github.com/tobozo/M5Stack-SD-Updater))
- SetWiFi_Mic (M5Stack):2019/5/17 ([micutil/SetWiFi_Mic](https://github.com/micutil/M5Burner_Mic))
- SetWiFi_Mic (**Odroid-GO**):2019/5/17 ([micutil/SetWiFi_Mic](https://github.com/micutil/M5Burner_Mic))
- Others: my sample program.


## Feature

- The Windows version of M5Burner has firmware in the external firmwares folder, but the Mac version is in the package, so it is troublesome to make it compatible with M5Burner with a self-made application, but M5Burner_Mic is firmwares Because you use firmware in the folder, you do not need to prepare two firmwares for Mac and Win.
- In the Mac version of M5Burner, you can not select a port, but M5Burner_Mic can be selected.
- M5Burner_Mic reads files with extension .json in the firmwares folder, so you can prepare json files individually.
- You can use any json file or the folder containing json files by dropping it on the window or the icon of M5Burner_Mic.
- When you drop a **bin file** into the window or the icon of M5Burner_Mic then, the configuration file for installation **be built into the firmwares folder** and added to the preset menu, so you click the start button You can just install it.
- If you want to install LovyanLauncher, download and unzip [LovyanLauncher-firmware] (https://github.com/lovyan03/LovyanLauncher-firmware) and place the folder in the firemwares folder in M5Burner_Mic.

![Firmwares folder](images/firmwaresfolder.png)

## How to use

Basically the same as M5Burner.

1. Connect M5Stack to a computer.
2. Start M5Burner_Mic, then select port and baud rate.
3. Select the firmware or program you want to install from the presets.
4. Installation starts with the "Start" button.

- The configuration file can be divided into multiple files as long as the extension is .json.

**(Connect as serial montor)**

1. Set baud rate for serial montor.
2. Push "Connect" button. 

<img src="images/connect.png" width="240">

- If it weree connected, the background color of the bottom field change to pink.
- If you want to disconnect it, Push "Dissconnect" button, it is as same as "Connect" button.

<img src="images/montor.png" width="240">

### tips
- You can also use M5Burner_Mic in the official M5Burner **Windows version** folder (see below). However, in the case of Windows version of M5Burner_Mic, it is necessary to put both M5Burner_Mic.exe and M5Burner_Mic Lib folder.

<img src="images/preview.png" width="500">


## Licence

The M5Burner_Mic app itself is [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) Micono (https://github.com/micutil/M5Burner_Mic). You may distribute M5Burner_Mic as an installer for your program in your archive.


## Special thanks

tobozo           https://github.com/tobozo<br>
@o_sio (M5Stack) https://m5stack.com
