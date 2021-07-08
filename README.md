# EFI-catalina-HP15ac136nv
This is the needed and tested EFI files for the HP Laptop 15ac136nv.
They have been used with the latest version of OpenCore 0.7

![1625753893044](https://user-images.githubusercontent.com/6118285/124938264-d30ee780-e010-11eb-8255-30f6d93c6e29.jpg)



It has been tested and works fine with Catalina 10.15.7

What is NOT working so far:
wifi (I have used a cheap external usb adapter RTL8188CUS that works fine. Driver is included thanks to https://github.com/chris1111/Wireless-USB-Adapter)
bluetooth
Radeon gpu

How to install:

1)Use a free program like EFI Mounter v3.1 in order to mount the EFI partition of your hd
2)Unzip the file EFI.zip to that folder...this will also make your hd bootable in case that you still use a usb boot.
3)Reboot your system


Please, make sure that you are aware of the needed mods for making your new mac unique, because I have not included them for obvious reasons:
https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html#using-gensmbios

You are free to modify and test further.

