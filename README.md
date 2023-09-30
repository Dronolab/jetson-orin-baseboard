# Dronolab Jetson Orin Carrier Board

Modified Version of [Jetson Orin Baseboard](https://github.com/antmicro/jetson-orin-baseboard) by [Antmicro](https://www.antmicro.com)

[![image](https://img.shields.io/badge/View%20on-Antmicro%20Open%20Source%20Portal-332d37?style=flat-square)](https://opensource.antmicro.com/projects/jetson-orin-baseboard)

![](img/jetson-orin-baseboard-photo.png)

## Overview

This project contains hardware design files for a carrier board supporting NVIDIA Jetson Orin Nano and Jetson Orin NX System on Modules (SoMs). The board break-routes the typical IO interfaces from the SoM. Additionally, it exposes an expansion connector also known as the Payload Area Connector (PAC) that allows for an electrical connection for monitoring and control of any payload.

The design files were preapared in KiCad 7.x.

## Quick Start

Install Kicad's Latest Stable Release and Github Desktop. Clone this project using Github Desktop and make sure to set the option to contributing to the Dronolab Repository (not the Antmicro one). To make a change, create your own branch that describes the change being made. Once you are done, commit and push your changes. Finally, merge your branch to main and wait for approval.

## Key features

* DC Power connector
* MIPI CSI-2 interfaces
* USB-C 10 Gbps with DP Alternate Mode
* USB-C 10 Gbps + USB-C Uart
* M.2 key M for SSD
* 1Gb Ethernet
* Custom Payload Area Connector (PAC)
* RTC battery backup

## Project structure

The main directory contains KiCad PCB project files, a LICENSE, and a README.
The remaining files are stored in the following directories:

* `lib` - contains the component libraries
* `img` - contains graphics for this README
* `doc` - contains schematics in pdf form

## Block diagram

![Diagram](doc/jetson-orin-baseboard-diagram.png)

## Licensing

This project is published under the [Apache-2.0](LICENSE) license.

