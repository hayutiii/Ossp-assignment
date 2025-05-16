# OSSP Project – Lubuntu Installation & rename() System Call

## 🧩 Part A: Lubuntu Installation

Lubuntu is a lightweight, fast Linux distribution based on Ubuntu.  
I installed it in a virtual environment using VirtualBox by downloading the official ISO.  
The installation process included partitioning the disk, choosing system settings, and completing the setup.  
After installation, I removed the ISO and successfully booted into the Lubuntu desktop.

## 🔁 Part B: rename() System Call

The `rename()` system call is used in Linux to rename or move a file or directory.  
It takes two pathnames as arguments: the old and the new file names.  
If the new path exists, it will be overwritten (if allowed), and the operation is atomic.  
I wrote a C program and tested the system call in Lubuntu using the terminal and `gcc`.
