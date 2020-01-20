# HomeAssistant Tuya based floor thermostat BHT-002-GBLW custom component

## Setup
Place manifest.json, \_\_init\_\_.py and climate.py into custom_components/tuya_climate. Then setup config.

## Configuration
```
climate:
  - platform: tuya_climate
    ip: "IP"
    id: "ID"
    key: "KEY"
    scan_interval: 10 # how frequently request updates from thermostat
```

## Key and ID extraction

https://github.com/codetheweb/tuyapi/blob/master/docs/SETUP.md has  information for how to get device id and local key.