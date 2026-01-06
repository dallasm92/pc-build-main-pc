# PC Build – MAIN-PC (Windows 11 Pro Hyper-V Host)

Custom-built workstation designed for virtualization, IT labs, and daily productivity.

This document covers:
- Hardware selection and rationale
- Physical build process
- BIOS and OS configuration
- Post-build validation

Purpose

This repository documents the research, assembly, configuration, and validation of my primary Windows 11 desktop (MAIN-PC).

The system was intentionally built to support:

Long-term daily use

Virtualization with Hyper-V

IT lab work (Windows Server, Linux, security testing)

CompTIA A+–aligned hardware knowledge

This project demonstrates hardware selection, compatibility research, system assembly, troubleshooting, and post-build validation.

🧠 Build Goals

Reliable long-term workstation

Strong multi-core performance for virtualization

NVMe storage for fast VM workloads

Upgrade-friendly platform

Practical learning experience aligned with IT fundamentals

🔍 Research & Planning
Tools Used

PCPartPicker – compatibility checking and part research

YouTube build guides – physical assembly reference

CompTIA A+ study material – hardware concepts and best practices

Manufacturer documentation (BIOS, chipset, drivers)

PCPartPicker was used to validate:

CPU ↔ motherboard compatibility

RAM type and speed support

Power requirements

Storage interface compatibility

Case clearance and airflow considerations

🧩 System Specifications (Sanitized)
Component	Details
Operating System	Windows 11 Pro
CPU	AMD Ryzen 7 3700X
GPU	NVIDIA RTX 3070
Memory	32 GB RAM
Storage	NVMe 1 TB + NVMe 500 GB
Virtualization	Hyper-V
Hostname	MAIN-PC

Serial numbers and unique identifiers are intentionally excluded.

💾 Storage Layout Strategy
Drive	Purpose
NVMe 1 TB	Host OS, applications, primary data
NVMe 500 GB	Virtual machines and lab workloads

Separating VM storage from the host OS helps with:

Performance isolation

Easier troubleshooting

Cleaner backup strategy

⚙️ Assembly Process (High Level)

CPU installation and thermal paste application

RAM installation and slot configuration

NVMe drive installation

Motherboard mounting

Power supply installation and cable management

GPU installation

Initial POST and BIOS verification

🔧 BIOS & Firmware Configuration

Key actions performed:

Verified CPU and RAM detection

Enabled virtualization extensions (SVM / AMD-V)

Checked boot mode (UEFI)

Confirmed NVMe detection

Updated BIOS (if applicable)

🖥️ Operating System Setup

Installed Windows 11 Pro

Installed chipset, GPU, and system drivers

Verified Device Manager health

Applied Windows updates

Enabled Hyper-V feature

🧪 Validation & Testing

Post-build validation included:

Successful POST and stable boot

Temperature monitoring under load

Disk health checks

Memory stability

Hyper-V VM creation and operation

General system responsiveness

The system is now stable and suitable for daily use and lab workloads.

🧰 Current Lab Usage

MAIN-PC is actively used as the primary Hyper-V host for:

Windows Server

Kali Linux

Ubuntu

RHEL 9 (Lab)

Linux Mint

Elementary OS

This system supports multi-OS virtualization, Windows Server labs, Linux administration, and security testing.

📚 Lessons Learned

Hardware compatibility research prevents costly mistakes

Proper storage planning improves VM performance

BIOS configuration is critical for virtualization

Documentation simplifies future troubleshooting and upgrades

Building a system deepens understanding of real-world IT support scenarios

🚀 Future Improvements

Additional storage as VM library grows

Enhanced backup strategy

Hardware monitoring and logging

Incremental upgrades as needs evolve

🔗 Related Repositories

Home Lab Overview
Architecture and network overview
https://github.com/dallasm92/home-lab-overview

IT Support Labs
Ticket-style troubleshooting documentation
https://github.com/dallasm92/it-support-labs

📌 Why This Project Matters

Building and maintaining a system from the hardware level up reinforces core IT fundamentals and provides real-world context for troubleshooting, system administration, and virtualization.

This project reflects practical skills that translate directly to entry-level IT and support roles.
