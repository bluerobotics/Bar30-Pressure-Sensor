# Bar30 Pressure Sensor

Arduino software library is available [here](http://github.com/bluerobotics/BlueRobotics_MS5837_Library/).

The schematic and board layout are designed in EagleCAD.

# Hardware

## Description

The Bar30 pressure sensor is a high-pressure, high-resolution pressure sensor that is sealed from the water and ready to install in a watertight enclosure. With 0.2 bar resolution, it has an amazing depth measurement resolution of 2mm in the water column!

The sensor is the Measurement Specialties MS5837-30BA, which can measure up to 30 bar (300m depth) and communicates over I2C. We’ve added level switching circuitry so that it can operate on both 3.3V and 5V I2C lines. It comes standard with a 4-pin DF13 connector and compatible with most DroneCode compatible boards including the APM2.6, PixHawk, and others.

## Features

* Measure up to 300m water depth with 2mm resolution
* Reverse polarity protection
* 5V tolerant circuitry
* Standard DF13 connector for connection to DroneCode boards such as APM, PixHawk, Navio2, etc.

## Compatibility

##Configuration

[Image with arrows]

##Ratings

| Value                              | Minimum | Nominal | Maximum | Unit    |
|-----------------------------------:|:-------:|:-------:|:-------:|:--------|
| Supply Voltage                     | 2       | 3.3     | 5.5     | V       |
| I<sup>2</sup>C (SCL & SDA)         | 2       | 3.3     | 5.5     | V       |
| Current Consumption                |         |         | 2       | mA      |
| Pressure Measurement (sensor)      |         |         | 30      | Bar     |
| Maximum Device Pressure            |         |         | 50      | Bar     |

##Example Setups

Examples TBD

##Physical Specifications

* Bulkhead hole size: 10-10.5mm
* Wire length: 11" (280mm)

##License

The Bar30 Pressure Sensor Hardware Design is released under the MIT License.

##Revision History

0.0 - Under development
0.1 - First production version (marked with rev4)