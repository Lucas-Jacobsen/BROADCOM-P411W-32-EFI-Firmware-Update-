# BROADCOM-P411W-32-EFI-Firmware-Update-
```
[user@localhost ~]$ cd /home/user/Downloads/SFW-00414_Rev_B_Folder/SFW-00414_Rev_B/G4xFLASH_SAS3.5_P18_0/Linux/
[user@localhost Linux]$ sudo ./g4Xflash.x86_64 

-------------------------------------------------------------
g4Xflash v4.3.13.0 - Broadcom Inc. (c) 2021
-------------------------------------------------------------


  DeviceId/RevId  WWID               FwVersion        Type            
  1) PEX88048 B0  500605b0:000272bf  00.01.02.00      Switch (IT)

Enter the target index to connect with : 1
PEX88048 B0> show 
Product Id                : PEX88048 B0
Firmware Version          : 00.01.02.00
SAS Address               : 500605b0:000272bf
Vendor Id                 : BROADCOM
Mfg. Product Id           : PEX88048
Revision Level            : 0013
Mfg. Associated FW Rev    : 00:01:00:00
Mfg. Revision             : 00:01:00:01
Product Name              : PEX88048            
Platform Name             : P411W-32P HBA       
Mfg. Time Stamp           : 02/13/20  14:54
Platform Serial           : HBA-1234
Temperature *C/*F         : 31.1 *C / 87.7 *F
PCI Bus Location          : 00:9B:00:00
System Time               : 11/05/2026 08:34:41
PEX88048 B0> dl -f /home/user/Downloads/SFW-00414_Rev_B_Folder/SFW-00414_Rev_B/P411W-32P_4_1_2_1_HBA_signed_P14.2.fw/P411W-32P_4_1_2_1_HBA_signed_P14.2.fw/Firmware/4.1.2.1_pci4armfw_hba_signed.fw
Current Flash image, 
     FW Image Size : 369512
        FW Version : 0.1.2.0
      Concatenated : YES
    SBR Bootloader : YES
      Config Pages : YES
      Signed Block : YES
   KeyUpdate Block : Not Available
Secure Boot Enabled : YES
Secure Boot Status : Passed
Replace firmware details, 
     FW Image Size : 369512
        FW Version : 0.1.2.0
      Concatenated : YES
    SBR Bootloader : YES
      Config Pages : YES
      Signed Block : YES
   KeyUpdate Block : Not Available
Secure Boot Enabled : YES
Secure Boot Status : Passed
Do you want to continue to perform 'Download' (Yes/No) : Yes
 - Downloading the image...
 - Image has been sent to firmware.
 - Post validating image by uploading back.
 - Post validation of the image is successful.
Image has been downloaded successfully. Restart the system to make the fresh image active.
PEX88048 B0> 
