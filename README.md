# rp2350-flight-controller
This is my design for a prototype quadcopter flight controller board using the rp2350 as the main mcu. 

Here is the [Schematic](Schematic.pdf) and also some renders of the finished board:

<img src="https://github.com/user-attachments/assets/03747724-e6eb-4a25-9e6e-05ac3ccbb617" alt="CloseUpFront2" width="400"/>

<img src="https://github.com/user-attachments/assets/1bfb95ba-25b7-45d9-9898-d99bdaf8a12e" alt="CloseUpBack2" width="400"/>

### Main Features

- Raspberry pi RP2350 microcontroller
- ICM-42605 Acc-Gyro (SPI1)
- BMP280 Barometer (SPI1)
- LSM303DLHC Magnetometer (I2C)
- NRF24 GT24 Mini (SPI0)
- SD card reader (SPI0)

### Extra features
- USB-C for power and data transfer
- External 5V power supply input
- Onboard RT6150B 3V3 buck converter
- Battery voltage divider input
- 2x External load 5V switching via mosfets
- GPS module interface (I2C and Serial)
- 3V3 and 5V power output
- 2x onboard Leds
- IMU heating resistors
- Reset and Bootsel buttons

