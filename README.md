# PC Build - MAIN-PC (Windows 11 Pro Hyper-V Host)

This repository documents the research, assembly, configuration, and validation of my primary Windows 11 desktop (`MAIN-PC`) built for virtualization and IT lab work.

## Project Objectives
- Build a reliable daily-use workstation.
- Prioritize virtualization performance for Hyper-V labs.
- Keep the platform upgrade-friendly.
- Reinforce hardware and troubleshooting fundamentals aligned with entry-level IT roles.

## System Role
`MAIN-PC` is used as:
- Primary workstation
- Hyper-V host for multi-OS labs
- Build/test platform for Windows Server and Linux administration practice

## Sanitized Specifications
| Component | Details |
|---|---|
| Operating System | Windows 11 Pro |
| CPU | AMD Ryzen 7 3700X |
| GPU | NVIDIA RTX 3070 |
| Memory | 32 GB RAM |
| Storage | NVMe 1 TB + NVMe 500 GB |
| Virtualization | Hyper-V |
| Hostname | MAIN-PC |

Note: Serial numbers and unique identifiers are intentionally excluded.

## Planning and Research
Tools used:
- PCPartPicker (compatibility and power planning)
- Vendor documentation (BIOS, chipset, drivers)
- Build-reference videos (assembly sequence)
- CompTIA A+ study material (hardware concepts and best practices)

Compatibility checks completed:
- CPU and motherboard support
- RAM type and speed support
- Power headroom
- Storage interface compatibility
- Case fit and airflow considerations

## Storage Strategy
| Drive | Purpose |
|---|---|
| NVMe 1 TB | Host OS, core apps, daily-use data |
| NVMe 500 GB | VM and lab workloads |

Why this matters:
- Better workload isolation
- Cleaner backup strategy
- Easier troubleshooting when host and VM performance differ

## Build and Configuration Workflow
1. Assemble core components (CPU, RAM, NVMe, board, PSU, GPU).
2. Confirm POST and hardware detection.
3. Configure BIOS/UEFI:
   - verify CPU/RAM/NVMe detection
   - enable virtualization extensions
   - verify boot order
4. Install Windows 11 Pro.
5. Install chipset/GPU/system drivers.
6. Apply Windows updates.
7. Enable Hyper-V and validate VM creation.

## Validation Completed
- Stable boot and successful POST
- Device Manager health checks
- Temperature and stability checks under load
- Storage health checks
- Hyper-V VM creation and operation validation

## Current Lab Usage
`MAIN-PC` currently supports:
- Windows Server lab workloads
- Linux VM workloads (Ubuntu, Linux Mint, Kali, RHEL, Elementary)
- Security and troubleshooting practice in isolated virtual environments

## Skills Demonstrated
- Hardware compatibility and build planning
- BIOS/firmware and virtualization configuration
- Endpoint provisioning and validation
- Performance-aware storage design
- Practical documentation and incident prevention mindset

## Lessons Learned
- Planning compatibility up front avoids expensive rework.
- Storage layout decisions directly affect lab performance and supportability.
- BIOS settings are critical for successful virtualization workflows.
- Structured post-build validation improves long-term reliability.

## Future Improvements
- Expand VM-dedicated storage as lab scope grows
- Add host monitoring/logging baseline
- Strengthen backup and recovery testing for VM workloads

## Related Repositories
- Home Lab Overview: https://github.com/dallasm92/home-lab-overview
- IT Support Labs: https://github.com/dallasm92/it-support-labs
- AD Lab (Windows Server 2022): https://github.com/dallasm92/ad-lab-windows-server-2022

## Why This Project Matters
Building and validating this system end-to-end demonstrates practical ownership of an IT endpoint platform, from hardware planning through operational readiness.
