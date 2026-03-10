# HexForge Portable Slicer

A custom portable build of OrcaSlicer tailored for HexForge Labs' 3D printing workflow. This repository organizes the portable distribution and adds HexForge-specific profiles, presets, and branding assets.

## Overview
- Portable OrcaSlicer bundle curated for HexForge Labs.
- Includes lab-specific printer profiles, presets, and future branding.
- Repository structured for easy updates and collaboration without touching bundled binaries.

## Features
- Ready-to-run portable slicer (`orca-slicer.exe`).
- HexForge printer profiles for consistent lab output.
- Presets tuned for common materials (e.g., easy support removal for PLA).
- Placeholder branding assets for upcoming UI customization.

## Supported Printers
- Ender-3 (CR-Touch)
- FlashForge Creator Pro
- Anycubic Kobra 3 V2 + ACE
- Anycubic Kobra X + ACE Pro

## Installation
1) Download or clone this repository.
2) Keep the folder structure intact; no installer required.
3) Ensure you have required printer drivers/USB permissions as usual.

## Usage
- Launch `orca-slicer.exe` from the repository root.
- Select the HexForge profiles under `resources/profiles/HexForge/` as needed.
- Apply presets (e.g., HexForge_EasySupportRemoval) before slicing.

## Repository Structure
- resources/profiles/HexForge/ — HexForge printer profiles.
- presets/ — Print and material presets.
- branding/ — Logos and splash assets (placeholders for now).
- docs/ — Project documentation and notes.
- slicer binaries — Portable OrcaSlicer executables and supporting files.

Visual tree:
```
HexForge Portable Slicer
│
├── resources
│   └── profiles
│       └── HexForge
├── presets
├── branding
├── docs
└── slicer binaries
```

## Future Roadmap
- Add finalized HexForge-branded UI elements.
- Expand printer and material presets (PETG, ABS, flexible filaments).
- Automated CI packaging for portable builds.
- Lab QA checklists and calibration guides.
