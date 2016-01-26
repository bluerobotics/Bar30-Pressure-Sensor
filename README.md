# Bar30 Pressure Sensor

Arduino software library is available [here](http://github.com/bluerobotics/BlueRobotics_MS5837_Library/).

The schematic and board layout are designed in EagleCAD.

# Hardware

## Description

The Bar30 pressure sensor is a high-pressure, high-resolution pressure sensor that is sealed from the water and ready to install in a watertight enclosure. With 0.2 bar resolution, it has an amazing depth measurement resolution of 2mm in the water column!

The sensor is the Measurement Specialties MS5837-30BA, which can measure up to 30 bar (300m depth) and communicates over I2C. It comes standard with a 4-pin DF13 connector and compatible with most DroneCode compatible boards including the APM2.6, PixHawk, and others.

## Features

* Measure up to 300m water depth with 2mm resolution
* Reverse polarity protection
* Standard DF13 connector for connection to DroneCode boards such as APM, PixHawk, Navio2, etc.
* Sealed in a bulkhead penetrator for easy installation into any 10mm hole

## Compatibility

The Bar30 sensor is compatible with any device with 3.3V I<sup>2</sup>C logic. When using with a 5V device, such as an Arduino Uno, it is necessary to use a logic level converter.

##Configuration

--

##Ratings

**Electrical:**

| **Item** | **Condition** | **Value** |
| -------------: | :---------: | --- |
| Supply Voltage| - | 2.5-5.5 volts |
| I<sup>2</sup>C Logic Voltage | - | 2.5-3.6 volts |
| Peak Current   | - | 1.25 mA   |

**Pressure:**

| **Item** | **Condition** | **Value** |
| -------------: | :---------: | --- |
| Maximum Mechanical Pressure | - | 50 bar |
|Operating Pressure| - |0-30 bar [up to 1000 ft (300 m) in water]|
|Absolute Accuracy  (0-40&deg;C) | From 0-6 bar | +/- 50 mbar 	(51 cm in freshwater)		 |
|  				   | From 0-20 bar | +/- 100 mbar (102 cm in freshwater)			 |
|				   | From 0-30 bar | +/- 200 mbar (204 cm in freshwater)    	 |
|Absolute Accuracy (-25-85&deg;C)| From 0-6 bar | +/- 100 mbar 	(102 cm in freshwater)		 |
|  				   | From 0-20 bar | +/- 200 mbar (204 cm in freshwater)			 |
|				   | From 0-30 bar | +/- 400 mbar (408 cm in freshwater)     	 |

**Temperature:**

| **Item** | **Condition** | **Value** |
| -------------: | :---------: | --- |
| Operating Temperature | - | -20 to +85&deg;C |
| Storage Temperature | - | -40 to +85&deg;C                        |
| Absolute Accuracy   | From 0-10 bar at 0-60&deg;C | +/- 1.5&deg;C      |
|                     | From 0-30 bar at -20-85&deg;C |  +/- 4.0&deg;C   |

**Physical:**

| **Item** | **Value** |
| -------------: | ------------- |
| Wire Colors | Green - I<sup>2</sup>C Clock (SCL) |
|             | White - I<sup>2</sup>C Data (SDA)  |
|             | Red - Positive (2.5-5.5V) |
|             | Black - Ground          |
| Overall Length | 37 mm |
| Thread Size    | M10x1.5 20 mm threaded |
| Recommended Through Hole Size | 10-11 mm |
| Wrench Flats | 16 mm |

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

0.2 - Minor layout changes (marked with rev5)
