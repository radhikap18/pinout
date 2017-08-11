<!--
---
name: Grove Seeed Sensor Mezzanine
class: board
type: Mezzanine
description: Makes it simple and easy to connect sensors and devices to any 96Boards-compatible base board
url: https://www.96boards.org/product/sensors-mezzanine/
github: https://github.com/96boards/documentation/tree/master/mezzanine/sensors-mezzanine
buy: http://linaro.co/20n34bc
image: 'grove-seeed-sensor-mezzanine.jpg'
pincount: 40
eeprom: no
power:
  '35':
  '37':
ground:
  '1':
  '2':
  '39':
  '40':
pin:
  '15':
    mode: i2c
  '17':
    mode: i2c
  '19':
    mode: i2c
  '21':
    mode: i2c

-->


# Grove Seeed Sensor Mezzanine
The 96Boards Sensors Mezzanine adapter makes it simple and easy to connect sensors and devices to any 96Boards-compatible base board. With it you can connect your favourite Grove modules and Arduino compatible shields and interface to software running on the 96Boards baseboard. It provides everything you need to start experimenting and prototyping on the 96Boards platform.

On the board you will find sockets for 18 Grove modules, an Arduino-compatible shield socket, and two SPI headers. It also includes an ATMega328 microcontroller which can be programmed from the Arduino IDE and will run most Arduino UNO sketches unchanged. The shield connector and half of the Grove sockets are controlled by the microcontroller, while the remaining Grove sockets are controlled directly by the baseboard. This makes it a flexible prototyping platform which supports both direct control of devices from application software, and offload to a microcontroller. It also provides a USB-UART interface to access the base board’s serial console.

### Features (Mezzanine Board)
- Compatible with 96Boards CE and EE baseboards
- Integrated Arduino-compatible ATMEGA328 microcontroller
- Arduino UNO compatible expansion headers
- 9 Grove connectors for 96Boards IO (mixed 3.3V and 5V; all 5V tolerant): 5x GPIO, and 4x I2C
- 9 Grove connectors for ATMEGA328 IO (all 5V): 5x GPIO, 3x ADC, and 1x I2C
- 2 6-pin SPI headers
- MicroUSB interface to 96Boards console serial port
- 1 Power LED
- 3 user LEDs
- Reset button
- Power button

### Buy Now
- [SeeedStudio - Mezzanine Only](http://linaro.co/20n34bc)
- [SeeedStudio - Grove Starter Kit](http://linaro.co/1KnV9TA)

