# chare
share, chare, misc, ect, configuration
## Centos remove unused packages
```
yum remove empathy cheese gnome-dictionary gnome-contacts\
    gnome-weather totem orca system-config-printer gnome-tweak-tool\
    pulseaudio-utils alsa-plugins-pulseaudio gnome-video-effects\
    alsa-firmware alsa-utils\
    system-config-printer-udev system-config-printer-libs gutenprint firewalld 
```

## Centos install teamviewer
```
rpm -i teamviewer_13.1.8286.x86_64.rpm
warning: teamviewer_13.1.8286.x86_64.rpm: Header V4 RSA/SHA1 Signature, key ID 0c1289c0: NOKEY
error: Failed dependencies:
       libQt5Qml.so.5()(64bit) >= 5.5 is needed by teamviewer-13.1.8286-0.x86_64
       libQt5Quick.so.5()(64bit) >= 5.5 is needed by teamviewer-13.1.8286-0.x86_64
       libQt5WebKit.so.5()(64bit) >= 5.5 is needed by teamviewer-13.1.8286-0.x86_64
       libQt5WebKitWidgets.so.5()(64bit) >= 5.5 is needed by teamviewer-13.1.8286-0.x86_64
       libQt5X11Extras.so.5()(64bit) >= 5.5 is needed by teamviewer-13.1.8286-0.x86_64
       qt5-qtdeclarative >= 5.5 is needed by teamviewer-13.1.8286-0.x86_64
       qt5-qtquickcontrols >= 5.5 is needed by teamviewer-13.1.8286-0.x86_64
   
yum install epel-release
yum install qt5-qtwebkit qt5-qtx11extras qt5-qtquickcontrols
```
