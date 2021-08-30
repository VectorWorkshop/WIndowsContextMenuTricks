# Context menu tricks for Windows

## Add to search

In Windows 10 you can execute apps using Windows Search. Some apps doesn't automaticaly add themeselves to Search. Yes you can pin it in to Start menu or put shortcut to program in `C:\ProgramData\Microsoft\Windows\Start Menu\Programs`. But my addition to Windows registry can do it for you automaticaly, just follow steps:

### Installation

Download latest [AddToSearch.reg](https://github.com/VectorWorkshop/WIndowsContextMenuTricks/blob/main/AddToSearch/AddToSearch.reg) and execute it.

### Using

Create and rename a shortcut to any program, right-click it and select `Add to search`. Shortcut will be copied to `C:\ProgramData\Microsoft\Windows\Start Menu\Programs` and **deleted**

![Screenshot](https://user-images.githubusercontent.com/87804989/131368476-2434d2bf-5f9d-4f6e-9531-04cac9c86e97.png)
