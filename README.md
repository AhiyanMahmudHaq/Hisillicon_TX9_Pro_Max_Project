# The Hisillicon TX9 Pro Max Project
*named so because it is allegedly manufactured by Hisillicon*
## **Disclaimer**
* **I am not responsible for any of the damages that may be inflicted to your device.** 
* **The incorrect installation of an operating system (OS) on an embedded computer system may render it permanently unuseable, often referred to as *"bricking."***
* **Never violate the End User License Agreement of a manufacturer's device, *violations include reverse engineering the source code of properietary software and then uploading it to the internet or using it for commercial purposes.***
* **If users intend to install their own system software on such devices, they must analyze the device's hardware specifications and think critically before attempting to do so.**

## Preface
The Hisillicon TX9 Pro Max Project's GitHub repository is dedicated to the development of a custom build of the Armbian Trixie GNU/Linux distribution (minimal or server variant), referred onwards as Armbian GNU/Linux, for the use of a cheap, common TV box that goes by the name of 'TX9 Pro Max.' Since the device is an open-source, white-label product; many different third-party Chinese companies resell it, so I did not specify its brand (the company that sells it). The TV box is found in television (TV) box and video accessories stores across Bangladesh. Although the box which it came from claim highly performative device hardware specifications (e.g., 256 Gigabytes (GB) of on-device non-volatile memory, 16 GB of Random Access Memory (RAM), Allwinner H313 System on a Chip (SoC)) the TV box comprises of significantly less performative device hardware specifications, as given below:

<img width="589" height="601" alt="Screenshot from 2026-06-24 13-32-07" src="https://github.com/user-attachments/assets/946d4ac7-df1b-49bc-a556-c56b798f5e4e" />

I initially began developing this project to learn more about embedded Linux systems, as I aspire to work professionally with embedded and IoT systems. The project includes the important documentation of the Linux kernel, running on the Allwinner H616 SoC. Allwinner H616 (sun50iw9p1) is a SoC that features a Quad-Core Cortex-A53 ARM CPU, and a Mali-G31 MP2 GPU from ARM. It is targeted for low-end TV boxes that require hardware accelerated transcoding capability for media streaming, usually of popular media streaming platforms like YouTube (e.g., Tanix TX9, Tanix TX9 Pro (original), TX9 Pro Max (non-specific brand; counterfeit model), X96, X96Q, etcetera). [Source](linux-sunxi.org/H616)

This repository contains the full procedure of research, development and installation of the custom build of Armbian GNU/Linux, on the H616-powered machine. It even includes the mistakes that were made during the entire process. The whole project, including all the files are protected as *open-source* and is provided with *absolutely* no warranty, to the extent the law provides. Therefore, you do not require crediting the owner.

## Research

The primary resource for learning how to build the customized variant of Armbian GNU/Linux for this exact TV box are Wikipedia pages and documentation from [linux-sunxi.org](linux-sunxi.org) which provide information about core concepts that are mandatory to understand ARM (ARM64) architecture's system software which is important for embedded computing.
