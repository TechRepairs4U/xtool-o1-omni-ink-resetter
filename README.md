# xTool O1 Omni Ink Resetter

**Version 1.0.1 · Made by TechRepairs4U**

A Windows app for viewing your xTool O1 Omni printer's ink levels and manually resetting the recorded level after you have refilled a cartridge.

![xTool O1 Omni Ink Resetter showing the UV + DT ink and maintenance dashboard](screenshots/app-preview.png)

*UV + DT layout shown with sample readings in offline preview.*

## Download

[Download xTool O1 Omni Ink Resetter v1.0.1 for Windows](https://github.com/TechRepairs4U/xtool-o1-omni-ink-resetter/releases/download/v1.0.1/xTool-O1-Omni-Ink-Resetter-v1.0.1.exe)

Download the `.exe` and open it on a Windows PC. Connect the PC to the same local network as your printer.

## What it does

- Shows the ink levels and maintenance-tank information reported by your printer.
- Helps find printers on a local network and lets you save their addresses.
- Lets you manually update a cartridge's recorded ink level after refilling it.
- Provides layouts for **Single UV**, **Dual UV**, and **UV + DT (fabric)**.
- Shows the Dual UV expansion inks separately: **Rigid White (RW)**, **Flexible White (FW)**, **Fluorescent Red (FR)** and **Fluorescent Yellow (FY)**.

## Getting started

1. Choose your printer model.
2. Enter its IP address, or click **Search network** and enter your local network range, such as `192.168.1.0/24`.
3. Select the printer and click **Connect**. If a pairing message appears, press the printer's illuminated **Start/Stop button once** and keep the app open.
4. Open **Ink & maintenance** to view the cartridges.
5. After physically refilling a cartridge, use its **Refill** button and follow the confirmation steps.

Network search needs the correct local range; it cannot find a printer at another location over the internet.

## Version 1.0.1: printer login update

This update adds the newer printer-confirmed pairing flow to address **406 guest login rejected** errors on firmware that requires pairing. Successful pairing is remembered for future connections. The app now waits for you to click Connect and keeps any connection error visible so it can be shared for troubleshooting.

The included engine has been updated to upstream 1.0.31. Pairing was introduced upstream for firmware V0.14.11, with the older login retained for V0.13.1. The affected physical printer still needs to be tested; if the error continues, share the full message and your printer's firmware version.

## Support the app

If this app has helped you, consider buying me a coffee. Donations help support future updates and are always optional.

<a href="https://www.buymeacoffee.com/TechRepairs4u"><img src="assets/buy-me-a-coffee.webp" alt="Buy me a coffee" width="220"></a>

## Before using it

Resetting the displayed level does not add ink. This app does not make cartridges chipless and does not automatically reset them when removed and reinserted.

The interface, build and simulated pairing flow have passed offline checks, and the Windows app has been launched successfully. Discovery, connection and ink resets still need testing with a physical printer, so compatibility with every firmware version is not confirmed.

This is an independent utility by TechRepairs4U, not an official xTool application. This repository contains the Windows download and usage information; source code is not published here.

## File verification

SHA-256 for `xTool-O1-Omni-Ink-Resetter-v1.0.1.exe`:

```text
c31c549b1dfa57a5f9676a983af8670cf2607f292afd18b2f3c39dc64ebeed03
```
