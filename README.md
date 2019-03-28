# mpv.net

mpv.net is a libmpv based media player for Windows, it looks and works like mpv, even shares the settings and therefore the mpv documentation applies.

mpv and mpv.net have a learning curve and are only suitable for experienced users.

mpv manual: <https://mpv.io/manual/master/>

Table of contents
-----------------

- [Features](#features)
- [Screenshots](#screenshots)
- [Context Menu](#context-menu)
- [Settings](#settings)
- [Scripting](#scripting)
- [Support](#support)
- [Changelog](#changelog)

### Features

- Customizable context menu defined in the same file as the keybindings
- Addon API for .NET languages
- Scripting API for Python, C#, Lua, JavaScript and PowerShell
- mpv's OSC, IPC, conf files and more

### Screenshots

![](https://raw.githubusercontent.com/stax76/mpv.net/master/screenshots/screenshot.png)

![](https://raw.githubusercontent.com/stax76/mpv.net/master/screenshots/mpvSettingsEditor.png)

### Context Menu

The context menu can be customized via input.conf file located at:
```
C:\Users\username\AppData\Roaming\mpv\input.conf
```
if it's missing mpv.net generates it with the following defaults:

<https://github.com/stax76/mpv.net/blob/master/mpv.net/Resources/input.conf.txt>

### Settings

mpv.net shares the settings with mpv, settings can be edited in a settings dialog or in a config file called mpv.conf located at:
```
C:\Users\user\AppData\Roaming\mpv\mpv.conf
```
if it's missing mpv.net generates it with the following defaults:

<https://github.com/stax76/mpv.net/blob/master/mpv.net/Resources/mpv.conf.txt>

### Scripting

Scripting is supported for Python, C#, Lua, JavaScript and PowerShell

https://github.com/stax76/mpv.net/wiki/Scripting-(CSharp,-Python,-JavaScript,-Lua,-PowerShell)

### Support

<https://forum.doom9.org/showthread.php?t=174841>

<https://forum.videohelp.com/threads/392514-mpv-net-a-extendable-media-player-for-windows>

<https://github.com/stax76/mpv.net/issues>

### Changelog

### 2.0 (2019-03-28)

- setting track-auto-selection added to settings editor (<https://mpv.io/manual/master/#options-track-auto-selection>)
- setting loop-playlist added to settings editor (<https://mpv.io/manual/master/#options-loop-playlist>)
- setting audio-file-auto added to settings editor (<https://mpv.io/manual/master/#options-audio-file-auto>)
- setting video-sync added to settings editor (<https://mpv.io/manual/master/#options-video-sync>)
- command execute-mpv-command added to menu: Tools > Enter a mpv command for execution
- added youtube-dl.exe, please note this will only work when a certain Visual C++ runtime is installed
- added drag & drop support to drag & drop a youtube URL on mpv.net
- added support to open a youtube URL from command line
- added support for opening a URL from the menu: Open > Open URL