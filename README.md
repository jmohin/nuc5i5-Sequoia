
<img width="1440" height="810" alt="Screenshot 2026-02-03 at 6 04 08 PM" src="https://github.com/user-attachments/assets/18144462-1039-4d14-9965-324cd113f58e" />

# Intel NUC (NUC5i5) running Sequoia 15.7.3
Fully working OSX Sequoia using OpenCore, OpenCoreLegacyPatcher

## My setup
https://www.intel.com/content/www/us/en/products/sku/83255/intel-nuc-kit-nuc5i5ryh/specifications.html

Nuc5i5RYH with: 
 - OSX Sequoia installed to a 512GB SSD in the  m.2 slot
 - Windows 10 installed to a HDD in the SATA port
 - 16GB RAM

## How I did it
Followed this guide for the install:
 - https://github.com/5T33Z0/OCLP4Hackintosh/blob/main/Guides/Haswell-Broadwell.md
Note that the top guide uses "stock" OCLP and the bottom guide uses a fork called OCLP-mod; only OCLP-mod works for Wifi/BT

And I followed this guide for Wifi/BT:
 - https://github.com/5T33Z0/OCLP4Hackintosh/blob/main/Enable_Features/AirportItllwm_Sequoia.md

## What works
 - Sleep/wake
  - Full CPU PM
  - Native Intel Wifi
 - Native Intel Bluetooth
 - Full graphics acceleration, with dual displays
 - Native Intel Ethernet
 - Native Intel HD Audio over HDMI/miniDP
 - Headphone audio port
 - USB2/3

## What doesn't work
 - SD Card reader
 - OSX Tahoe (have tried and failed!)
