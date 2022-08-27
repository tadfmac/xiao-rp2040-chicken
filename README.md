# xiao-rp2040-chicken

A crazy midi controller make with Seeed Studio's [XIAO RP2040](https://www.seeedstudio.com/XIAO-RP2040-v1-0-p-5026.html)  and showting chicken!

![top](./topview.png)
![bottom](./bottomview.png)

### schematics

![schematics](./schematics.png)

### parts list

- [XIAO RP2040](https://www.seeedstudio.com/XIAO-RP2040-v1-0-p-5026.html) x 1
- [Mic board](https://akizukidenshi.com/catalog/g/gM-08940/) x 1
- [Vibration sensor](https://akizukidenshi.com/catalog/g/gP-15375/) x 1
- 2.54mm pitch lowprofile pinheader (1x7) x 2
- 0805 10kΩ resistor x 1
- 2.54mm pitch L-angle pinsocket (1x4) x 1
- showting chicken (**Important! the showting checken must 40cm or larger! it maybe cannot insert to smaller it.**) [example (must chose '40cm')](https://ja.aliexpress.com/item/32899623947.html?spm=a2g0o.productlist.0.0.47ca4900kHPyQw&algo_pvid=134d390f-c75f-4f2b-b0bf-b81694eb1b31&algo_exp_id=134d390f-c75f-4f2b-b0bf-b81694eb1b31-18&pdp_ext_f=%7B"sku_id"%3A"65853772185"%7D&pdp_npi=2%40dis%21JPY%21656.0%21525.0%21%21%21%21%21%402103250d16615813887934542e5813%2165853772185%21sea&curPageLogUid=4S6EgBV8VM1s) 

### How to Making?

1. Read the [mic board instructions (japanese)](https://akizukidenshi.com/download/ds/akizuki/AE-SPU0414.pdf) and set the mic gain on the mic board to 20db. Solder to the jumper part of the board.
2. Solder the parts while looking at the schematic. For thinness, please use low profile pin headers to connect the board and XIAO RP2040.
3. Connect the USB cable to XIAO RP2040.
4. Insert the board with soldered components through the mouth of the chicken. It's hard to insert, but do your best!

### XIAO RP2040 Programming

1. Use Arduino. First, have the [Arduino IDE](https://www.arduino.cc/en/software) installed on your PC.
2. Next, install the software for XIAO RP2040 on Arduino by [Seeed Studio's instructions (Seeed Studio XIAO RP2040 with Arduino)](https://wiki.seeedstudio.com/XIAO-RP2040-with-Arduino/).
3. Finally, download [XIAO-RP2040-CHICKEN.ino](https://gist.github.com/tadfmac/8916deed75f60839810058b9485af5d4) and flash it from your Arduino IDE to your XIAO RP2040.
4. done! Let's Enjoy with connect through USB your PC and start your MIDI software.

### License

MIT

