## 05-05-19

So, the linux matter with Durlav Sir's laptop was not an issue as he didn't need the OS or the data in it.

I returned him the laptop and he started working on it as now the arduino driver issue was solved. The next day, he sent for me regarding some issue with the Windows 7. On meeting him, he told me that as a part of the course of *Embedded Systems and 8051 Microcontroller*, he plans to exhibit the various programming boards (some of older generation) and the software used for write code into the boards (being quite old) were not compatible with Windows 7.

One such problematic driver belonged to the 8051 flashing suite by *Mikroelectronika*, I searched their website for compatible drivers (that didn't solve the issue according to Durlav Sir) so I visited their forum and searched for similar issues with the software. Many users seemed to be able to solve the issue by `disabling UAC` so noted this possible fix. 

Another general solution was to create a virtual PC within the laptop and install WinXP on it but I wasn't sure if the USB was going to be connected to the emulated OS. Until then, I had only seen USB sticks, Hard drives and peripherals being shared with the emulated OS. This fix was worth a try and it could solve all OS related issues with other old boards as well.

On the weekend, I went to his lab and tried installing `vmware player` (14.0 latest version) for creating a virtual PC but wasn't successful due to '*incompatibe processor type*'. Later I realized that the new version of vmware player only works on 64-bit OS while the machine had 32-bit OS installed. I searched for compatible version of the software and found that version 6.0 and before were 32-bit compatible. I downloaded and installed version 6.0 with the hope that important features like USB device sharing were still included in these versions. Hopefully, the features were included and tommorow, I shall test out writing on boards using the virtual OS.