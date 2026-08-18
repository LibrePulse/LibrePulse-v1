# LibrePulse 1

![Status](https://img.shields.io/badge/Status-Early%20WIP-orange)
[![License](https://img.shields.io/badge/License-CERN--OHL--S-blue)](https://github.com/spdx/license-list-data/blob/main/text/CERN-OHL-S-2.0.txt)

Flagship-level open source smartwatch on the ESP32-P4.

---

## Scope

**LibrePulse aims to be:**
- A high-end, fully open, well-documented smartwatch (hardware + software)
- Competitive with commercial flagship watches
- Repairable and understandable


**Current hardware direction includes:**
- ESP32-P4 + ESP32-C3
- Full health sensing (PPG + ECG + BioZ + EDA via AS7058 & Body Temp via AS6221)
- High-quality Sensor suite (including: 9-Axis DOF, pMUT ToF, ALS, UV, GNSS, TPHG)
- Microphone, Speaker, Vibration Motor, Flashlight
- 64GB eMMC (KLMCG4JETD-B041) + microSD Card
- \~1300 mAh battery + Qi1.3 wireless charging
- Slint UI on Zephyr RTOS (in Rust)

**Non-goals (for now):**
- Ultra-thin or ultra-small form factor
- Lowest possible cost
- Supporting every possible sensor or radio

Schematic and PCB work is actively in progress (KiCad files are in the repository).

---

## Project Roadmap

- [ ] **Schematic**
  - [x] ~~Draft~~
  - [ ] Cleanup
  - [ ] Verification

- [ ] **PCB**
  - [ ] Placement draft
  - [ ] Routing draft
  - [ ] Verification

- [ ] **Enclosure**
  - [ ] 3D CAD design
  - [ ] Fit test
  - [ ] Finalize production files

- [ ] **Software**
  - [ ] Write Drivers
  - [ ] Integrate Zephyr RTOS using Rust
  - [ ] Write UI in Slint
  ## NOTE: this roadmap is a simplified overview for the full roadmap [ROADMAP.md](ROADMAP.md)
