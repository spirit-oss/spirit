# SPIRIT Smartphone – Open Source, Open Future

<p align="center">
    <img src="https://github.com/user-attachments/assets/60e87523-02cf-482b-8433-5f611e48ca2d" width="40%">
</p>

<p align="center">
  <a href="#how-the-project-is-organized"><img src="https://img.shields.io/badge/Purpose-Project%20Hub-blue?style=for-the-badge" alt="Purpose: Project Hub"></a>
  <a href="#current-development-status"><img src="https://img.shields.io/badge/Status-In%20Development-orange?style=for-the-badge" alt="Status: In Development"></a>
  <a href="https://discord.gg/aJ36KzGZ"><img src="https://img.shields.io/discord/1271169002228514816?label=Discord&logo=discord&style=for-the-badge" alt="Discord"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-GPL--3.0-green?style=for-the-badge" alt="License: GPL-3.0"></a>
</p>

---

**SPIRIT** is an open-source smartphone designed to put control, privacy, and repairability back into the hands of users. This repository is the central hub for the entire project, guiding you to the right place whether you want to build, contribute, or just learn more.

## Table of Contents
- [Join the Community](#join-the-community)
- [How the Project is Organized](#how-the-project-is-organized)
- [Current Development Status](#current-development-status)
- [Core Specifications](#core-specifications)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

## Join the Community
This project is built by and for the community. Get involved, ask questions, and follow our progress here:

| Platform | Link | Purpose |
| :--- | :--- | :--- |
| 💬 **Discord** | [**Join our Server**](https://discord.gg/aJ36KzGZ) | Real-time chat, support, and collaboration. |
| 📺 **YouTube** | [**@Spirit-OSS**](https://www.youtube.com/@Spirit-OSS) | Development updates, demos, and deep-dives. |
| 🌐 **Website** | [**spirit-oss.github.io**](https://spirit-oss.github.io) | Project overview and live status. |
| 📧 **Email** | [**contact.spirit.oss@gmail.com**](mailto:contact.spirit.oss@gmail.com) | For partnerships and direct inquiries. |
| 🤝 **Contribute** | [**CONTRIBUTING.md**](https://github.com/spirit-oss/spirit/blob/main/CONTRIBUTING.md) | Learn how you can help build SPIRIT. |

## How the Project is Organized
SPIRIT is a modular project spread across several repositories. Find the one that fits your interest in the table below.

| I want to... | Go to Repository | What's Inside |
| :--- | :--- | :--- |
| **Understand the project** | `spirit` (You are here) | Project roadmap, high-level coordination, and this guide. |
| **Modify the hardware** | [**`spirit-design`**](https://github.com/spirit-oss/spirit-design) | KiCad schematics, PCB layouts, 3D models, Bill of Materials (BOM). |
| **Develop the OS** | [**`spirit-os`**](https://github.com/spirit-oss/spirit-os) | AOSP device tree, kernel drivers, and software customizations. |
| **Read the docs / build a phone**| [**`spirit-docs`**](https://github.com/spirit-oss/spirit-docs) | Assembly guides, user manuals, build instructions, specifications. |
| **Update the website**| [**`spirit-oss.github.io`**](https://github.com/spirit-oss/spirit-oss.github.io) | The HTML/CSS/JS for our official project website. |
| **Find logos or templates** | [**`assets`**](https://github.com/spirit-oss/assets) | Shared project logos, branding, images, and document templates. |

## Current Development Status
**SPIRIT is in active development.** Here's a snapshot of our progress.

| Component | Status | Notes |
| :--- | :---: | :--- |
| **Privacy Switches** | ✅ | Hardware design complete and integrated into the PCB. |
| **Display & Touch** | ✅ | Fully functional with driver support in AOSP. |
| **Wi-Fi & Bluetooth** | ✅ | Core connectivity is working in the OS. |
| **Hardware PCB** | 🚧 | Prototype assembled and currently in testing phase. |
| **Android OS (AOSP)** | 🚧 | AOSP 16 boots; core features working, HALs in progress. |
| **Camera** | 🚧 | Hardware is integrated; software HAL is under development. |
| **Cellular (4G/5G)** | 🚧 | Basic RIL functionality; requires further optimization. |
| **GPS / GNSS** | ❌ | Hardware present; driver development has not yet started. |

**Legend:** ✅ = Complete | 🚧 = In Progress | ❌ = Not Started

See an area you can help with? Check the "Issues" tab in the relevant repository or bring it up on Discord!

## Core Specifications
- **Processor:** Broadcom BCM2712 (64-bit, quad-core, up to 2.4GHz)
- **RAM:** 2GB–16GB LPDDR4 options
- **Storage:** 16GB–64GB eMMC, expandable via MicroSD
- **Display:** 5.5" TFT, 720×1280 resolution
- **Connectivity:** Wi-Fi, Bluetooth 5, GSM, GPS/GNSS
- **Privacy Switches:** Physical hardware cut-offs for Mic, Camera, and Radios (GPS/Cellular).

## Getting Started

### New to the Project?
1.  **Explore the Website:** Get a high-level overview at [spirit-oss.github.io](https://spirit-oss.github.io).
2.  **Read the Docs:** Learn more in the [Project Overview documentation](../spirit-docs/getting-started/project-overview.md).
3.  **Join the Conversation:** Say hello on our [Discord Server](https://discord.gg/aJ36KzGZ).

### Ready to Build or Contribute?
1.  **Find Your Niche:** Use the [repository guide](#how-the-project-is-organized) to pick an area.
2.  **Read the Guidelines:** Each repository has its own `CONTRIBUTING.md` with specific instructions.
3.  **Find a Task:** Look for issues labeled `good first issue` to get started.

## Contributing
We welcome all contributors, from hardware engineers to documentation writers. Contributions are primarily managed through GitHub Issues and Pull Requests. Please read our main [Contribution Guide](CONTRIBUTING.md) to learn more.

## License
The SPIRIT project, including all hardware designs, software, and documentation, is licensed under the [GPL-3.0 License](LICENSE). We believe in free and open access to technology for everyone.

---

<p align="center">
  <strong>SPIRIT: Taking back control of our digital lives.</strong>
</p>
