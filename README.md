# xTool O1 Omni Ink Resetter

**Version 1.0.0 · Made by TechRepairs4U**

A Windows app for viewing your xTool O1 Omni printer's ink levels and manually resetting the recorded level after you have refilled a cartridge.

## Download

[Download xTool O1 Omni Ink Resetter v1.0.0 for Windows](https://github.com/TechRepairs4U/xtool-o1-omni-ink-resetter/releases/download/v1.0.0/xTool-O1-Omni-Ink-Resetter-v1.0.0.exe)

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
3. Select the printer and click **Connect**.
4. Open **Ink & maintenance** to view the cartridges.
5. After physically refilling a cartridge, use its **Refill** button and follow the confirmation steps.

Network search needs the correct local range; it cannot find a printer at another location over the internet.

## Before using it

Resetting the displayed level does not add ink. This app does not make cartridges chipless and does not automatically reset them when removed and reinserted.

The interface and build have passed offline checks. Discovery, connection and ink resets still need testing with a physical printer, so compatibility with every firmware version is not confirmed.

This is an independent utility by TechRepairs4U, not an official xTool application. This repository contains the Windows download and usage information; source code is not published here.

## File verification

SHA-256 for `xTool-O1-Omni-Ink-Resetter-v1.0.0.exe`:

```text
76480452e1f77dce1c456f587f2507567661a9c794613180764152db5e3e103c
```
