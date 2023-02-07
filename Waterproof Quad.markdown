---
layout: "page"
title: Watertight Quad
permalink: /WatertightQuad/
vimeoId: 796156536
---

## Demonstration

{% include vimeoPlayer.html id=page.vimeoId %}


## Build Pics

![Alt Text]({{ "/assets/1.jpg" | relative_url }})
![Alt Text]({{ "/assets/2.jpg" | relative_url }})
![Alt Text]({{ "/assets/3.jpg" | relative_url }})
![Alt Text]({{ "/assets/5.jpg" | relative_url }})
![Alt Text]({{ "/assets/7.jpg" | relative_url }})
![Alt Text]({{ "/assets/4.jpg" | relative_url }})

## STL Files

Provided free of charge, is STL files for all 3D printed parts pictured. License = MIT
[Link to Github repo with STL files](https://github.com/UltiFix/source_one_V5)

## BOM

(Referral Links used)

1. [832TC Thermally Conductive Epoxy from MG Chemicals](https://amzn.to/3JF7ZQF)
2. [HGLRC Zeus VTX](https://amzn.to/3JO4ck9)
3. [Caddx Ratel 2](https://amzn.to/3YnFOtw)
4. EMAX ECOII 2306 1900kv
5. JHEMCU GHF405 PRO BLHELI_S 45A 3-6S AIO
6. [Crossfire Nano RX](https://amzn.to/3laai3R)
7. TBS Source One V5 Frame
8. [USB Micro B Breakout Board DIY](https://amzn.to/3x1h8vh)
9. [USB Micro B Male Plug DIY](https://amzn.to/3RA7Dwx)

## Build

# General Build Notes

Each component was placed into its corresponding mold, hot glue was applied near cable exits to keep epoxy in, and each component was tested for functionality. Next, 832TC epoxy was mixed and put into the mold. I let cure for ~app 24Hr. Its critical when building you take pictures/notes showing which wire colors correspond to what signals for CAM, VTX, and RX. If you ever need to replace any of those components later you will be glad you took notes.

I used a cooking scale to mix epoxy by WEIGHT, not volume to ensure accuracy. Note epoxy mixing ratio is 1/1 by VOLUME but 1.1/1 by WEIGHT. See TDS for 832TC.

# USB Notes

USB port was broken out to a daugter board for ease of epoxy (getting the USB up off the board). Take a male Micro B USB port and solder wires on USB TX RX and GND (NOT 5V). Then solder to correct location on Micro B breakout board. THIS MEANS QUAD MUST HAVE BATTERY CONNECTED AND USB PLUGGED INTO PC TO CONNECT TO BETAFLIGHT. REMOVE PROPS!!!!

# Caddx Ratel V2 Notes

Camera Lens Watertight, thus only need to epoxy to edge of lens
![Alt Text]({{ "/assets/6.jpg" | relative_url }})

# AIO Mold Notes

M3 Threaded Inserts was heatstaked into plastic. You will want M3 18mm bolt length (not including head) to go through carbon and into threaded insert.

# Soldering Notes

Had issue with connecting Crossfire receiver to RX1 and TX1 on the AIO board used. Did not function. Switched to RX3 and TX3 worked no problem.

# Software Notes

With crossfire receiver hooked up, when I used impulse RC driver fixer to put FC into DUF mode for firmware update it crashed. I had to unsolder power wire to crossfire receiver to get impulse RC driver fixer working.

# Comments

All parts/compenents used in this build where purchased. Open to sponsor.
