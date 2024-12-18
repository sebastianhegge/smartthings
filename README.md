[![hacs_badge](https://img.shields.io/badge/HACS-Custom-41BDF5.svg)](https://github.com/hacs/integration)
# SmartThings Custom
A fork of the Home Assistant SmartThings Integration. This adds some additional Sensor Devices.

## Added devices:
  - Cooktop Operating State
  - Cooktop Flex Zone
  - Kids Lock Control
  - Audio Mute
  - Residual Heat
  - Heating Mode
  - Manual Level
  - Manual Level Min
  - Manual Level Max
  - Supported Heating Modes
  - Count Down Timer Status
  - Count Down Timer Start Value
  - Count Down Timer Current Value
  - Firmware Update Available


## Known issues:
Home Assistant SmartThings doesn't support child devices, so burner's are not recognized at the moment.

## Installation:
### HACS
- Remove your original SmartThings integration
- Add `https://github.com/sebastianhegge/smartthings` as a Custom Repository
- Install `SmartThings Custom` from the HACS Integrations
- Restart Home Assistant
- Install `SmartThings` from the HA Integrations tab

## License
[MIT](LICENSE)
