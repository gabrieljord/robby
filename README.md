# Robby - Automated 5-Disc Media Ripper Robot

An automated 5-disc tray robotic media ripping station that streamlines ripping physical media (DVDs, Blu-rays, and CDs), syncing media over the network or cloud via `rclone`, and cataloging collections in Jellyfin.

---

## Overview

**Robby** is an automated disc loader and ripping system built to eliminate manual disc-swapping. With a motorized 5-disc carousel/tray mechanism, the robot sequentially loads, rips, and unloads physical optical media without manual intervention.

### Key Features
- **Batch Processing**: 5-disc motorized tray mechanism for unattended queue processing.
- **Multi-Format Support**: Automated ripping pipeline for DVDs, Blu-rays, and audio CDs.
- **Automated Cloud & NAS Sync**: Built-in `rclone` workflows to push completed rips directly to a local NAS or cloud storage (such as Google Drive).
- **Jellyfin Integration**: Automatically organizes folders, tags media, and updates your Jellyfin media library.

---

## Project Structure & Components

| Component / Directory | Description |
| :--- | :--- |
| **[hardware/](hardware/)** | CAD files, 3D print STLs, mechanical assemblies, and tray mechanism designs. |
| **[software/](software/)** | Ripping automation scripts, motor control/firmware, `rclone` sync pipeline, and Jellyfin integration. |
| **[docs/](docs/)** | Bill of Materials (BOM), assembly instructions, wiring diagrams, and setup guides. |

### Component Breakdown

- **[Hardware & CAD Designs](hardware/)**: Contains all mechanical assets, including CAD source files, STEP/STL models for 3D printing, chassis components, and stepper/servo mounting brackets for the 5-disc tray mechanism.
- **[Software & Automation Pipeline](software/)**: Contains the ripping automation tools, disc-detection and changer control logic, `rclone` NAS/cloud backup routines, and Jellyfin library updater scripts.
- **[Documentation & BOM](docs/)**: Contains project documentation, component sourcing info, full Bill of Materials (BOM), electronics schematics, and software setup guides.
