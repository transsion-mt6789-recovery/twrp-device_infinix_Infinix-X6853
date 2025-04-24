## Infinix NOTE 50 Pro 4G (_X6853_)
## TWRP / OrangeFox device tree

## Device specifications

Device                  | Infinix NOTE 50 Pro 4G
-----------------------:|:-----------------------------------------
SoC                     | Mediatek Helio G100 Ultimate (6 nm)
CPU                     | Octa-core (2x2.2 GHz Cortex-A76 & 6x2.0 GHz Cortex-A55)
GPU                     | Mali-G57 MC2
Memory                  | 8/12 GB RAM
Storage                 | 256 GB (UFS 2.2)
MicroSD                 | None
Shipped Android Version | 15.0
Battery                 | Non-removable 5200 mAh
Display                 | 1080 x 2436 pixels (~393 ppi density), 6.78 inches
Camera                  | 50 MP (wide), 8 MP (ultrawide); 32 MP (front, wide)

## Device picture

![ Xiaomi Redmi Note 13 Pro 5G / POCO X6 5G ](https://fdn2.gsmarena.com/vv/pics/infinix/infinix-note50-pro-2.jpg "Infinix NOTE 50 Pro 4G")

## Features

Works:

- [X] ADB
- [X] Decryption
- [X] Display
- [X] Fasbootd
- [X] Flashing
- [X] MTP
- [X] Sideload
- [ ] USB OTG
- [ ] Vibrator

## Building

_Lunch_ command :

```
lunch twrp_X6853-eng && mka adbd vendorbootimage
```

### Copyright
 ```
  /*
  *  Copyright (C) 2025 Transsion mt6789 Custom Recovery Project
  *
  * This program is free software: you can redistribute it and/or modify
  * it under the terms of the GNU General Public License as published by
  * the Free Software Foundation, either version 3 of the License, or
  * (at your option) any later version.
  *
  * This program is distributed in the hope that it will be useful,
  * but WITHOUT ANY WARRANTY; without even the implied warranty of
  * MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
  * GNU General Public License for more details.
  *
  * You should have received a copy of the GNU General Public License
  * along with this program.  If not, see <http://www.gnu.org/licenses/>.
  *
  */
  ```
