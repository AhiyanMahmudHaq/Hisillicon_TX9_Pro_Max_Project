# The Hisillicon TX9 Pro Max Project

*named so because it is allegedly manufactured by Hisillicon*

## **Disclaimer**
* **I am not responsible for any of the damages that may be inflicted to your device.** 
* **The incorrect installation of an operating system (OS) on an embedded computer system may render it permanently unuseable, often referred to as *"bricking."***
* **Never violate the End User License Agreement of a manufacturer's device, *violations include reverse engineering the source code of properietary software and then uploading it to the internet or using it for commercial purposes.***
* **If users intend to install their own system software on such devices, they must analyze the device's hardware specifications and think critically before attempting to do so.**

## Preface
The Hisillicon TX9 Pro Max Project's GitHub repository is dedicated to the development of a custom build of the Armbian Trixie GNU/Linux distribution (minimal or server variant), referred onwards as Armbian GNU/Linux, for the use of a cheap, common TV box that goes by the name of 'TX9 Pro Max' as a GNU/Linux device. Since the device is most likely an open-source, white-label product; many different third-party Chinese companies resell it, so I did not specify its brand (the company that sells it). The TV box is found in television (TV) box and video accessories stores across Bangladesh. Although the box which it came from claim highly performative device hardware specifications (e.g., 256 Gigabytes (GB) of on-device non-volatile memory, 16 GB of Random Access Memory (RAM), Allwinner H313 System on a Chip (SoC)) the TV box comprises of significantly less performative device hardware specifications, as given below:

<img width="589" height="599" alt="image" src="https://github.com/user-attachments/assets/82acb34f-fb77-4313-a1b1-89ff9099bd07" />

I initially began developing this project to learn more about embedded Linux systems, as I aspire to work professionally with embedded and IoT systems. The project includes the important documentation of the Linux kernel, running on the Huawei-manufactured Hisillicon Hi3798MRCBV30100.  (; in community made system software) is a SoC that. It is targeted for low-end TV boxes that require hardware accelerated transcoding capability for media streaming, usually of popular media streaming platforms like YouTube (e.g., Tanix TX9, Tanix TX9 Pro (original), TX9 Pro Max (non-specific brand; counterfeit model), X96, X96Q, etcetera).

This repository contains the full procedure of research, development and installation of the custom build of Armbian GNU/Linux, on the -powered machine. It even includes the mistakes that were made during the entire process. The whole project, including all the files are protected as *open-source* and is provided with *absolutely* no warranty, to the extent the law provides. Therefore, you do not require crediting the owner.

## Research

The primary resources are sourced from Wikipedia and Hisillicon's official website (states SoC specifications for a similar variant of the chip in this TV box) as well as datasheets for other microchips found floating in the internet which explicitly state specifications.
* Wikipedia links to important definitions/core concepts
[Das U-Boot](https://en.wikipedia.org/wiki/Das_U-Boot)
[Bootloader](https://en.wikipedia.org/wiki/Bootloader)
[Boot ROM](https://en.wikipedia.org/wiki/Boot_ROM)
[Android TV OS](https://en.wikipedia.org/wiki/Android_TV)
[eMMC](https://en.wikipedia.org/wiki/MultiMediaCard#eMMC)
[Hi3798MV310](https://www.hisilicon.com/en/products/smart-media/stb/hi3798mv310)


