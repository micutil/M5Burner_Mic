# M5Burner_Mic

![M5Burner_Mic Icon](images/m5burnermic128.png)

M5Burner by Micono<br>
(Mac and Windows version)

M5Stack is an application that can basically do the same as M5Burner ([https://m5stack.com/download](https://m5stack.com/download)) that transfers the official firms or program to M5Stack. You can load and transfer firms and programs in the firmwares folder at the same level as the M5Burner_Mic application.<br>
(JP: M5Burner_Micは、M5Stackにファームやプログラムを転送するプログラムで、M5Burner（[https://m5stack.com/download](https://m5stack.com/download))と基本的に同じアプリケーションです。 M5Burner_Micアプリケーションと同じ階層にあるfirmwaresフォルダの中に設定ファイルが入っていればプログラムをロードして転送することができます。)

## Update
v1.2.0

- Modified preset menu to be divided into each json file.
- You can use any json file or the folder containing json files by dropping it on the window or the icon of M5Burner_Mic.<br>(JP: どこにあるjsonファイルやそれらが入ったフォルダでも、ドラッグ＆ドロップすればプリセットに追加されます）
- When you drop a **bin file** into the window or the icon of M5Burner_Mic then, the configuration file for installation **be built into the firmwares folder** and added to the preset menu, so you click the start button You can just install it.<br>(JP: ビルドしたbinファイルをドラッグ＆ドロップすれば、設定ファイルがfirmwaresフォルダに構築されます）

v1.1.0

- Added simple serial monitor function.
- Bundled some M5Stack related official firmwares.
- Bundled SetWiFi_Mic

## Download

### Download [here](http://micutil.com/download/M5Burner_Mic.zip), both Mac and Win versions are included.<br>

**Bundled firmwares and programs:**

- M5Stack related official firmwares (M5Bala, M5Cam, M5Cloud, M5Fire, M5Flow, M5GO, M5Unit, FACES_Kit)
- SD-Menu ([tobozo/M5Stack-SD-Updater](https://github.com/tobozo/M5Stack-SD-Updater))
- SetWiFi_Mic ([micutil/SetWiFi_Mic](https://github.com/micutil/M5Burner_Mic))
- Others: my sample program.


### Feature

- The Windows version of M5Burner has firmware in the external firmwares folder, but the Mac version is in the package, so it is troublesome to make it compatible with M5Burner with a self-made application, but M5Burner_Mic is firmwares Because you use firmware in the folder, you do not need to prepare two firmwares for Mac and Win.<br>(JP: M5BurnerのWindows版は、外部のfirmwaresとうフォルダの中にfirmwareが入っていますが、Mac版はパッケージの中に入っているので自作アプリでM5Burner対応にさせるのに面倒であるが、M5Burner_Micは、firmwaresフォルダの中のfirmwareを使うので、firmwaresをマック用とWin用と２つ用意する必要はありません)
- In the Mac version of M5Burner, you can not select a port, but M5Burner_Mic can be selected.<br>(JP: M5BurnerのMac版では、ポートが選べないが、M5Burner_Micは選べます)
- M5Burner may not work well if there is a space in the path or it is a double-byte character, but M5Burner_Mic may work.<br>(JP: M5Burnerはパスにスペースが入ってたり、２バイト文字だったりすると、もしかするとうまく動かないかもしれないけど、M5Burner_Micはもしかすると動くかもしれません)
- M5Burner_Mic reads files with extension .json in the firmwares folder, so you can prepare json files individually.<br>(JP: M5Burner_Micは、firmwaresフォルダの中に入っている拡張子が.jsonというファイルを読み込みますので、jsonファイルを個別に用意することもできます)

![Firmwares folder](images/firmwaresfolder.png)

## How to use

Basically the same as M5Burner.<br>(JP: 基本的にM5Burnerと同じです)

1. Connect M5Stack to a computer.<br>(JP: M5StackとコンピュータをUSBで繋ぎます)
2. Start M5Burner_Mic, then select port and baud rate.<br>(JP:M5Burner_Micを起動し、ポートやボーレートを設定します)
3. Select the firmware or program you want to install from the presets.<br>(JP: プリセットでファームウエアやプログラムを選択します)
4. Installation starts with the "Start" button.<br>(JP: スタートボタンをクリックすると転送が始まります)

- The configuration file can be divided into multiple files as long as the extension is .json.<br>(JP: firmwaresフォルダの中にある拡張子がjsonのファイルをすべて読み込みます。jsonファイルを複数に分けて作っておくことが可能です）

**(Connect as serial montor)**

1. Set baud rate for serial montor.
2. Push "Connect" button. 

<img src="images/connect.png" width="240">

- If it weree connected, the background color of the bottom field change to pink.
- If you want to disconnect it, Push "Dissconnect" button, it is as same as "Connect" button.

<img src="images/montor.png" width="240">

### tips
- You can also use M5Burner_Mic in the official M5Burner **Windows version** folder (see below). However, in the case of Windows version of M5Burner_Mic, it is necessary to put both M5Burner_Mic.exe and M5Burner_Mic Lib folder.<br>(JP: 公式のM5BurnerのWindows版にM5Burner_Micを入れて使うこともできます。)

<img src="images/preview.png" width="500">


## Licence

The M5Burner_Mic app itself is [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) Micono (https://github.com/micutil/M5Burner_Mic). You may distribute M5Burner_Mic as an installer for your program in your archive.


## Special thanks

tobozo           https://github.com/tobozo<br>
@o_sio (M5Stack) https://m5stack.com
