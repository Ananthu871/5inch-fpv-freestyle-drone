# 5inch-fpv-freestyle-drone
Built and configured a high-performance 6S FPV freestyle drone from scratch, including hardware integration, firmware tuning, ESC calibration, GPS rescue, and HD digital FPV system setup.


# 5-Inch FPV Freestyle Drone Build

Built and configured a high-performance 6S FPV freestyle drone from scratch, including hardware integration, firmware tuning, ESC calibration, GPS rescue, and HD digital FPV system setup.

---

## Project Overview

Built a 6S freestyle FPV drone from scratch for responsive control, stable flight, and long-range HD video transmission. The project required both hardware integration and low-level firmware configuration.

---

## Hardware Components

| Component | Model |
|-----------|-------|
| Frame | GEPRC Mark4 5-inch Frame |
| Flight Controller | Radiolink F722 |
| ESC | JHEMCU 45A 4-in-1 ESC |
| Motors | T-Motor Velox V3 2207 1750KV |
| Receiver | SpeedyBee Nano ELRS Receiver |
| Transmitter | Radiomaster Pocket ELRS |
| GPS | HGLRC M10 GPS |
| Battery | CNHL 6S LiPo |
| FPV Camera / VTX | DJI O4 Air Unit |
| Goggles | DJI Goggles |

---

## Features

- 6S high-performance freestyle build
- HD digital FPV video transmission
- Low-latency ELRS radio link
- GPS rescue and failsafe recovery
- Multiple flight modes
- Custom transmitter switch mapping
- Brushless motor propulsion system
- ESC firmware optimization using Bluejay

---

## Engineering Tasks Performed

### Mechanical Assembly

- Assembled full 5-inch drone frame
- Mounted motors and propellers
- Installed FC, ESC, receiver, GPS, and air unit
- Managed wiring and vibration isolation

### Electrical Integration

- Soldered ESC to flight controller
- Connected motors to 4-in-1 ESC
- Wired GPS, receiver, and DJI air unit to UART ports
- Verified power distribution and signal routing

### Flight Controller Configuration

Configured the drone using Betaflight:

- Port configuration
- Receiver protocol setup
- Motor direction verification
- Sensor calibration
- Failsafe setup
- PID tuning
- Rate tuning
- OSD configuration

### ESC Configuration

- Calibrated ESC using ESC Configurator
- Flashed Bluejay firmware to ESC
- Optimized motor startup behavior
- Verified motor direction and RPM response

### Radio Configuration

Configured Radiomaster Pocket with custom switch assignments:

| Switch Function | Purpose |
|-----------------|---------|
| Arm / Disarm | Enable or disable motors |
| Acro Mode | Manual freestyle flight |
| Angle Mode | Self-level stabilization |
| Horizon Mode | Assisted acrobatics |
| GPS Rescue | Automatic recovery on signal loss |
| Altitude Hold | Maintain altitude |

### GPS Integration

Integrated HGLRC M10 GPS:

- UART configuration
- Satellite lock verification
- Rescue mode configuration
- GPS telemetry monitoring

### EMI / Interference Reduction

Identified interference affecting:

- Camera transmitter
- GPS module

Mitigation:

- Increased distance between GPS and video transmitter
- Improved component placement to reduce electromagnetic interference
- Re-routed wiring for cleaner signal paths

---

## Challenges Faced

- ESC firmware flashing issues
- Rough motor startup after flashing
- GPS signal interference
- Camera transmitter noise
- Flight tuning for stable freestyle performance
- UART resource management

---

## Technical Skills Demonstrated

- Drone assembly
- Hardware debugging
- Soldering and wiring
- Embedded systems integration
- RF interference mitigation
- Flight controller firmware configuration
- ESC flashing and calibration
- Betaflight tuning
- ELRS receiver setup
- GPS rescue configuration
- Sensor troubleshooting

---

## Tools Used

- Betaflight Configurator
- Bluejay Configurator
- ESC Configurator
- Multimeter
- Soldering station
- Smoke stopper

---

## Outcome

Successfully built and tuned a fully functional 5-inch FPV freestyle drone with stable flight characteristics, GPS-assisted safety features, HD digital FPV transmission, and optimized ESC performance.

---

## Future Improvements

- Blackbox log analysis
- Advanced PID tuning
- Custom TPU mounts
- Long-range optimization
- Autonomous waypoint navigation