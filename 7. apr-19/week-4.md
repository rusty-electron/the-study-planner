## 27-04-2019

During the Bihu holidays I haven't been up to much - I took the SIM800 RS232 Modem home to begin testing but due to the lack of debugging tools, I couldn't get it to work. I plan on working on it again soon.

I was able to complete the MP Assignment during the last few days of the vacation and it worked out well. I was able to implement a decent algorithm in 8085 Assembly and It has been submitted. This reminds me that I will have to begin working on the second assignment soon.

So, today as the exam date for the NPTEL MP and MC course - It went well considering the minimal amount of pre-exam preparation put into it. I hope to get a percentage of 80+.

## 28-04-2019

The course content (both books and videos) have arrived and the closed group for the course subcribers is now quite active. So, it is now high time for me to begin serious preparation for the GATE Exams. First of all, I plan to take along the prep for GATE by starting to study the subjects - Signals & Systems and Network Theory. As the NPTEL course is now over, I should be able to devote time into this cause now.

# 29-04-2019

The code for the SIM800 RS232 Modem is completed and I will submit it to the teacher tommorow. The PPC Test went somehow well and I will have to prepare its first lab report within three days.

While writing the code for SIM800, I was able to learn the following new things:

* use of `atof()` to convert character array into float values.
* use of the `Regexp` library for using Regular Expressions within Arduino C code.
* Sample code for extracting lines from `SoftwareSerial`
* use of pointers for slicing arrays in C

## 30-04-19

Although Sir didn't test my SIM800 code today yet he gave me the task of making a fresh install of Windows on his laptop. After some trial and error with various image burning tools like UltraISO and Win32DiskImager - `Rufus` worked out for creating a bootable usb stick for Windows XP. The Windows XP install probably could not find appropriate drivers as the Windows Theme defaulted to *Classic* and no other theme was available (which is generally not the case). Even the LAN cable connection(It appeared that the device had no WiFi Card) was not being detected and I didn't know how to create one manually (and I didn't watch to spend more time troubleshooting). So I decided to install Windows 7 on the machine despite the fact that it had only 2 Gigs of RAM.

I have seen machine running Windows 7 work fine with 2 Gigs of RAM, even my home Desktop is of the same config and it runs well. Therefore, I installed Windows 7 on the machine. Once the installation was over, it turned out that the OS was able to install drivers for the WiFi card (previously assumed absent) and it was now detecting my Mobile Hotspot. Now, I could install and update the drivers via Internet.

In order to restore the bootmenu of RHEL Linux, I had planned to use EasyBCD but after trying I realised that although I may work for Ubuntu but It will not be able to recover the grub of RHEL. So I searched for RHEL5 ISOs for some time for rescuing the grub but wasn't successful so I resorted to recovering the data present in the RHEL partitions. I wrote Ubuntu ISO to a usb stick and live booted it on the machine to access the ext file system. After some `chmod`ing and searching, I realised that there wasn't much data on the partition and therefore, I can simply inquire and then install any other linux distro in place of RHEL. 


