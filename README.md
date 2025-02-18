# RexPilot 🦖

RexPilot is my personal fork of the OpenPilot driver assistance system with enhancements to reduce distractions and noise. Based on FrogPilot, it enables a quiet, screen-off driving experience, allowing drivers to use the instrument cluster instead.

**Enhancements:**

- Screen stays off while driving in standby mode, unless critical alerts happen or experimental mode is toggled.
- Improved integration with Toyota and Lexus instrument clusters:
  - Left and right lane lines show what the driving model detects
  - LTA icon indicates lateral control, engagement status, and steering override.
- Removed annoying "Reverse Gear" message.
- Removed annoying startup message.
- Replaced obnoxious boot logo

**Planned features:**

- Improve the "wrong gear" alert

## Installation on Comma3X

Enter the following URL at installation where you choose "Custom Software (Advanced)". The first install may take over 10 minutes as the user interface is compiled on your device.

```
https://installer.comma.ai/keyeh/RexPilot
```

## Default settings

I suggest using these settings to have a quiet and peaceful drive:

- Screen Standby Mode: ON
- Screen Timeout (Onroad): 5 seconds
- Alert Volume Controller: set according to your preferences

## Development

This repository is automatically rebased daily onto the latest upstream `FrogPilot` branch, before the `Compile FrogPilot` commit.

## What is openpilot?

[openpilot](http://github.com/commaai/openpilot) is an open source driver assistance system. Currently, openpilot performs the functions of Adaptive Cruise Control (ACC), Automated Lane Centering (ALC), Forward Collision Warning (FCW), and Lane Departure Warning (LDW) for a growing variety of [supported car makes, models, and model years](docs/CARS.md). In addition, while openpilot is engaged, a camera-based Driver Monitoring (DM) feature alerts distracted and asleep drivers. See more about [the vehicle integration](docs/INTEGRATION.md) and [limitations](docs/LIMITATIONS.md).

## What is FrogPilot? 🐸

FrogPilot is a fully open-sourced fork of openpilot, featuring clear and concise commits striving to be a resource for the openpilot developer community. It thrives on contributions from both users and developers, focusing on a collaborative, community-led approach to deliver an advanced openpilot experience for everyone!
