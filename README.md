# SPIRIT Smartphone – Open Source, Open Future

<p align="center">
    <img src="https://github.com/user-attachments/assets/60e87523-02cf-482b-8433-5f611e48ca2d" width="40%">
</p>

<p align="center">
  <img src="https://img.shields.io/github/v/release/V3lectronics/SPIRIT">
  <img src="https://img.shields.io/badge/License-Open%20Source-blue">
  <img src="https://img.shields.io/badge/Status-Development-orange">
</p>

---

## About

**SPIRIT** is an open-source smartphone project designed to put control, repairability, and privacy back in the hands of users.  
Every component, schematic, and line of code is openly documented and modifiable.

- **Transparent hardware & software**
- **Physical privacy controls**
- **Repairable & upgradeable by design**
- **Community-driven development**
- **Ethical sourcing**

This repo is your entry point to the **entire project** — from hardware design to software builds, DIY assembly, and philosophy.

---

## Project Repositories

SPIRIT is organized into specialized repositories for different aspects of the project. Choose the one that matches your interests:

### Want to Contribute to Hardware?
**Repository:** [spirit-design](../spirit-design)  
**Perfect for:** Hardware engineers, PCB designers, mechanical engineers, and repair enthusiasts  
**Contains:** KiCad schematics, PCB layouts, Bill of Materials, 3D models, mechanical drawings

### Want to Develop Software?
**Repository:** [spirit-os](../spirit-os)  
**Perfect for:** Android developers, ROM builders, kernel developers, and software enthusiasts  
**Contains:** AOSP device configuration, drivers, system customizations for Raspberry Pi 5

### Need Documentation or Want to Learn More?
**Repository:** [spirit-docs](../spirit-docs)  
**Perfect for:** New users, technical writers, and anyone wanting comprehensive guides  
**Contains:** Assembly guides, specifications, troubleshooting, user manuals, development docs

### Want to See the Big Picture?
**Repository:** spirit (this repository)  
**Perfect for:** Project overview, general discussions, and coordination between teams  
**Contains:** Project roadmap, general information, and links to specialized repositories

---

## Quick Navigation by Interest

| I want to... | Go to Repository | Key Resources |
|--------------|------------------|---------------|
| **Build my own SPIRIT phone** | [spirit-docs](../spirit-docs) → [Assembly Guide](../spirit-docs/hardware/assembly-guide.md) | Complete build instructions, BOM, troubleshooting |
| **Modify the hardware design** | [spirit-design](../spirit-design) | KiCad files, schematics, PCB layouts |
| **Customize the Android OS** | [spirit-os](../spirit-os) | AOSP build system, device trees, drivers |
| **Understand the technical specs** | [spirit-docs](../spirit-docs) → [Specifications](../spirit-docs/hardware/specifications.md) | Detailed hardware and software specifications |
| **Join the community** | [spirit-docs](../spirit-docs) → [Community](../spirit-docs/community/) | Discord, support channels, events |
| **Contribute code or designs** | See contributing guides in each repo | [Hardware](../spirit-design), [Software](../spirit-os), [Docs](../spirit-docs) |

---

## Project Overview

SPIRIT breaks away from locked-down devices by:

1. **Empowering the user** – you decide what runs and what’s connected.
2. **Ensuring privacy** – hardware switches physically cut off mic, camera, GPS, and cellular radios.
3. **Encouraging community collaboration** – hardware, firmware, and documentation are all open.

Current development is documented here and on our  
🎥 [V Electronics YouTube Channel](https://www.youtube.com/@V_Electronics).

---

## Core Specifications

- **Processor:** Broadcom BCM2712 (64-bit, quad-core, up to 2.4GHz)  
- **RAM:** 2GB–16GB LPDDR4 options  
- **Storage:** 16GB–64GB eMMC, expandable  
- **Display:** 5.5" TFT, 720×1280 resolution  
- **Connectivity:** Wi-Fi, Bluetooth 5, GSM, GPS/GNSS  
- **Privacy Switches:** Mic, GPS/GSM, Camera, Battery  

---

## Current Development Status

**SPIRIT is actively in development.** Here's what's working and what's coming:

| Component | Status | Notes |
|-----------|:------:|-------|
| **Hardware PCB** | 🚧 | Prototype assembled, testing in progress |
| **Android OS** | 🚧 | AOSP 16 boots, core features working |
| **Privacy Switches** | ✅ | Hardware design complete |
| **Display & Touch** | ✅ | Fully functional |
| **Wi-Fi & Bluetooth** | ✅ | Working in software |
| **Camera** | 🚧 | Hardware ready, software integration ongoing |
| **Cellular (4G/5G)** | 🚧 | Basic functionality, optimization needed |
| **GPS** | ❌ | Driver development required |

✅ = Complete | 🚧 = In Progress | ❌ = Not Started

**Want to help?** Check the issues in each repository or join our [Discord](https://discord.gg/zBG4KdHJWx) to see what needs attention!

---

## Getting Started

### New to SPIRIT?
1. **Learn about the project** → Read [Project Overview](../spirit-docs/getting-started/project-overview.md)
2. **See what's possible** → Watch [V Electronics YouTube](https://www.youtube.com/@V_Electronics)
3. **Join the community** → [Discord Server](https://discord.gg/zBG4KdHJWx)

### Ready to Build?
1. **Check requirements** → [spirit-docs](../spirit-docs) Hardware Assembly Guide
2. **Get the parts** → Bill of Materials in [spirit-design](../spirit-design)
3. **Follow the build guide** → Step-by-step instructions in documentation

### Want to Contribute?
1. **Pick your area** → Use the repository guide above
2. **Read contribution guidelines** → Each repo has its own CONTRIBUTING.md
3. **Start small** → Look for "good first issue" labels

---

## Contributing

We welcome all contributors: developers, designers, engineers, and testers.

- **Code & hardware design contributions** → Pull requests
- **Documentation improvements** → Direct edits or PRs
- **Testing feedback** → GitHub Issues

Please read our [Contribution Guide](CONTRIBUTING.md).

---

## License

All SPIRIT resources (hardware, software, and documentation) are released under open-source licenses.  
Details are in the `/licenses` directory.

---

<p align="center">
  <strong>SPIRIT: Taking back control of our digital lives</strong>
</p>
