# CYW9P62S1-43012EVB-01 BSP

## Overview

The CYW9P62S1-43012EVB-01 Kit is a low-cost hardware platform that enables design and debug of the USI WP1-2019-C1 Module. USI WP1-2019-C1 is a System in Package (SiP) module that contains the MCU part, PSoC 62 MCU (CY8C6247FDI-D32) and the radio part CYW43012 ( WiFi + Bluetooth Combo Chip).
![](docs/html/board.png)

To use code from the BSP, simply include a reference to `cybsp.h`.

## Features

### Kit Features:

* BLE v5.0
* Serial memory interface
* Industry-leading CapSense

### Kit Contents:

* CYW9P62S1-43012EVB-01 evaluation board
* Quick Start Guide
* USB Type-A to Micro-B cable

## BSP Configuration

### Clock Configuration

| Clock    | Source    | Output Frequency |
|----------|-----------|------------------|
| CLK_HF0  | CLK_PATH0 | 100 MHz          |
| CLK_HF1  | CLK_PATH0 | 100 MHz          |
| CLK_HF2  | CLK_PATH0 | 50 MHz           |
| CLK_HF3  | CLK_PATH1 | 48 MHz           |

### Power Configuration

* System Active Power Mode: LP
* System Idle Power Mode: Deep Sleep
* VDDA Voltage: 3300 mV
* VDDD Voltage: 3300 mV

## API Reference Manual

The CYW9P62S1-43012EVB-01 Board Support Package provides a set of APIs to configure, initialize and use the board resources.

See the [BSP API Reference Manual][api] for the complete list of the provided interfaces.

## More information
* [CYW9P62S1-43012EVB-01 BSP API Reference Manual][api]
* [CYW9P62S1-43012EVB-01 Documentation](http://www.cypress.com/documentation/development-kitsboards/cyw9p62s1_43012evb_01)
* [Cypress Semiconductor](http://www.cypress.com)
* [Cypress Semiconductor GitHub](https://github.com/cypresssemiconductorco)
* [ModusToolbox](https://www.cypress.com/products/modustoolbox-software-environment)

[api]: https://cypresssemiconductorco.github.io/TARGET_CYW9P62S1-43012EVB-01/html/modules.html

---
© Cypress Semiconductor Corporation, 2019.