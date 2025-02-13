# Dual Camera to GMSL Serializer CSI Adapter

Copyright (c) 2024-2025 [Antmicro](https://www.antmicro.com)

![Dual Camera to GMSL Serializer CSI Adapter visualization](./assets/previews/orthoB.png)

## Overview

This project contains open hardware design files for the Dual Camera to GMSL Serializer CSI Adapter.
The board is designed to accept 2 x MIPI CSI-2 signals from the [OV5640 Dual Camera Board](https://github.com/antmicro/ov5640-dual-camera-board) and output them to 2 x [GMSL Serializer Board](https://github.com/antmicro/gmsl-serializer).
The power distribution circuit is configured to draw power from the selected serializer board and supply it to the camera board.
The design files were prepared in KiCad 8.

### Project structure

The main directory contains KiCad PCB project files, a LICENSE, and a README.
The remaining files are stored in the following directories:

* ``img`` - contains graphics for this README
* ``doc`` - contains schematics in PDF format
* ``assets`` - contains visual assets for showcasing this design on [Open Hardware Portal](https://openhardware.antmicro.com) and [Antmicro Designer](https://designer.antmicro.com/welcome).

## Key features

* Input: 2 x 4-lane MIPI CSI-2 interface on a 50-pin  Dual Camera connector
* Output: 4-lane MIPI CSI-2 interface on a 2 x 50-pin  Dual Camera connector
* 2 x QWIIC connectors for seamless integration of additional I2C devices.

## Licensing

This project is published under the [Apache-2.0](LICENSE) license.
