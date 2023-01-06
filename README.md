# uSUSbuntu OS

This project is made to fulfill the 1st milestone for the Operating System. It is a simple os that can print a string and read the string from keyboard you pressed, it also can clear the screen and change the cursor position back to left corner.

## Made by

| Name                           |   Nim    |
| ------------------------------ | :------: |
| Muhammad Garebaldhie ER Rahman | 13520029 |
| Rayhan Kinan Muhannad          | 13520065 |
| Aira Thalca Avila Putra        | 13520101 |

## Screenshots

![image](https://user-images.githubusercontent.com/63847012/156034629-ebfcf38c-c7d3-4368-8525-91f661333ecf.png)
![image](https://user-images.githubusercontent.com/63847012/156034667-9fd9a24b-f57f-4de3-bc21-76766125d605.png)

## Technologies Used

1. [VirtualBox](https://www.virtualbox.org/)
2. [Window Subsytem for Linux](https://docs.microsoft.com/en-us/windows/wsl/install)
3. [Ubuntu 20.04 LTS](https://releases.ubuntu.com/20.04/)
4. [Nasm](https://www.nasm.us/)
5. [bcc](https://bochs.sourceforge.io/)
6. bochs
7. c

## Features

This OS was in implementation from the boilerplate given by sister19. In this OS, there are three main function. printString, readString, and clear Screen. printString can print the string you already input. The readString can read the keystrokes you pressed in the keyboard and put it in the buffer. clearScreen can wipe the entire screen leaving nothing except the black background.

## Setup

1. Install all the requirements in the technologies section

```
sudo apt update
sudo apt install nasm bcc bin86 bochs bochs-x make
```

2. Run the virtual machine using VirtualBox (Another option by using [WSL2](https://github.com/Sister19/WSL-Troubleshoot))
3. clone the github repository by using `git clone https://github.com/Sister19/tugas-besar-os-ususbuntu`
4. run `make all run` and viola! the bochs emulator should pop up and the os are ready to be used

## Usage

1. After you run the OS the clearFunction will run by default and it will clear the screen into nothing
2. You can type any character, the character you typed will be put in the buffer with 128 byte size.
3. If you pressed enter, the text you typed before will be output in the next line and you can type another text in the next line

## References

1. [Interrupt](http://www.oldlinux.org/Linux.old/docs/interrupts/int-html/int.htm)
2. [Bios and Dos](https://jbwyatt.com/253/emu/8086_bios_and_dos_interrupts.html)
3. [Milestone1 Doc](https://docs.google.com/document/d/1x9g3kspefka_vBl8JseBROv8f7cQdfEq-59W0jOqmo4/edit#)
