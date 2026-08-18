# HUUM Dial firmware

Public over-the-air binaries for the HUUM Dial (M5Dial S3 and ESP32-C3).

Application source is private. Each `vX.Y.Z` GitHub Release contains:

- seven SKU-specific `.bin` files
- one signed `release.json` envelope

Dials fetch:

`https://github.com/hsuperman/sauna-controller/releases/latest/download/release.json`

Do not edit published tags or overwrite binaries. If a release is bad, publish a newer version.
