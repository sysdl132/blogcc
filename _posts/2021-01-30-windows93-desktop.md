---
layout: post
---

# [Windows93](https://www.windos93.net) desktop OS???

Yes. This is not wrong. Simply follow these steps:
- 1. Download [Porteus Kiosk OS](http://porteus-kiosk.org)
- 2. Boot from it
- 3. Configure the network and choose your browser(firefox is recommended)
- 4. Load an config like the following things:
```
connection=<---PLEASE SET YOUR NETWORK CONFIG HERE, MINE IS "wired"--->
dhcp=yes
browser=firefox
autohide_navigation_bar=yes
enable_file_protocol=yes
homepage=https://www.windows93.net/!#fullscreen
hostname=win93
password_manager=yes
allow_popup_windows=yes
disable_private_mode=yes
removable_devices=yes
right_mouse_click=yes
shutdown_menu=lock reboot restart-session shutdown sleep 
timezone=Etc/GMT+8
wallpaper=https://ss3.bdstatic.com/70cFv8Sh_Q1YnxGkpoWK1HF6hhy/it/u=2267195964,945477003&fm=26&gp=0.jpg
additional_components=uefi.zip 05-flash.xzm 
```
- 5. Set up your disk and install
##### Note:You can also export ISO file without install to the disk.
- 6. Enjoy your windows93 desktop!
