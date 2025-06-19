# rp2350-flight-controller
This is my design for a simple quadcopter flight controller board using the raspberry pi rp2350 microcontroller at the center. 

<p align="center">
<img src="https://github.com/user-attachments/assets/f8417588-fadb-41e4-a209-7a155e58ef71" alt="Feature" width="720"/>
</p>

### [Schematic](Schematic.pdf)

<p align="center">
<img src="https://github.com/user-attachments/assets/03c6fbb7-4cb7-4f5e-bc76-9c4ed9c33439" alt="Schematic" width="360"/>
<img src="https://github.com/user-attachments/assets/deb6fa9c-44d3-4bd1-9d9a-508375fcaa13" alt="Schematic2" width="360"/>
</p>

### Board preview

<p align="center">
<img src="https://github.com/user-attachments/assets/64967ffd-b356-4d3e-b8b2-37f0c5186aae" alt="CloseUpFront" width="360"/>
<img src="https://github.com/user-attachments/assets/73288ab0-88da-4977-90d7-d28c7de68f6a" alt="CloseUpBack" width="360"/>
</p>

### Main Features

- Raspberry pi RP2350 microcontroller
- ICM-42605 IMU (SPI1)
- BMP280 Barometer (SPI1)
- LSM303DLHC Magnetometer (I2C)
- NRF24 GT24 Mini 2.4Ghz radio module (SPI0)
- Micro SD card reader (SPI0)

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

