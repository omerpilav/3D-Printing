# Autonomous Drone-Mounted BLE Sensor Data Collection System

A complete technical record of designing and building a Raspberry Pi Pico W drone pod that locates, wakes, and collects data from distributed IoT sensor sticks in the field.

**[View the full technical record →](https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/drone_project_full_record.html)**

*(Replace `YOUR-USERNAME` and `YOUR-REPO-NAME` once GitHub Pages is live — see setup note at the bottom.)*

## What This Covers

This record documents the entire build process in plain language, written for use as a research/reference document. It includes:

- **System overview** — what the drone pod does and why
- **Hardware** — the drone pod components and the sensor sticks (built by Franklin Slaby)
- **Wiring** — full pinout for the Raspberry Pi Pico W carrier board
- **BLE fundamentals** — advertising, services, characteristics, notifications, and how the data collection sequence works step by step
- **Debugging log** — what went wrong with BLE connections and how it was fixed, including confirmed working connection tests
- **GPS / waypoint navigation** — the two-flight system (mapping flight, then data collection flight), how GPS data is translated and combined with BLE
- **RF wake-up system** — 433MHz receiver (working) and the remaining transmitter automation problem, with two candidate solutions
- **Displays** — ST7796 (large, testing) and ST7735 (small, final build)
- **Session-by-session build log**
- **Full operational workflow** — from one-time setup through repeated data collection flights
- **Every script used in the project, in full**

## Hardware / Tech Stack

`Raspberry Pi Pico W` · `MicroPython` · `Bluetooth Low Energy` · `GPS / GNSS Navigation` · `433MHz RF Wake-Up` · `ST7796 + ST7735 Displays` · `SD Card Logging`

## Repo Contents

| File | Description |
|---|---|
| `drone_project_full_record.html` | Self-contained technical record (open directly or view live via GitHub Pages link above) |

## Viewing Locally

The HTML file is self-contained — just download it and open it in any browser, no setup required.

---

*Setup note: To activate the live link above, enable GitHub Pages in this repo under Settings → Pages → Deploy from branch `main`, folder `/root`. Then swap the placeholder URL in this README for your actual `github.io` link.*
