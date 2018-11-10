# linux-configuration

## Wine/Office 2010 ugly font fix

Source: https://wiki.archlinux.org/index.php/Wine#Fonts

> If the fonts look somehow smeared, import the following text file into the Wine registry with regedit:
> 
> ```
> Windows Registry Editor Version 5.00
> [HKEY_CURRENT_USER\Software\Wine\X11 Driver]
> "ClientSideWithRender"="N"
> ```
