# Portable Computer
My attempt at designing the hardware and software for my own personal portable computer.

## Day 0
First step is obviously figuring out the components I want to use and planning the physical hardware. I looked at a number of microcontrollers and the most appealing to me is the [ESP32-S31](https://www.espressif.com/en/products/socs/esp32-s31). It's fast out of the box (320MHz); with 2 32-bit cores using the RISC-V instruction set, and contains so many features built in, including WiFi and Bluetooth support. It's also relatively cheap, at just under [$9AU on AliExpress](https://www.aliexpress.com/item/1005012434557649.html).

I also found a nice large [(7 inch, 800x400) touchsreen display](https://littlebirdelectronics.com.au/products/7-0-40-pin-tft-display-800x480-with-touchscreen) that I decided I would like to try and implement, although this would be the most expensive part of this whole project.

From here I though about what else I would want/need. MicroSD for persistent storage; USB-A and USB-C ports for peripherals like a keyboard or mouse; a battery so the computer is (somewhat, depending on the final size) portable.

I didn't pick out any specific parts beyond the chip and display at this point, most of these are relatively generic and my plan is ultimately to have as much as possible printed via [PCBA at JLCPCB](https://jlcpcb.com/capabilities/pcb-assembly-capabilities).

With all this in mind, I opened up KiCad and created an empty project.

