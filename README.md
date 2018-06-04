# Holjeron DotS GUI

Repo for the DotS GUI software for use with the Holjeron ZL.S-F32 and ZL.S-F64

## Supported OS's

* XP, Vista, Seven, 8.x, 10 (x86 & x64 Windows platforms)
 
## Contents: 

* en.stsw-stm32102.zip: Software and installation instructions for STMicro Virtual Comm port 
driver required to use Dot S Software Interface

* DotS V2.0.exe: Executable file to launch Dot S Software Interface.  This is the only file 
you should need to open once the STMicro driver is installed.  
 
* Device files: Several device files are included, which provide configuration settings for
the Dot S interface for specific products: 
     - device8.txt:  ZL.S-AK112
     - device9.txt:  ZL.S-AK112-35
     - device14.txt: ZL.S-DK112
     - device15.txt: ZL.S-DK112-35
     - device16.txt: ZL3.S-AK122
     - device17.txt: ZL3.S-AH122
     - device18.txt: CST-CAS101-1001
     - device19.txt: ZL3.S-AK122-1001/ZL3.S-AK122-1002 (Rev0 and 1)
     - device21.txt: ZL3.S-AK122-1001/ZL3.S-AK122-1002 (Rev2 and Up)
     - device82.txt: Zx3.S-AG422
     - device83.txt: Zx3.S-AM422
     - device84.txt: Zx3.S-MDT423
     - device86.txt: Zx3.S-AG423D
     - device87.txt: Zx3.S-AG423D
* DotS.vshoste.exe, DotS.pdb: Files used by the program that users should not 
need to access under normal operating conditions.  


## How to use 

* All of the files contained in this .zip file should be extracted together, all in the same 
folder.    	

* Install STMicroelectronics  STM32 Virtual Com Port Driver V1.5.0 (included in this package)
     - Download Link: http://www.st.com/en/development-tools/stsw-stm32102.html 
     - Extract the contents of the zip file to a convenient location on your host PC.
     - Go into the folder you extracted to and run the appropriate version of the driver 
       install package, based on the version of Windows youíre running.  
     - Windows 10 Users Please Note: The ST Micro website and readme.txt file with the 
       download indicate that the ìnative inbox driverî provided with Windows should be used, 
       however this does currently work with our software.  Please install the Windows 8 
       version of the driver (either 32 or 64 bit depending on your PC) 
       Note: As of 5/18/2018 the download package says Version 1.5.0, but once installed  
       Device Manager will show it as Version 1.4.0
* Once the ST Micro Virtual Com Port driver is installed and the DotS software is extracted, 
open the DotS.exe executable package to run the ZoneLink™.S Interface GUI

          

## Version Information:

* V2.0 - 05/29/2018

## New Features

* Compatibility with F64 Multi-Configuration Protocol Tool
* Improved Error Handling
	   

(C) COPYRIGHT 2018 Matthews Automation Solutions
