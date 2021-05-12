---
layout: post
---

# Faster livecd 🚀

- Download [pclinuxos KDE or others in this page](https://www.pclinuxos.com/?page_id=180)
- boot livecd and run "install me"
- install OS to disk or virtual machine
- install "draklive-install" and "mylivecd"
- do the changes to the OS
- When you are satisfied, run:
```
umount -a    # in a root shell by using 'su'
mylivecd myimage.iso
```
This should return:
```
[root@domain dir]# mylivecd name.iso
mylivecd, version 0.9.10, http://pclinuxos.com/
Copyright (C) 2016, Texstar <texstar at gmail.com>

This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or (at your option) any later version.

Disabling Services not needed on the LiveCD

running: /sbin/chkconfig --list
running: chkconfig --del atd
running: /sbin/chkconfig --list
running: chkconfig --del cups
running: /sbin/chkconfig --list
running: chkconfig --del cups-browsed
running: /sbin/chkconfig --list
running: chkconfig --del crond
running: /sbin/chkconfig --list
running: chkconfig --del rsyslog
running: /sbin/chkconfig --list
running: chkconfig --del xinetd
running: /sbin/chkconfig --list
running: chkconfig --del haldaemon
running: /sbin/chkconfig --list
running: chkconfig --del vnstat
running: /sbin/chkconfig --list

Creating initrd:                                   [100.00% 00:00:11/00:00:11]
Setting filesystem parameters:                     [100.00% 00:00:29/00:00:29]
Creating compressed image:                         [100.00% 00:03:48/00:03:48]
Creating isolinux boot:                            [100.00% 00:00:00/00:00:00]
Creating UEFI boot image:                          [100.00% 00:00:01/00:00:01]
Creating final iso:                                [100.00% 00:00:10/00:00:10]
                                                                              
Restoring Services on the installed system

running: chkconfig --add atd
running: chkconfig --add cups
running: chkconfig --add cups-browsed
running: chkconfig --add crond
running: chkconfig --add rsyslog
running: chkconfig --add xinetd
running: chkconfig --add haldaemon
running: chkconfig --add vnstat

Created 'name.iso' (1819,279,360 bytes) in 00:04:46
```

- The file should in this directory. "name.iso"
