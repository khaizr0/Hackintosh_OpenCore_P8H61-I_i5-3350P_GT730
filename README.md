<p align="center">
	<img src="https://iili.io/JCfJ3u.png" width="200" height="48"/>
</p>

-----
# OpenCore-P8H61-I
Hackintosh on Asus P8H61-I with i5 3350P and GT730 1GB DDR5

[![OpenCore](https://img.shields.io/badge/OpenCore-0.7.0-blue)](https://github.com/acidanthera/OpenCorePkg)
![Support-status](https://img.shields.io/badge/Support-YES-Green)
![BigSur-support](https://img.shields.io/badge/BigSur-YES-Green)

<img align="right" src="https://user-images.githubusercontent.com/54585187/121187703-8c539380-c892-11eb-9975-c45729586469.png" alt="Critter" width="550">
<img align="right" src="https://user-images.githubusercontent.com/54585187/121187968-d3418900-c892-11eb-8699-cf927b9ed805.png" alt="Critter" width="550">
<img align="right" src="https://user-images.githubusercontent.com/54585187/121188066-f10eee00-c892-11eb-851d-fd5f3c20fe9e.png" alt="Critter" width="550">

# Download [here](https://github.com/KhaiZeR0/Hackintosh_OpenCore_P8H61-I_i5-3350P_GT730/releases)

# Hackintosh Spec:
Main Asus P8H61-I (Ver 0909)
Intel Core i5 3350P
GT730 1GB DDR5
8GB DDR3 ram
VIA VT 1708s
Ethernet RTL8111
## Working
- Native Power Management
- Bluetooth
- USB ports
- Internal Audio & Microphone
- Ethernet
- Battery
- Icloud/Facetime/imessage
- etc
## Untesting: Sleep/Wake
## Unknown issue: 
- On Macos 12 Beta 1, Usb bluetooth dongle stop working

### For Big Sur 11.4 and higher: Set xhciportlimit to FALSE

## Before Continue Guide!!

Please use ProperTree for customize config file

(Don't use OpenCore Configuration, Clover Configuration or it will broke your config file)

## Pre Condition

**Bios configuration**
Bios Config | Setting 
:---:| :---:
SATA Operation | AHCI


  
  ## 1. Create OSX Installer
  (I will use Olarila Mojave)
  
  *note: i do not recommended using Olarila to install because mine cause alot of issue with it and i reccommended using REAL vanilla on Apple AppStore or  Dortania OpenCore guide*
  
  1. Download MacOS Mojave From Olarila [here](https://drive.google.com/file/d/11XOoe-3Dcgqy97SJ3DGPSTx9Nz3LJIff/view "Here")
  
  2. Download [this](https://www.balena.io/etcher/ "this")
 
 3. Extract the .raw image
 
 4. Open Etcher, select image, select Drive and flash (Use USB 16GB or higher)
 
 ![Etcher](https://user-images.githubusercontent.com/54585187/78206356-cc69fa00-74c8-11ea-87d4-f380bd9d2b66.gif)

## 2. Install OSX

1. When OC boot screen appears, choose Install OS mojave ... (i guess)

2. The system will then boot into the OS X Installer

3. For a new installation of OS X, you MUST erase and format the destination drive according to the following steps before continuing.

   a. From the menu bar, click Utilities -> Choose Disk Utility
   
   b. Highlight your target hard drive for the High Sierra installation in left column.
   
   c. Click Erase tab
   
   d. Under Scheme: GUID Partition Map
   
   e. Under Name: type HD (You can name anything you want)
   
   f. Under Format: choose APFS
   
   g. Click Erase
   
   h. Close Disk Utility
   
4. Click Continue, Continue, Agree

5. Select name of your existing drive, where you want to install Macos Mojave and click Continue

6. Upon completion, system will restart

7. Press the F12 to choose boot device

8. Choose under UEFI Boot:

9. When OC boot screen appears, choose your existing name drive

10. After Booted successfull, copy your EFI folder from your USB to Hard drive and ready to go :)

# IMPORTANT:
(After installed MacOS sucessful, please change your System info with ProperTree and Clover configuration generate)

<img align="" src="https://user-images.githubusercontent.com/54585187/80679059-5caa5780-8ae6-11ea-9ded-beed34526b00.png" width="600">
<img align="" src="https://user-images.githubusercontent.com/54585187/80678840-ead20e00-8ae5-11ea-8f9e-128a9ed6e1c5.png" width="600">
<img align="" src="https://user-images.githubusercontent.com/54585187/80679145-806d9d80-8ae6-11ea-86d9-27d675b92a2a.png" width="600">


## IF you wanna ask something: 
- [Opencore](https://dortania.github.io/OpenCore-Desktop-Guide/ "OpenCore") Guide
- [Olarila](https://www.olarila.com "Olarila") Website
- [Olarila](https://www.facebook.com/groups/122585311156411 "Olarila") Facebook group
- If you are VietNamese you can go to this [group](https://www.facebook.com/groups/224780132268974/?ref=share "group") and this [group](https://www.facebook.com/groups/hackintosh.vietnam "group")

# AND PLEASE 🙏 DO NOT USING THIS EFI FOR COMMERCIAL PURPOSES
## Credit
- [Apple](https://www.apple.com "Apple") for the Operation System
- [OpenCore](https://dortania.github.io/OpenCore-Desktop-Guide/misc/credit.html "OpenCore") for great Bootloader
- And for some other (i guess :v)
