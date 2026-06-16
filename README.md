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
|Designator                                           |Component Name / Description  |Package     |Value / Spec            |Qty|Unit Price (USD)|Total (USD)|Primary Supplier|Part Number / Source Link                                                                                                                                                                                              |
|-----------------------------------------------------|------------------------------|------------|------------------------|---|----------------|-----------|----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|C1, C2                                               |Multilayer Ceramic Capacitor  |0805        |22pF                    |2  |0.4600          |$0.92      |LCSC            |https://www.lcsc.com/product-detail/C1804.html?s_z=n_q_CL21C220JBANNNC&lcsc_vid=FVBdVAJfRgcKUwcCQlVdBFQETlgIUlMAFFFcVAYEEVgxVlNeRlRXVVxWQVFdXzsOAxUeFF5JWBYZEEoKFBINSQcJGk4eFQsCAgIaSgADAwAHC0slQFVcU1NVTk8GEwkK       |
|C3                                                   |Multilayer Ceramic Capacitor  |0805        |1uF                     |1  |0.9400          |$0.94      |LCSC            |https://www.lcsc.com/product-detail/C28323.html?s_z=s_p_CL21B105KBFNNNE&lcsc_vid=FVBdVAJfRgcKUwcCQlVdBFQETlgIUlMAFFFcVAYEEVgxVlNeRlRXVVxQQVlbVjsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D                                |
|C10                                                  |Multilayer Ceramic Capacitor  |0805        |4.7uF                   |1  |0.4300          |$0.43      |LCSC            |https://www.lcsc.com/product-detail/C1779.html?s_z=s_p_CL21A475KAQNNNE&lcsc_vid=FVBdVAJfRgcKUwcCQlVdBFQETlgIUlMAFFFcVAYEEVgxVlNeRlRXVFVRT1lXUDsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D                                 |
|C11,C12,C13,C14,C15,C16,C17,C19,C20,C4,C5,C6,C7,C8,C9|Multilayer Ceramic Capacitor  |0805        |100nF                   |15 |0.0687          |$1.03      |LCSC            |https://www.lcsc.com/product-detail/C49678.html?s_z=n_q_CC0805KRX7R9BB104&lcsc_vid=FVBdVAJfRgcKUwcCQlVdBFQETlgIUlMAFFFcVAYEEVgxVlNeRlRXVFdQT1ZaUzsOAxUeFF5JWBYZEEoKFBINSQcJGk4eFQsCAgIaSgADAwAHC0slRlZZXkoOAwwC        |
|R1, R2, R5, R6                                       |Thick Film Chip Resistor      |0805        |100 kΩ                  |4  |0.0825          |$0.33      |LCSC            |https://www.lcsc.com/product-detail/C149504.html?s_z=s_p_0805W8F1003T5E&lcsc_vid=FVBdVAJfRgcKUwcCQlVdBFQETlgIUlMAFFFcVAYEEVgxVlNeRlRXVFFVT1deXjsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D                                |
|R4                                                   |Thick Film Chip Resistor      |0805        |680 Ω                   |1  |0.2200          |$0.22      |LCSC            |https://www.lcsc.com/product-detail/C17798.html?s_z=n_q_0805W8F6800T5E&lcsc_vid=FVBdVAJfRgcKUwcCQlVdBFQETlgIUlMAFFFcVAYEEVgxVlNeRlRXVFJVQ1BWVTsOAxUeFF5JWBYZEEoKFBINSQcJGk4eFQsCAgIaSgADAwAHC0slRlZZXlxIHxUDCw%3D%3D   |
|R7, R8                                               |Thick Film Chip Resistor      |0805        |330 Ω                   |2  |0.1400          |$0.28      |LCSC            |https://www.lcsc.com/product-detail/C17630.html?s_z=s_p_0805W8F3300T5E&lcsc_vid=FVBdVAJfRgcKUwcCQlVdBFQETlgIUlMAFFFcVAYEEVgxVlNeRlRXVFJeQlZXVjsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D                                 |
|R10, R23                                             |Thick Film Chip Resistor      |0805        |5.1 kΩ                  |2  |0.1400          |$0.28      |LCSC            |https://www.lcsc.com/product-detail/C27834.html?s_z=n_q_0805W8F5101T5E&lcsc_vid=FVBdVAJfRgcKUwcCQlVdBFQETlgIUlMAFFFcVAYEEVgxVlNeRlRXVFNXT1FeUDsOAxUeFF5JWBYZEEoKFBINSQcJGk4eFQsCAgIaSgADAwAHC0slRlZYVFRIHxUDCw%3D%3D   |
|R11-R20                                              |Thick Film Chip Resistor      |0805        |10 kΩ                   |14 |0.0250          |$0.35      |LCSC            |https://www.lcsc.com/product-detail/C17414.html?s_z=s_p_0805W8F1002T5E&lcsc_vid=FVBdVAJfRgcKUwcCQlVdBFQETlgIUlMAFFFcVAYEEVgxVlNeRlRXVFNfRFlXUjsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D                                 |
|D1, D2                                               |Surface Mount Indicator LED   |0805        |Standard Red/Green      |2  |0.3350          |$0.67      |LCSC            |https://www.lcsc.com/product-detail/C84256.html?s_z=s_p_NCD0805R1                                                                                                                                                      |
|SW1                                                  |SMT Tactile Push Button       |3.9x2.9mm   |1.6N / 2.0mm Height     |1  |2.2100          |$2.21      |LCSC            |https://www.lcsc.com/product-detail/C495942.html?s_z=n_q_MPTFP2-V-T%252FR&lcsc_vid=FVBdVAJfRgcKUwcCQlVdBFQETlgIUlMAFFFcVAYEEVgxVlNeRlRXVFxeRlRbUjsOAxUeFF5JWBYZEEoKFBINSQcJGk4eFQsCAgIaSgADAwAHC0slT1VcUlJIHxUDCw%3D%3D|
|CARD1, CARD2                                         |Hinged MicroSD Card Slot      |SMT         |SD-106M Hinged          |2  |0.5200          |$1.04      |LCSC            |https://www.lcsc.com/product-detail/C266603.html?s_z=s_p_SD-106M&lcsc_vid=FVBdVAJfRgcKUwcCQlVdBFQETlgIUlMAFFFcVAYEEVgxVlNeRlRXVF1VQFZXVDsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D                                       |
|GL850G                                               |USB 2.0 Hub Controller IC     |SSOP-28     |GL850G-HHY22            |1  |0.5500          |$0.55      |LCSC            |https://www.lcsc.com/product-detail/C136617.html?s_z=n_q_GL850G-HHY22&lcsc_vid=FVBdVAJfRgcKUwcCQlVdBFQETlgIUlMAFFFcVAYEEVgxVlNeRlRXVF1eTllbXzsOAxUeFF5JWBYZEEoKFBINSQcJGk4eFQsCAgIaSgADAwAHC0slRVdYUVRVWQkaCgg%3D      |
|IC3, IC4                                             |USB SD Card Reader Controller |SOP-16      |GL823K-HCY04            |2  |0.4550          |$0.91      |LCSC            |https://www.lcsc.com/product-detail/C284879.html?s_z=n_q_GL823K-HCY04&lcsc_vid=FVBdVAJfRgcKUwcCQlVdBFQETlgIUlMAFFFcVAYEEVgxVlNeRlRXU1RSR1JZVzsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktfQ1hADxALGw%3D%3D                |
|U1, U2                                               |TVS Diode ESD Protection Array|SOT-23-6    |SRV05-4 (Low Cap)       |2  |0.2550          |$0.51      |LCSC            |https://www.lcsc.com/product-detail/C2836319.html?s_z=n_q_x_SRV05-4&lcsc_vid=FVBdVAJfRgcKUwcCQlVdBFQETlgIUlMAFFFcVAYEEVgxVlNeRlRXU1RRRFlfVTsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktfQ1hADxALGw%3D%3D                  |
|USB1, USB2                                           |USB Type-A Receptacle         |Through-Hole|Right Angle / 90° Female|2  |0.2450          |$0.49      |LCSC            |https://www.lcsc.com/product-detail/C456018.html?s_z=n_q_p_AF%252090%2520WJDG&lcsc_vid=FVBdVAJfRgcKUwcCQlVdBFQETlgIUlMAFFFcVAYEEVgxVlNeRlRXU1VURlNYUDsOAxUeFF5JWBYZEEoKFBINSQcJGk4eFQsCAgIaSgADAwAHC0slRVldUVdXTk8GEwkK|
|USB3                                                 |USB Type-C Receptacle         |SMT+TH      |16-Pin 2MD Type-C       |1  |1.4100          |$1.41      |LCSC            |https://www.lcsc.com/product-detail/C2765186.html?s_z=n_q_TYPE-C%252016PIN%25202MD(073)&lcsc_vid=FVBdVAJfRgcKUwcCQlVdBFQETlgIUlMAFFFcVAYEEVgxVlNeRlRXU1VQRFZaUDsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D                |
|Y2                                                   |Quartz Resonator Crystal      |3225 SMT    |26.2982 MHz / 4-Pad     |1  |0.1400          |$0.14      |LCSC            |https://www.lcsc.com/product-detail/C2981681.html?s_z=n_q_3225-26.2982-22-10-10%252FA                                                                                                                                  |
|PCB                                                  |Custom 2-Layer Circuit Board  |100x80mm    |FR-4 / 1.6mm Thickness  |5  |0.7000          |$3.50      |JLCPCB          |https://www.jlcpcb.com                                                                                                                                                                                                 |
|                                                     |                              |            |                        |   |                |           |                |                                                                                                                                                                                                                       |
|                                                     |                              |            |                        |   |                |$16.21     |                |                                                                                                                                                                                                                       |



## Build & Assembly
(I may or may not be larping, I've never soldered anything this miniscule before so bare with me and my limited theory knowledge)

### Required Tools
- Soldering iron
- Solder
- Tweezers
- Tacky Flux
- IPA & ESD Brush

### Assmebly  Steps

#### Solder on the microchips (the lowest profile ones), which include the GL850G, GL823K, and the ESD Protection Diodes.
1. Apply a thin layer of tacky flux to the PCB pads
2. Align and place the chip
3. Tack down one corner pin with a tiny dab of solder
4. Apply flux across all pins, and solder everything together

#### Solder on any passives, including resistors, caps, crystals, and LEDs
1. Use the two-pad SMT technique, applying a small dab of solder on one pad
2. Slide the component into the solder using tweezers
3. Solder the remaining pad

#### Solder on the electromechanical components, which include the tactile switch and SD card slots
1. Just do it? Haha?

#### Solder on the final, highest profile components, including the USB IO connectors
1. Put the connector into the holes on the PCB, and solder from the bottom
2. Use a magnifying glass for the USB-C, the 16 pins are going to be hell.

#### If you can afford PCBA, good for you. Ignore everything I just said >:(
