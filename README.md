# M5Burner_Mic

![MacDown logo](images/m5burnermic128.png)

M5Burner by Micono
(Mac and Windows version)

M5Stack is an application that can basically do the same as M5Burner ([https://m5stack.com/download](https://m5stack.com/download)) that transfers the official firms or program to M5Stack. You can load and transfer firms and programs in the firmwares folder at the same level as the M5Burner_Mic application.

## Download

Download [here](http://micutil.com/download/M5Burner_Mic.zip), both Mac and Win versions are included.
This download archive includes the SD-Menu ([tobozo/SD-Updater](https://github.com/tobozo/M5Stack-SD-Updater)) as a bin file that can be installed with M5Burner_Mic.

### Feature

- The Windows version of M5Burner has firmware in the external firmwares folder, but the Mac version is in the package, so it is troublesome to make it compatible with M5Burner with a self-made application, but M5Burner_Mic is firmwares Because you use firmware in the folder, you do not need to prepare two firmwares for Mac and Win. (M5BurnerのWindows版は、外部のfirmwaresとうフォルダの中にfirmwareが入っていますが、Mac版はパッケージの中に入っているので自作アプリでM5Burner対応にさせるのに面倒であるが、M5Burner_Micは、firmwaresフォルダの中のfirmwareを使うので、firmwaresをマック用とWin用と２つ用意する必要はありません)
- In the Mac version of M5Burner, you can not select a port, but M5Burner_Mic can be selected. (M5BurnerのMac版では、ポートが選べないが、M5Burner_Micは選べます)
- M5Burner may not work well if there is a space in the path or it is a double-byte character, but M5Burner_Mic may work. (M5Burnerはパスにスペースが入ってたり、２バイト文字だったりすると、もしかするとうまく動かないかもしれないけど、M5Burner_Micはもしかすると動くかもしれません)
- M5Burner_Mic reads files with extension .json in the firmwares folder, so you can prepare json files individually. (M5Burner_Micは、firmwaresフォルダの中に入っている拡張子が.jsonというファイルを読み込みますので、jsonファイルを個別に用意することもできます)

![MacDown logo](images/firmwaresfolder.png)



## How to use

Basically the same as M5Burner.

1. Connect M5Stack to a computer.
2. Start M5Burner_Mic, then select port and baud rate.
3. Select the firmware or program you want to install from the presets.
4. Installation starts with the "Start" button.

- The configuration file can be divided into multiple files as long as the extension is .json.

- You can also use M5Burner_Mic in the official M5Burner **Windows version** folder (see below). However, in the case of Windows version of M5Burner_Mic, it is necessary to put both M5Burner_Mic.exe and M5Burner_Mic Lib folder.

![MacDown logo](images/preview.png)


## Licence

The M5Burner_Mic app itself is [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) Micono (https://github.com/micutil/M5Burner_Mic). You may distribute M5Burner_Mic as an installer for your program in your archive.


## Special thanks

tobozo  https://github.com/tobozo 
