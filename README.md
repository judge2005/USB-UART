# USB-UART
A USB to serial adapter specifically designed for programming the ESP01. It uses node-mcu style programming, so no fiddling with buttons is necessary - just change the reset method to 'node-mcu'.

It has enough power to run the ESP01 without the need for an additional power source.

It uses the Silicon Labs CP2102N, so it can detect the charge protocol supported by the USB port it is plugged in to. You will have to use the Silicon Labs Express Configurator to set that up.
