---
layout: post
---

# [Windows93](https://www.windows93.net) desktop OS???

Yes. This is not wrong. Simply follow these steps:
- 1. Download [Porteus Kiosk OS](http://porteus-kiosk.org)
- 2. Boot from it
- 3. Configure the network and choose your browser(firefox is recommended)
- 4. Add your config with the following things:

**NOTE: Things in <---...--> needs to be set during the configuration**

```
autohide_navigation_bar=yes
enable_file_protocol=yes
homepage=https://www.windows93.net/#!fullscreen|https://sheeptester.github.io
hostname=kiosk93
persistence=full
password_manager=yes
allow_popup_windows=yes
disable_private_mode=yes
removable_devices=yes
right_mouse_click=yes
screen_settings=Virtual1:1280x960:60.00:normal:normal:normal
screensaver_idle=30
shutdown_menu=reboot restart-session shutdown sleep 
volume_level=95%
timezone=Asia/Shanghai <---YOUR TIME ZONE like: <locale>/<city> --->
wallpaper=http://porteus-kiosk.org/public/wallpapers/sample.jpg
additional_components=uefi.zip 06-fonts.xzm 05-flash.xzm 

```
 
 ! Your original configuration should apply these things: !

```
connection=<---PLEASE SET YOUR NETWORK CONFIG HERE, MINE IS "wired"--->
dhcp=yes
browser=firefox
```
- 5. Set up your disk and install

**NOTE: You can also export ISO file without install to the disk.**

- 6. Enjoy your windows93 desktop!
