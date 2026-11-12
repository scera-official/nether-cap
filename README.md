# Nethercap — ESP8266 Wi-Fi Security Project Notes

> **Documentation companion repository.** This repository is maintained by the SCERA Official account and is not the upstream Nethercap project.

Nethercap is a third-party wireless-security project associated with embedded boards including **ESP8266**, **ESP32**, and **BW16 (RTL8720DN)**. The upstream project describes itself as a Wi-Fi penetration-testing tool. Its published materials also describe capabilities that can disrupt wireless connectivity or imitate access points. Those capabilities can affect other people's devices and networks, so this repository intentionally does **not** redistribute firmware binaries, attack code, or instructions for disruptive or deceptive operations.

## What is in this repository?

- Hardware and project overview
- A transparent inventory of the supplied archive names
- General ESP8266 serial/USB troubleshooting
- Responsible-use and home-router security guidance
- Contribution, security-reporting, and third-party licensing notes

This repository is currently **documentation-only**. No firmware, executable flasher, source-code archive, or compiled binary is included.

## Project references

- Upstream project: [Cancro29/NETHERCAP](https://github.com/Cancro29/NETHERCAP)
- Upstream releases: [NETHERCAP releases](https://github.com/Cancro29/NETHERCAP/releases)
- Upstream wiki: [NETHERCAP wiki](https://github.com/Cancro29/NETHERCAP/wiki)
- Upstream FAQ: [NETHERCAP FAQ](https://github.com/Cancro29/NETHERCAP/wiki/FAQ)

These links are provided for attribution and background only. This repository is not affiliated with, endorsed by, or a substitute for the upstream project.

## Important safety boundary

Only assess networks and devices that you own or have explicit permission to assess. Do not interfere with nearby networks, collect other people's credentials, impersonate trusted networks, or interrupt connectivity. For a safe learning project, focus on passive observation, router configuration review, and defensive security checks.

## Hardware overview

The supplied archive was described as containing ESP8266 firmware variants named:

- `NETHERCAP_FREE_SH1106_4MB.bin`
- `NETHERCAP_FREE_SSD1306_4MB.bin`

The names indicate OLED driver variants (SH1106 and SSD1306) and a 4 MB flash target. **This is filename-level information only**; the binaries have not been independently inspected, verified, or tested by this repository.

See [HARDWARE.md](HARDWARE.md) and [FILE_INVENTORY.md](FILE_INVENTORY.md).

## Documentation

| Document | Description |
|---|---|
| [HARDWARE.md](HARDWARE.md) | Board and display overview |
| [FILE_INVENTORY.md](FILE_INVENTORY.md) | Supplied archive inventory and verification status |
| [TROUBLESHOOTING.md](TROUBLESHOOTING.md) | General USB/serial and board diagnostics |
| [SAFE_WIFI_GUIDE.md](SAFE_WIFI_GUIDE.md) | Defensive home Wi-Fi checklist |
| [FAQ.md](FAQ.md) | Common project and repository questions |
| [DISCLAIMER.md](DISCLAIMER.md) | Responsible-use and limitation notice |
| [LICENSE_STATUS.md](LICENSE_STATUS.md) | Licensing and redistribution status |
| [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) | Attribution and third-party references |
| [CONTRIBUTING.md](CONTRIBUTING.md) | Contribution guidelines |
| [SECURITY.md](SECURITY.md) | Responsible security reporting |
| [CHANGELOG.md](CHANGELOG.md) | Repository documentation history |

## Status

- Repository type: documentation companion
- Hardware family discussed: ESP8266
- Firmware included: no
- Executable tools included: no
- Firmware provenance and redistribution permission: not verified

If you are the rights holder for any third-party component and believe this repository needs an attribution or licensing correction, please open an issue with the relevant details.
