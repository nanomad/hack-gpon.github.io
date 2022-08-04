---
title: VSOL V2801F
has_children: true
parent: ONT
---

# VSOL V2801F

## Hardware Specifications

|          |               |
|----------|---------------|
| Vendor   | VSOL        |
| Model    |  V2801F      |
| Alias | |
| Chipset  | Realtek RTL9601CI |
| Flash | 8 MB |
| RAM | 64 MB |
| System | Linux (Luna SDK) |
| HSGMII | No |
| Optics | SC/APC |
| IP address |   |
| Web Gui | ✅ |
| SSH | ✅ |
| Form Factor | miniONT SFP |

### Interchangeable firmware with


- [ODI DFP-34X-C2C](ont-ODI-DFP-34X-C2C)
- [VSOL V2801F](ont-vsol-V2801F)
- [TWCGPON657](ont-TWCGPON657)
- [UFiber UF-Instant](ont-UFiber-UF-Instant) can be used as universal GPON stick with V2801F rootfs, but only with stock UF kernel (4.3.1) - needed for Laser controller
- [DFP-34X-2C2](ont-DFP-34X-2C2)
- [CarlitoxxPro CPGOS03-0490 v2](ont-CarlitoxxPro-CPGOS03-0490-v2)

### List of software version
### List of partition
### List of firmware and files
## Miscellaneous Links

- [Hacking RTL960x](https://github.com/Anime4000/RTL960x)

## Bugs

VLAN swap issue (MEID 171), auto-sensing mode to switch between SGMII/HiSGMII

use VID/VLAN from command "omcicli mib get 84" via telnet to bring up PPPoE
