# NAH

A program that prevents you from typing the word "yeah" by closing the window you currently have active.

## Requirements
- Only runs on linux
- Install `xdotool` with your system's package manager

## Installation
Simply install with these 4 commands
```
git clone https://github.com/Linkioli/NAH.git
cd NAH
chmod +x nah
sudo cp nah /usr/local/bin
```

Nah requires root permissions to run (`sudo nah`). It is recommended that you have nah run in the background on startup simply add `sudo nah &` to whatever startup script you have.
