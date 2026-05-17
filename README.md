# Xteink X4 Custom Firmware Releases

This repository is the OTA release target for the custom Xteink X4 firmware based on CrossPoint Reader.

## OTA contract

The device OTA updater queries GitHub Releases latest at:

`https://api.github.com/repos/Sonny-bot-33/xteink-x4-custom-firmware/releases/latest`

Each release must include an asset named exactly:

- `firmware.bin`

That asset should be the patched/custom firmware image intended for OTA installation.
