# Changelog
All notable changes to this project will be documented in this file.  

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),  
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [1.2.0] - 2025-08-30
### Added
- New `SystemInfo` protocol message exposing:
  - Firmware version
  - Protocol version
  - Build date
- Support for battery voltage monitoring
- Safety watchdog for motor driver

### Changed
- Motor control loop improved for smoother acceleration
- Updated protocol to **v2.1.0** (incompatible with firmware <1.1.0)

---

## [1.1.3] - 2025-07-10
### Fixed
- Fixed PWM overflow bug in motor driver
- Corrected units in temperature sensor reporting

---

## [1.1.0] - 2025-06-15
### Added
- Initial support for NanoPB protocol v2.0.0
- Telemetry messages for IMU data (accel, gyro, magnetometer)

### Changed
- Reorganized source tree to follow Zephyr module layout

---

## [1.0.0] - 2025-05-01
### Added
- First stable firmware release
- Implements NanoPB protocol v1.0.0
- Features:
  - Motor driver control
  - Basic telemetry (temperature, status flags)
