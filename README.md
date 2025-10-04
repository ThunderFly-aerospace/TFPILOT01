# Teensy 4.1 Controller for dRehmFlight

This project is a hardware controller board designed specifically for use with the [dRehmFlight open-source flight controller firmware](https://github.com/nickrehm/dRehmFlight). It is based on the Teensy 4.1 microcontroller and provides all the essential interfaces and components needed for a compact, capable flight control unit.

## Features

### Core Components

* **Teensy 4.1** (MIMXRT1062DVJ6B – Arm Cortex-M7 @ 600 MHz)
* **MKL02Z32VFG4** bootloader MCU (required for Teensy compatibility)
* **W25Q64JVXGIM** 8 Mb SPI Flash memory

### Sensors

* **GY-91 (MPU9250 + BMP280)** IMU module connected via **SPI** for reduced latency.

  * Replaces the GY-521 module (MPU6050) commonly used in the default dRehmFlight configuration
  * Integrated magnetometer (AK8963) provides full 9‑DOF capability
  * Integrated BMP280 barometric sensor for altitude estimation

### Storage

* **microSD card slot** for onboard data logging

### Power and Connectivity

* **XT30 power connector** for powering both the autopilot and connected servos
* **PWM outputs** using standard RC servo connectors for direct model integration
* **Multiple high-current GPIO outputs** with transistor drivers for triggering pyrotechnic or other one-shot actuators
* **USB‑C connector** for power and debug interface (compatible with PJRC Teensy bootloader)

### Expansion and Debugging

* **2.54 mm pin headers** for access to all I/O pins (except D41)
* **JTAG pins** broken out (not yet tested)

## Acknowledgements

This updated board builds upon the original Teensy 4.1 KiCad example design, transforming it into a purpose-built flight controller platform optimized for dRehmFlight. It adds robust sensing, storage, power distribution, and actuator control features for experimental UAV and aerospace applications.

