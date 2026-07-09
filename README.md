# stromdisplay-releases

Public firmware releases for [Stromdisplay](https://github.com/k8dhnqmxjd-create/stromdisplay-360-display) (ESP32-S3 electricity price display).

This repo holds **no source code** -- only `manifest.json` / `manifest-beta.json` and the firmware binaries under `firmware/`. Devices poll `manifest.json` (stable channel) via `raw.githubusercontent.com` for OTA updates; `manifest-beta.json` is used only by the developer's own test device.

Published and updated by `release.sh` in the source repo.
