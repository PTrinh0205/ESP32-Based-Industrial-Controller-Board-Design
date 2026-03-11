# ESP32-Based-Industrial-Controller-Board-Design

## Summary
A custom-designed PCB centered on the **ESP32-WROOM-32** module, tailored for industrial monitoring and data acquisition.

## Hardware Specifications
- **MCU**: ESP32 (Dual-core, Wi-Fi & Bluetooth integrated).
- **Power Management**: 3.3V switching regulator using **TPS5430**, supporting 5V-36V input range.
- **Sensing**: Dual-channel current sensing via **LM358** op-amps and **TA12/TA17** sensors.
- **Communication Protocols**: 
    - **RS-485** interface (MAX485) for robust long-distance data exchange.
    - UART/MQTT for IoT cloud connectivity (Adafruit IO).
- **Peripheral Interface**: 4-bit DIP switch, 2-color status LEDs (MMBT3904 driven), and RJ45 connectors.

## Software/Tools
- **PCB Design**: Altium Designer (Schematic & Layout)
- **Simulation**: PSpice
- **Firmware**: Python (MicroPython) / C++
