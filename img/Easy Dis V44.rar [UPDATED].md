# How to Install Easy DIS v44 for BMW Diagnostic Software
  
If you are looking for a way to install DIS v44, a diagnostic software for BMW vehicles, you may have come across Easy DIS v44, a simplified version that comes with an ISO file and a VMWare virtual machine. In this article, we will show you how to install Easy DIS v44 step by step and what you need to prepare before you start.
  
## What is Easy DIS v44?
  
Easy DIS v44 is a modified version of DIS v44, which stands for Diagnostic Information System. It is a software that allows you to connect to your BMW car's computer and perform various diagnostic functions, such as reading and clearing fault codes, checking live data, programming modules, coding options, etc. Easy DIS v44 is designed to work with a USB-OBD cable or a serial-OBD cable that connects your laptop to your car's OBD port.
 
**Download • [https://t.co/HzlMhaLS0V](https://t.co/HzlMhaLS0V)**


  
Easy DIS v44 comes with two ISO files: Easy DIS v44 BASE and Easy DIS v44 Programs. The BASE file contains the operating system and the basic software needed to run DIS v44, while the Programs file contains the actual diagnostic programs for different BMW models. You will need to mount these ISO files using a software like Daemon Tools and install them on a VMWare virtual machine.
  
## What do you need to install Easy DIS v44?
  
Before you start installing Easy DIS v44, you will need the following:
  
- A laptop running Windows, preferably XP SP2.
- A USB-OBD cable or a serial-OBD cable that is compatible with your BMW car.
- INPA / EDIABAS software, which is a prerequisite for running DIS v44.
- VMWare Workstation version 6 or later, which is a software that allows you to create and run virtual machines.
- Easy DIS v44 BASE iso and Easy DIS v44 Programs iso files, which you can download from various online sources[^1^] [^2^] [^4^].
- Daemon Tools software, which is a software that allows you to mount ISO files as virtual drives.
- Diag Head Emulator software, which is a software that emulates the diagnostic head device that is normally used with DIS v44.

## How to install Easy DIS v44 step by step?
  
Once you have all the required software and hardware ready, you can follow these steps to install Easy DIS v44:

1. Disable Windows Firewall and Anti Virus on your laptop.
2. Install drivers for your USB-OBD cable or serial-OBD cable and make sure it is set as port COM1.
3. Install / update INPA / EDIABAS using ADS interface, not OBD. Change environment path in Windows to c:/ediabas/bin. Install ADS Setup and OBD Setup. Edit ediabas.ini and change remote-host and port.
4. Install VMWare Workstation using default parameters during setup. Open VMWare and create a new virtual machine with typical settings. Name the VM, select host only networking, enter size of disk as 18.635 GB and allocate all disk space now.
5. Remove the sound adapter from the virtual machine settings. Adjust Ethernet adapter to use VMnet1. Add two additional Ethernet adapters and also assign them VMnet1. Switch to the options tab and uncheck drag and drop from guest isolation.
6. Mount Easy DIS v44 BASE iso file in Daemon Tools. Edit the CD drive of your virtual machine to use the Daemon Tools drive. Start the virtual machine and quickly press F2 to enter the BIOS for it. Set the CD-Rom to be the first boot device. Save and exit the BIOS. The installation of GT1 begins.
7. The installation ends and you are notified to eject the CD and restart the VM, but do not do that yet. Eject the iso file from Daemon Tools and mount Easy DIS v44 Programs iso file in Daemon Tools. Now shut off the virtual machine and restart it.
8. Return to the BIOS by pressing F2 and set the boot order back to default. Save and exit and the VM will boot up. Select 8cf37b1e13


