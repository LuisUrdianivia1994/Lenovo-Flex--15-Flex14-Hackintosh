# Lenovo-Flex-15-and-Flex14-OpenCore-Hackintosh

This is My Hackintosh Build On OpenCore. 99% compatibility with MacOS /HighSierra/Catalina/BigSur 

Lenovo IdeaPad Flex 14 / Flex 15


![Captura de Pantalla 2022-03-30 a la(s) 4 40 02 a m](https://user-images.githubusercontent.com/85201616/160813347-8d471c8e-105c-4a24-88a2-6c3f0f0365b1.png)




Instruccions to Make it
  
create your Usb With a Mac os image following Dortania guide

https://dortania.github.io/OpenCore-Install-Guide/installer-guide/mac-install.html

------------------
IMPORTAND NOTE

On My Personal Experiense 
I recommend you to use Mac Os or PC with Hackintosh to Create Usb

---------------------------------------------------------

Installation 

·Once done, Mount USB EFI Memory

·Copy My EFI Folder

[EFI.zip](https://github.com/LuisUrdianivia1994/Lenovo-Flex--15-Flex14-Hackintosh/files/6605071/EFI.zip)


·Unzip 

·Paste My EFI Folder Inside Usb EFI 

·shutdown Your Laptop 

·Press Novo Button and Enter in Bios Menu

·Go to [Boot] Section 

·Move USB to be first in the boot sequence.

·Save Changes And exit 

·once your See Opencore Boot And Select Install

·The rest as language and formatting options 


IMPORTAND NOTE


·I recommend the APFS file system and GUID partitions system
--------------------------------


Post Install

·When Istalation Is Done Mount USB EFI and Copy EFI Folder (paste it on Secure Ubication)

·Mound your HDD or SSD EFI and Paste EFI folder inside them 

·Umount all EFI drivers, and Pull out your USB and Restart

(This is to Boot without the need for USB)


  DONE!!
  
  
-------------------

iT Works

 ·Audio ALC 283 [Works] AppleALC.    ❌VoodoooHDA.kext

 ·Intel HD Graphics  4400 [Works]

 ·Brigness [Works]

 ·TouchPad [Works]

 ·Keyboard [Works]

 ·WebCam [Works]

 ·Headphones Plug [Works]

 ·Usb Energy [Works]
 
 ·HDMI OUT. [Works]
 
 
 
   (New Update) Sunday 6 June 2021 
   
   
 
 ·Battery Status.  [Works]

 ·Ambient ligh Sensor  [Works]
 
 ·Bluethooth (AR9485) (Needs boot whit USB already kext injected)  [Works]
 
 ·Touchpad Smart Gestures [Works]
 
 (ONLY add ApplePS2Smarttouchpad.kext in OC/kext and apply changes in config.plist)
 
 
 
 
 (New Update) Monday 7 June 2021
 
 
 ·Wifi (AR9585) [Works]
 
 
 ·Sleep Mode [Works]

 

--------------------------

 Not Works ❌
 
 it works now ✓


  
  ·Ethernet (i have kext) but my conector is broken im not use ....LOL
  
  
  ·HDMI AUDIO OUT


-------------------

Resolved
 

High Noise on Internal Microphone


USB mapping always Says needs Rename but is allready named and Usb ports mapped 


Sleep Mode [Works But Bluethooth and usb porst down]

-------------------

New update

Wednesday 30 March 2022


Change list

- SMbios MacbookPro11,4 to update Monterey (don't update if you have AR9485)

- Asome ACPI added:


- SSDT-WMIS 

- SSDT-TVPC

- SSDT-DMAC

- SSDT-EHCx-disable

- SSDT-ECRW (to use YogaSMC kext)

-------------------------

Correction On DSDT

- Some error warnings and EHCI renames are corrected 

- Layout ID : 3

- some devices had to be set ASPM disabled like northbridge and network adapter


Miscellaneous:
 
- BootChime and Boot "PickerMode" 

Additional Information

- ⚠️Generate your own Serial Number and MBL for obvious reasons⚠️



