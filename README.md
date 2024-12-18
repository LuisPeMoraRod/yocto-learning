# Embedded Linux using Yocto
This repository contains the notes taken from Udemy course: [Embedded Linux using Yocto](https://www.udemy.com/course/embedded-linux-using-yocto/)

## Introduction
### Elements of embedded Linux
1. **Toolchain:** The compiler and other tools (like assembler, linker, loader) needed to create code for your targe device. Everything else depends on the toolchain.
2. **Bootloader:** The program that initializes the board and loads the Linux kernel.
3. **Kernel:** This is the heart of the system. Managis system resources and interfacing with hardware.
4. **Root filesystem:** Contains the libraries and programs that are run once the kernel has completed its initialization.
5. **Programs:** One more element can be the colleciton of programs specific to the embedded aplication which make the device what it is supposed to do.

### What is Yocto?
Non-technically speaking, Yocto is the smallest SI metric system prefix: y = 10^-24

### What is Yocto Project?
Yocto Project provides open-source, high quality architecture and tools to help developers create their own custom Linux distribution for any hardware architecture.

It was founded in 2010, in an effort to reduce work duplication, provide resources and information catering both new and experienced users. It was possible thanks to the collaboration of many hardware manufacturers, open-source operating system vendors and electronic companies. Yocto is also a project working group of the [Linux Foundation](https://www.yoctoproject.org/). 
