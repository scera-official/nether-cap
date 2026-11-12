# Troubleshooting

This guide covers general ESP8266 board and USB/serial diagnostics. It does not explain how to install or operate wireless-attack firmware.

## 1. Board is not detected by the computer

- Try a known data-capable USB cable; some cables provide power only.
- Try another USB port directly on the computer.
- Check Windows Device Manager for a newly appearing COM port.
- If no serial device appears, identify the USB-to-UART chip printed on the board and consult its manufacturer's official driver documentation.
- Avoid installing drivers from unofficial download mirrors.

## 2. Serial port is busy

- Close other serial monitors and terminal applications.
- Disconnect and reconnect the board.
- Reopen the development environment and select the port that actually appeared.
- Do not assume a COM port number from an older session is still correct.

## 3. Upload or serial communication fails

For ordinary, benign ESP8266 development:

- Confirm the selected board profile matches the exact board.
- Confirm the selected serial port.
- Check that the USB cable and connector are stable.
- Close applications that may be holding the port.
- Review the board vendor's documentation for its normal boot and upload requirements.

Do not repeatedly force upload attempts if the board becomes unusually hot, smells burnt, or shows signs of electrical damage. Disconnect it and stop testing.

## 4. OLED display is blank

A blank screen can result from an incorrect display controller assumption, wiring, power, or a damaged display. SH1106 and SSD1306 are different controller families; a filename alone does not establish compatibility.

For a safe display test, use a simple known-good graphics example from the display library's official documentation, not an unverified third-party binary.

## 5. Board resets or becomes unstable

- Disconnect external peripherals and inspect for shorts.
- Use a stable, correctly rated power source.
- Check for loose jumper wires or damaged connectors.
- Stop if the board or regulator becomes hot.

## 6. Safety and file-integrity concerns

Do not run an unknown Windows executable with administrator privileges. Do not flash a binary whose source, licence, and integrity you cannot establish. A firmware file can permanently alter device behaviour.

## Information to include in a support report

- Exact board model and revision
- Operating system
- USB-to-serial chip marking
- Error message copied as text
- Whether the board appears in Device Manager
- Display controller marking, if applicable

Never include passwords, tokens, private network details, or other people's personal information in a public issue.
