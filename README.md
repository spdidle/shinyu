# A-Side 🎼

<p align="center"><img width="527" height="749" alt="image" src="https://github.com/user-attachments/assets/4056605c-ca39-4327-acf0-5b355fbc1c73" /></p>

## What is this?

A-Side is a cassette tape inspired hub to connect full size SD cards among other things to my laptop. I own several cameras but it's not convenient at all to find my dongle and connect it. So why not use a cute form to easily see your pictures!

## Why did I make this?

I love cassette tapes and cameras. That's it!

Loving cameras mean that every time I need to view my photos, upload my photos, anything to do with my photos, it's such a hassle! Grabbing my SD card reader, then my hard drive, sometimes another dongle... Anyways, it's just way too much work. So I decided to make my own SD card dongle-esque thing, with 2 USB-A ports to facilitate any connecting of hard drives, and 2 SD card slots to maximize the photo goodness. When I don't need to fiddle with photos, it can also act as a normal USB hub, allowing me to plug in keyboard or mice into my laptop.

## Features

- **2 USB-A ports** for portable hard drives, keyboards, or mice
- **2 Full-Size SD Card slots** for photos!
- **USB-C port** because nowadays, everything seems to be USB-C...

## How does it work?

Very self explanitory! Grab your favourite USB-C to USB-C cable, plug one end into your computer, the other into the hub, and voila! You are now able to plug whatever you want into this cute little cassette tape.

## Design

Designed in KiCad, schematic and board files are in this repo:
<p align="center">
  <img width="1148" height="629" alt="image" src="https://github.com/user-attachments/assets/74b2533f-39b1-4c1d-be49-aa3d456b8695" />
  <img width="876" height="603" alt="image" src="https://github.com/user-attachments/assets/4cb433de-6a21-4b39-94a4-0f4ddf408139" />
  <img width="725" height="519" alt="image" src="https://github.com/user-attachments/assets/88688cb4-c530-400f-8f30-3ab6f7af21ce" />
<img width="768" height="494" alt="image" src="https://github.com/user-attachments/assets/7f13de89-52ca-41c1-9f50-0c34a3be54a8" />

</p>

Case was designed (+ rendered) in Fusion360:
<p align="center">
<img width="993" height="597" alt="image" src="https://github.com/user-attachments/assets/263e9e8e-2c5c-4518-8fe0-a2a3a9a8aaf9" />
</p>

## BOM (Bill Of Materials)

## Build & Assembly

### Required Tools
- Soldering iron
- Solder
- Tweezers
- Small screwdriver for M3 screws
- Computer with USB-C port
- 3D printer

### Assmebly  Steps
1. Solder all the THT diodes onto the PCB
2. Solder the LEDs to the PCB. I rotated the direction of the bottom row by accident so refer to the PCB layout if the orientation is confusing at all
3. Solder the microcontroller, OLED display, and switches to the PCB
4. To assemble the case, place the PCB into the bottom shell
5. Attach it to the top shell
6. Secure with M3 screws.
7. Since this build uses the RP2040, I will use QMK to install firmware
8. Plug in the RP2040 to your computer with a USB cable while holding BOOT
9. Flash the firmware using : "qmk flash -kb pommepad -km default"
10. Modify keymapping in firmware, and set the 6 keys to your desired shortcuts
11. Test your OLED (check I2C, SDA/SCL pins, etc)
12. Once everything work
