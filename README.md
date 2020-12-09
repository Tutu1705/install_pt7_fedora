## Install_pt7_fedora

1. Install dependencies:
```shell
sudo dnf -y install https://rpmfind.net/linux/opensuse/distribution/leap/15.2/repo/oss/x86_64/libjpeg8-8.1.2-lp152.7.3.x86_64.rpm double-conversion.x86_64
```

2. Create links for libs:
```shell
sudo ln -s /lib64/libicui18n.so.65.1 /lib64/libicui18n.so.60
sudo ln -s /lib64/libicuuc.so.65.1 /lib64/libicuuc.so.60
sudo ln -s /lib64/libdouble-conversion.so.3.1.5 /lib64/libdouble-conversion.so.1
```

3. Build AppImage or download the AppImage from: https://github.com/Diolinux/PacketTracer-AppImage.


4. Flag AppImage package as executable:
```shell
chmod +x appimage/package/folder
```
