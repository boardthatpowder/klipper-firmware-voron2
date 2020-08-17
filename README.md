# Klipper Firmware

Klipper config for Voron V2.4 350mm^3 printer with the following components installed that impact firmware configuration:
- AfterBurner Galileo direct drive
- Dual SKR 1.4 Turbo boards
- Dual LED bars
- TMC2209 drivers
- Mosquito Magnum hotend (including Mosquito high temperature sensor and heater cartridge)
- Omron probe
- Moons steppers
    - X/Y: Moons MS17HA6P4200-06
    - Z:   Moons MS17HD6P4200-29


Note: swapped Moons X/Y MS17HA6P4200-06 steppers with BOM recommended LDO's. With Moons could achieve 350mm/s travel at 10k accel, but with the LDO's could achieve 800mm/s travel at 10k accel.
