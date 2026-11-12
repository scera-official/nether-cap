# Hardware Overview

This page records hardware context from public upstream documentation and the filenames of the user-provided archive. It is not a wiring guide or firmware installation procedure.

## Hardware families mentioned upstream

The upstream Nethercap project describes builds for:

- ESP8266
- ESP32
- BW16 / RTL8720DN

This repository's supplied firmware archive was labelled for ESP8266 and 4 MB flash.

## ESP8266 display variants

The archive listing previously supplied with this project identified two filenames:

| Firmware filename | Display driver indicated by name |
|---|---|
| `NETHERCAP_FREE_SH1106_4MB.bin` | SH1106 |
| `NETHERCAP_FREE_SSD1306_4MB.bin` | SSD1306 |

These names are not proof of board compatibility. They do not confirm pin mapping, flash layout, firmware integrity, or safe operation.

## Before relying on any hardware claim

Confirm the exact board model and revision, flash capacity, display controller, and vendor documentation. Do not assume that two boards with the same ESP8266 chip are interchangeable. A mismatched or untrusted binary can make a board unusable or expose it to unexpected behaviour.

## Safe learning alternatives

For an educational ESP8266 project, consider a non-disruptive local sensor dashboard, a Wi-Fi signal-strength display for your own access point, or a simple web server that does not impersonate other networks or interfere with nearby devices.

## References

- [Upstream Nethercap repository](https://github.com/Cancro29/NETHERCAP)
- [ESP8266 documentation — Espressif](https://docs.espressif.com/projects/esp8266/)

This repository does not provide attack firmware, pin-by-pin attack wiring, or operational instructions for wireless disruption.
