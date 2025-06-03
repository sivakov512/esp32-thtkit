# ESP32 THT Development Kits
**Ultra-Compact Through-Hole Development Boards for ESP32**

[![SIVAKOV.TECH](https://img.shields.io/badge/designed%20by-SIVAKOV.TECH-black)](https://sivakov.tech)

This repository contains design files and documentation for ultra-compact, through-hole (THT) friendly development boards based on Espressif ESP32 microcontrollers. These boards are designed for easy integration into breadboard and other through-hole prototyping environments.

## Available Development Kits

| DevKit | Description | SoC | Features |
|--------|-------------|-----|----------|
| [ESP32-C3-THTKIT](esp32-c3-thtkit/) | Ultra-compact ESP32-C3 development board with THT headers | ESP32-C3FH4 | WiFi, Bluetooth 5 (LE), RISC-V single-core |
| [ESP32-H2-THTKIT](esp32-h2-thtkit/) | Ultra-compact ESP32-H2 development board with THT headers | ESP32-H2FH4 | 802.15.4 (Thread, Zigbee), Bluetooth 5 (LE), RISC-V single-core |

## Key Features

- **Ultra-compact form factor**: Minimal dimensions for tight integration
- **Breadboard friendly**: Design optimized for breadboard prototyping
- **THT headers**: Standard 2.54mm pitch through-hole pins
- **Smart header layout**: Bottom header deliberately offset by 1.27mm (half pitch) to prevent accidental shorts in breadboards
- **Simple power supply**: 3.3V to 12V input with onboard LDO
- **Essential pins exposed**: Focused on providing the most important functionality
- **UART debug access**: Dedicated UART pins for easy programming and debugging
- **KiCad design files**: Complete open-source hardware design

## Design Philosophy

These development kits are designed with several principles in mind:
- **Minimal but complete**: Only essential components while maintaining full functionality
- **Direct integration**: Design that works in final projects, not just for prototyping
- **Hackable**: Easy to modify and adapt to specific needs
- **Open design**: Full schematics and PCB files available

## Getting Started

Visit each development kit's directory for specific documentation:

- [ESP32-C3-THTKIT Documentation](esp32-c3-thtkit/)
- [ESP32-H2-THTKIT Documentation](esp32-h2-thtkit/)

## License

This project is released under the [MIT License](LICENSE).