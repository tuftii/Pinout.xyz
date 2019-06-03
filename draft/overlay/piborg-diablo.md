<!--
---
name: Diablo V2
class: board
type: Motor
formfactor: Custom
manufacturer: PiBorg
description: An add-on board for the Raspberry Pi
url: https://www.piborg.org/diablo
github: https://github.com/piborg/diablo
buy: http://www.piborg.org/diablo
image: 'piborg-diablo.png'
pincount: 6
eeprom: no
power:
  '1':
  '2':
  '4':
ground:
  '6':
pin:
  '3':
    mode: i2c
  '5':
    mode: i2c
-->
#Diablo V2

The Diablo V2 dual H-bridge motor controller from PiBorg is capable of running large motors and steppers up to 55A per channel from power sources from 7V to 36V. Speed control comes from PWM and the boards are individually addressable via I2C allowing for other I2C boards to be used on other addresses.

##Features
- On-board 5V regulator powers the Raspberry Pi
- Runs from any battery pack or power supply from 7V to 36V
- Proper 55A output per motor connection
- Speed control forwards and reverse via PWM
- Controls 2x DC Motors or 4, 5 or 6 wire stepper motors
- Uses I2C SCK/SDA and 3.3V/GND pins for communications allowing interfacing to the Raspberry Pi, Arduino, Beagle Bone, Microchip pic and many others.
- Stackable! Plug in more boards to control up to 200 motors!
- Overheat protection, under voltage lockout, and short circuit protection.
- Diablo code library available on [GitHub](https://www.github.com/piborg/diablo).
- Worked hardware and software examples available on the [PiBorg blog](https://www.piborg.org/blog/build/diablo-build).
