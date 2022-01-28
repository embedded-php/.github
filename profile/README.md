# Embedded PHP

This is an effort to get PHP to interact with sensors and displays in Linux-based Single-board computers, through
general-purpose input/output pins, SPI/I2C/UART protocols etc.

## Libraries

### Display

Interface with LCD and OLED matrix displays. [More details](https://github.com/embedded-php/display).

### Sensors

Interface with different types of sensors. [More details](https://github.com/embedded-php/sensors).

## Extensions

### GPIO

Interact with the general-purpose input/output pins. [More details](https://github.com/embedded-php/ext-gpio).

Main usage:
* Buttons
* Switches
* Lights

### I2C

Interact with external hardware using the I2C protocol. [More details](https://github.com/embedded-php/ext-i2c).

Main usage:
* Accelerometers
* Gyroscopes
* Compasses

### SPI

Interact with external hardware using the SPI protocol. [More details](https://github.com/embedded-php/ext-spi).

Main usage:
* Analog-to-digital
* Small displays

### UART

Interact with external hardware using the UART asynchronous serial communication protocol.
[More details](https://github.com/embedded-php/ext-uart).

Main usage:
* GPS Receivers
* Cellular modems
