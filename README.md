# Bolt Buddy

**An igent device that rides in a vehicle: it reads the vehicle's own data and the
ride-hail platforms the driver works with, speaks the igent.me contract, and never controls
the vehicle.**

| | |
|---|---|
| **Status** | Procurement in process. |
| **Class** | the ride-along igent; siblings: the sensor head and the silent drone |
| **Reference vehicle** | a 2019 Chevrolet Trax, standing in for a Bolt EV |
| **Reference hardware** | a Raspberry Pi Zero 2 W class computer and an OBD-II adapter, powered from a switched 12 V circuit with a low-voltage cutoff |
| **Standards to map** | COVESA Vehicle Signal Specification; Android Automotive Vehicle HAL; SAE J1979 (OBD-II); ISO 15118; ride-hail driver interfaces |
| **Contract** | [igent.me contract](https://github.com/toneron2/igent), version 0 |
| **Licence** | All rights reserved; patent pending. See [`LICENSE`](LICENSE) |

## What it does

The vehicle already carries governed state: speed, state of charge, cell voltages, 12 V
health, tyre pressure. Bolt Buddy reads that state rather than sensing it, sends it to the
portal as stream-1 data, and shows the driver the status line: one line of icon and text
for each agent action, with the verdict that allowed it. It reads; it never writes to the
vehicle.

## Next

The standards note: each signal the reference hardware reads, mapped to the Vehicle Signal
Specification. Then 24 hours of heartbeat from the reference vehicle on the bench. The
public form after that follows the shape of [RWS](https://github.com/toneron2/RWS): a
specification, servers that do the work, a scripted demonstration.

## Contact

Tony Slosar · TODOMODO.IO AGENCY LLC · anthonyslosar@gmail.com · [t.me/toneron2](https://t.me/toneron2) · [slosars.me](https://slosars.me)
