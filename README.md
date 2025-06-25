ThisariOS – A 16-Bit Real Mode Operating System

ThisariOS is a simple 16-bit real-mode operating system built using x86 Assembly. It runs on virtual machines like QEMU or VirtualBox and features a basic command-line interface using BIOS interrupts.

Features:
- Bootloader written in NASM
- Real-mode 16-bit OS
- Command-line interface with the following commands:
  - clear – Clears the screen
  - info – Displays system information (memory, CPU, drives)
  - help – Lists available commands
  - Unknown input – "Error: Command not found"

Tools Used:
- NASM – Netwide Assembler
- QEMU – Emulator for testing
- Visual Studio Code – Editor with Assembly support
- VirtualBox – For ISO testing

How to Build and Run:
1. Assemble with NASM:
   nasm -f bin bootloader.asm -o thisarios.img
2. Run with QEMU:
   qemu-system-x86_64 thisarios.img

Welcome screen 

![Screenshot from 2025-06-24 14-45-20](https://github.com/user-attachments/assets/03b4eef7-d4d0-42a6-b2bb-ae5ef610d8d0)

Help screen 

![Screenshot from 2025-06-24 14-47-34](https://github.com/user-attachments/assets/e76092f3-ef56-4e21-be2a-a2307efbd0ba)

Info screen

![Screenshot from 2025-06-24 14-47-50](https://github.com/user-attachments/assets/47092d0d-7ec2-4718-85c2-1a07f54e4737)

Clear screen

![Screenshot from 2025-06-24 14-48-20](https://github.com/user-attachments/assets/4b890840-6666-4493-b80c-bfc69c3d5cac)
