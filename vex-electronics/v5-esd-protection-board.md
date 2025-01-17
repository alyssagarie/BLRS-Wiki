---
description: An ESD Protection board for the V5
---

# V5 ESD Protection Board

This is an ESD protection board for the V5 Brain to help prevent dead ports or dead motors. **This solution is not competition legal but can be very easily removed before a competition.** This board sits in-between a port on the [brain](vex-electronics/vex-v5-brain/) and a [motor](vex-electronics/motors.md). Technical information about RS-485 Bus Protection can be seen here:

{% file src="../.gitbook/assets/ti-iec-esd-rs-485-bus-protection.pdf" %}

![The schematic of the board](../.gitbook/assets/image-2-.png)

## Specs

Everything you need for a functioning board is listed here as well as OSH Park link to buy our custom board:

| Vendor | Qty | MPN | Vendor Part \# | Description | Unit Cost | Ext |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Digi-Key | 1 | [CDSOT23-SM712](https://www.digikey.com/product-detail/en/bourns-inc/CDSOT23-SM712/CDSOT23-SM712CT-ND/1630607) | CDSOT23-SM712CT-ND | TVS DIODE | $1.53 | $1.53 |
| Digi-Key | 2 | [A-2004-3-4-LP-N-R](https://www.digikey.com/product-detail/en/assmann-wsw-components/A-2004-3-4-LP-N-R/AE10381-ND/2183632) | AE10381-ND | RJ9/11 Jack- 4P4C unshielded | $0.56 | $1.12 |
| OshPark | 1 | [29IVKKai](https://oshpark.com/shared_projects/JWIVZKsD) |  | PCB \(Set of 3\) | $1.27 | $1.27 |
| Total |  |  |  |  | $1.31 | $3.92 |

## Installation

![1. The first step should be to install the TVS Diode, which should be soldered onto the D1 pads.](../.gitbook/assets/image%20%2837%29.png)

![2. The second and final step should be to drop in and solder jacks into the J1 and J2 Section of the board. ](../.gitbook/assets/image%20%2838%29.png)

{% hint style="info" %}
To download the board file, please visit the OSHPark page.
{% endhint %}

### Teams Contributed to this Article:

* [BLRS](https://purduesigbots.com/) \(Purdue SIGBots\)

Special thanks to Jess from team EZ for helping test out the V2 iteration of the boards.

Original board design credit goes to Ritwik Pandey, a BLRS alumni.

