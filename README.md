# Chi-Wah-PC

HONG KONG - 24 May, 2021

My favorite settings on [Windows PCs](http://www.les.hku.hk/teaching-learning/learning-space/windows-pcs-in-the-learning-commons) of [Chi Wah Learning Commons](http://www.les.hku.hk/teaching-learning/learning-space/chi-wah-learning-commons) @ [HKU](https://hku.hk "The University of Hong Kong").

## 1. Taskbar Settings
- Right click on taskbar -> **:gear:Taskbar settings** -> **Notification area** -> **Select which icons appear on the taskbar** -> Turn on **Always show all icons in the notification area**
- Right click on taskbar -> Uncheck **Show Cortana button**
- Right click on **Microsoft Edge** -> **Unpin from taskbar**
- Right click on **Internet Explorer** -> **Unpin from taskbar**

## 2. Windows Security
Turn on **App & browser control**

## 3. Time & Language
- **Settings** -> **Time & Language** -> 
  - **Show additional calendars in the taskbar** -> **Traditional Chinese (Lunar)**
  - **Language** -> 
    - **Preferred languages** -> 
      - **Add a language** -> **Chinese (Simplified, China)** -> **Next** -> **Install**
      - **Chinese (Simplified, China)** -> **Options** -> **Microsoft Pinyin** -> **Options** -> **General** -> **Default mode** -> **Choose IME default mode** -> **English**
    - **Keyboard** -> **Override for default input method** -> **Chinese (Simplified, China) - Microsoft Pinyin**
- (**IME toolbar** -> :gear: -> **Hide IME toolbar**)

## 4. Default Apps
- **Settings** -> **Apps** -> **Default apps** -> 
  - **Web browser** -> **Google Chrome** -> **Switch anyway**
  - (**Video player** & **Music player** -> **VLC media player**)

## 5. Snipping Tool
**Settings** -> **Ease of Access** -> **Keyboard** -> **Print Screen shortcut** -> Turn on **Use the PrtScn button to open screen snipping**

## 6. Brightness & Night Light
- Brightness needs to be manually adjusted on the right side of the display on a *Dell OptiPlex 7450 All-In-One PC*; Or **Settings** -> **System** -> **Display** -> **Change brightness for the built-in display** on a *Lenovo ThinkCentre M920z All-In-One PC*. 
- **Settings** -> **System** -> **Display** -> **Night light settings** -> **Turn on/off now** & **Strength**

## 7. Virtual Desktops
- **Task View** (<kbd>Win</kbd> + <kbd>Tab</kbd>) -> **New desktop**
- Use <kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>&#8592;</kbd>/<kbd>&#8594;</kbd> to switch between them

## 8. Clipboard
<kbd>Win</kbd> + <kbd>V</kbd> -> **Turn on**

## 9. File Explorer
- Expand **This PC**
- **Expand the Ribbon** (<kbd>Ctrl</kbd> + <kbd>F1</kbd>)
- **View** -> Check **File name extensions** & **Hidden items**

## 10. Google Chrome
- Add any previously added extension (usually **Skype** and/or **NCapture**)
- Log into my Google accounts and turn on Sync
- **Adblock Plus** -> :gear: -> 
  - **ACCEPTABLE ADS** -> Uncheck **Allow Acceptable Ads** -> **NO, THANKS**
  -  **LANGUAGE** -> Change to **中文+English**
- **New Tab** -> **Youtube** -> Change to my frequently used account for YouTube -> 
  - A video on **Youtube** with Subtitles/CC -> 
    - Turn off Autoplay
    - **Settings** -> **Subtitles/CC** -> **Options** -> 
      - **Background opacity** -> **50%**
      - **Font family** -> **Monospaced Sans-Serif**
- **New Tab** -> Try each shortcut once until the favicon for each page is loaded and logging into some services

## 11. PDF-XChange Editor
- Download any 2 PDF files
- **Open with** -> **Choose another app** -> Select **PDF-XChange Editor** -> Check **Always use this app to open .pdf files** -> **OK**
- Close when having multiple PDF files open -> **Yes, and don't ask again**

## 12. Spotify
[Download](https://www.spotify.com/us/download/windows/)

After installing and logging in, click on **\<User\>** -> **Settings** ->

- **Display** -> Turn off **See what your friends are playing**
- **SHOW ADVANCED SETTINGS** ->
  - **Startup and window behaviour** -> 
    - **Open Spotify automatically after you log into the computer** -> **No**
    - Turn on **Close button should minimize the Spotify window**

## 13. WhatsApp
[Download](https://www.whatsapp.com/download/?lang=en)

## 14. Windows Ternminal
[Download](https://github.com/microsoft/terminal/releases)

If it fails to install after double clicking on it, try:

```powershell
Add-AppxPackage Microsoft.WindowsTerminal_<versionNumber>.msixbundle
```

## 15. WinSCP
[Download](https://winscp.net/eng/download.php)

I prefer tunneling (**Advanced** -> **Connection** -> **Tunnel**) through `gatekeeper2.cs.hku.hk` when connecting to HKUCS.

## 16. X2Go Client
[Download](https://wiki.x2go.org/doku.php/download:start)

Go to `C:\Users\<User>\AppData\Local`, create a folder `X2Go`, Go into the folder and move the installer there. 

Unzip the installer there. Right click on `x2goclient.exe` and send to desktop (create a shortcut). 

Right click on the shortcut, select **Properties**. Add 

```
 --broker-url=https://x2gobroker.cs.hku.hk/x2gobroker/plain/inifile
```

to the **Target**.

## 17. GitHub Desktop
[Download](https://desktop.github.com/)

## 18. VSCode
[Download](https://code.visualstudio.com/download)

#### Sync Settings with GitHub
Click on the user icon -> **Sign in to Sync Settings** -> **Sign in with GitHub**

## 19. Other issues
- Printing size: If in need to change some printers' default printing size from *Letter* to *A4* or other, go to **Settings** -> **Devices** -> **Printers & scanners** -> Select a printer -> **Manage** -> **Printing preferences** and find out where to change paper size
