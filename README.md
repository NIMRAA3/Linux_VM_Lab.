# Cisco Lab VM Workstation – Linux VM Installation Lab

## Overview

This repository contains the lab report for installing and using **Cisco Lab VM Workstation** and **Security Workstation** virtual machines on a personal computer using **Oracle VirtualBox**.

The lab demonstrates how to prepare a host computer for virtualization, import pre-configured VM images, and use them for hands-on exercises safely and efficiently.



## Objectives

1. Prepare a computer for virtualization.
2. Import virtual machines into VirtualBox inventory.
3. Familiarize with Cisco Lab VM and Security Workstation environments.

---

## Background

Virtualization allows multiple virtual computers (VMs) to run on a single physical computer (host). Cisco Lab VM Workstation provides a pre-configured Linux environment with essential tools such as:

* Wireshark (network protocol analyzer)
* jcryptool (cryptography tool)
* Terminal access
* Web browser

The VM ensures a safe and standardized environment for students to perform networking and cybersecurity labs.


## Required Resources

* Computer with at least **4 GB RAM** and **50 GB free disk space**.
* High-speed internet for downloading VirtualBox and VM images (\~5 GB).
* **Oracle VirtualBox** software and **Extension Pack** installed.

**Note:** 64-bit host system with hardware virtualization enabled in BIOS is required for 64-bit VMs.



## Lab Steps

### Part 1: Prepare Host Computer

1. Download and install [Oracle VirtualBox](https://www.virtualbox.org).
2. Install **VirtualBox Extension Pack** for USB 2.0/3.0 and RDP support.
3. Download VM images: **CSE-LABVM** and **Security Workstation**.
   #MY virtualbox file
 "C:\Users\DELL\Downloads\VirtualBox-7.2.2-170484-Win.exe"
#MY Oracle virtualbox extention file
"C:\Users\DELL\Downloads\Oracle_VirtualBox_Extension_Pack-7.2.2 (1).vbox-extpack"
# cisco CSE LAB workstation file (all tools in one file no need of any iso file )
"D:\ciscovm\Cybersecurity_Lab_VM_Worksation_20250409.ova"

### Part 2: Import Virtual Machines

1. Open VirtualBox → File → Import Appliance.
2. Select the `.OVA` file and import.
3. Adjust settings:

   * Machine Base Folder → Documents
   * MAC Address Policy → Generate new MAC addresses
4. Start the VM and log in:

**CSE-LABVM:**

* Username: `cisco`
* Password: `password`

**Security Workstation:**

* Username: `analyst`
* Password: `cyberops`

5. Familiarize yourself with pre-installed tools and VM environment.
6. Shutdown VMs using **File → Close → Save the machine state**.



## Reflection

**Advantages of Virtual Machines:**

* Cost-efficient
* Hardware virtualization
* Easy backup and snapshots

**Disadvantages of Virtual Machines:**

* Performance overhead
* Potential security risks



## Conclusion

The lab demonstrates installing and using pre-configured Linux virtual machines on a personal computer. Both **CSE-LABVM** and **Security Workstation** are ready for use in future networking and cybersecurity exercises.
full report link wth screenshots 
 [click here to download file ](https://github.com/NIMRAA3/Linux_VM_Lab./blob/main/LINUX%20Lab.docx)

