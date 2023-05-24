# VirtualBox Portable
VirtualBox Portable is a set of files that allows you to configure 90% of a VirtualBox Portable to which you can take your own portable operating systems an alternative to VBox.me

It is available in Italian and English
The current version of VirtualBox may not be the latest but it is quite stable it is 5.1.38

After extracting the files for VirtualBox at the end of the installation you can decide whether to install the Drivers and close, you can do it manually by double-clicking on the "Install.exe" file which will install all the drivers to make VirtualBox work, if you are done using VirtualBox on that computer just run "Uninstall.exe" to uninstall all the Drivers and then you can remove the USB stick (If in case you are using it on Stick)

Your virtual machines will be stored in the "Virtual Machines" folder while all the VirtualBox settings including the VirtualBox.xml will be stored in the Home folder

Attention!:
If in case you have installed the VirtualBox Drivers and you are unable to boot the VMs with this error
STATUS_OBJECT_NAME_NOT_FOUND

![VirtualBox_Windows 7_24_05_2023_16_07_57](https://github.com/Sorecchione07435/VirtualBox_Portable/assets/111366201/31ee2c22-ee69-4fa8-9ab6-b252b338fdcf)

to solve this error, just run a command prompt as administrator and check the status of the VBoxDrv service, and if it is stopped you can start it by writing "sc start VBoxDrv" and the problem should be solved

and that's all, if you are interested in trying it you can download it in this link

Download VirtualBox 5.1.38 Portable: http://sorecchione07.altervista.org/Downloads-URLS/VirtualBox/Online_Installer/5.1.38/VBox-5.1.38-x64P.msi (Only 64 Bits)
Download VirtualBox 6.1.40 Portable: It will be out soon

If in case you are unable to download the ISO for the Guest Additions from the installer you can download them manually from this link:
5.1.38 (http://sorecchione07.altervista.org/Downloads-URLS/VirtualBox/Online_Installer/5.1.38/VBoxGuestAdditions_5.1.38.iso)
