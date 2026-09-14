<div align="center">

# Longhorn eVTOL

**A piloted eVTOL, built by students at Texas.**

*A student organization at The University of Texas at Austin designing, building, and testing a single-seat electric octocopter.*

[![Regulatory basis](https://img.shields.io/badge/FAA-Part%20103-bf5700.svg)](https://www.law.cornell.edu/cfr/text/14/part-103)
[![Configuration](https://img.shields.io/badge/config-coaxial%20X8-555.svg)](https://github.com/LonghornEVTOL/longhorn-evtol/blob/main/docs/vehicle/baseline.md)
[![University](https://img.shields.io/badge/university-UT%20Austin-bf5700.svg)](https://utexas.edu)

[Website](https://longhorn-evtol.vercel.app) · [Vehicle baseline](https://github.com/LonghornEVTOL/longhorn-evtol/blob/main/docs/vehicle/baseline.md) · [Join the team](#join-us)

</div>

---

## Who we are

Longhorn eVTOL gives UT students hands-on experience across the whole life of an aircraft: requirements, design, analysis, fabrication, integration, and flight test. We are working toward a **single-occupant seated multirotor** capable of safe, low-altitude piloted flight.

Development is phased:

```
Subscale unmanned      1/3 scale coaxial X8, 6S, 17 in props, 9.6 kg  ← building now
Full-scale tethered    Full vehicle, no occupant, restrained then tethered
Piloted                Low altitude, day VFR, off campus, after Article X sign-off
```

---

## Current phase

An unmanned **1/3-scale coaxial octocopter** that mirrors the full-scale vehicle: same layout, 4-pack power architecture, DroneCAN motor bus, safety monitor, and recovery system, with a 2.7 kg ballast in the pilot's seat. [Read the design](https://github.com/LonghornEVTOL/longhorn-evtol/blob/main/docs/vehicle/subscale-demonstrator.md).

---

## The vehicle

Piloted flight is planned under **14 CFR Part 103**: under 254 lb empty weight with batteries, one occupant, daylight, away from congested areas. 

| | Baseline v1 (preliminary) |
| --- | --- |
| Configuration | Coaxial octocopter, 4 folding arms, 8 rotors |
| Propulsion | 8 × Hobbywing X13 G2 (motor, ESC, 56 in prop), 60 kgf each |
| Thrust-to-weight | 2.19 with a 160 lb pilot, 1.92 with one motor out |
| Battery | 4 independent 18S5P packs of Molicel P50B cells, 6.5 kWh |
| Empty weight | 250 lb with parachute, 229 lb without |
| Flight control | Pixhawk 6X Pro on a real-time OS |
| Safety monitor | Independent FPGA with its own power and reset |
| Recovery | Galaxy GRS 3 270 ballistic parachute |

Full sizing, parts, sources, and open risks: [`docs/vehicle/baseline.md`](https://github.com/LonghornEVTOL/longhorn-evtol/blob/main/docs/vehicle/baseline.md).

---

## Repositories

| Repository | Description |
| --- | --- |
| [`longhorn-evtol`](https://github.com/LonghornEVTOL/longhorn-evtol) | Main project repo: vehicle baseline, team folders, projects, and docs |
| [`website`](https://github.com/LonghornEVTOL/website) | Source for [longhorn-evtol.vercel.app](https://longhorn-evtol.vercel.app) |

---

## Teams

**Mechanical Design** · **Electrical and Power** · **Software and Avionics** · **Manufacturing and Operations** · **Flight Test and Range** · **Systems Engineering** · **Business and Outreach**

Current work ranges from a 6S buck converter board and a thrust stand data logger to a custom 18S ESC, the FPGA safety monitor, and the full-scale mass budget. See the [project list](https://github.com/LonghornEVTOL/longhorn-evtol#projects).

---

## Join us

Open to UT Austin students of any major and any experience level. **No dues, ever.** We recruit every fall and spring through a short application and a 20 minute interview, scored on interest, commitment, and contribution. Admitted members finish safety onboarding and three work sessions to join a team and get shop access.

**[Apply at longhorn-evtol.vercel.app/apply](https://longhorn-evtol.vercel.app/apply)**

---

<div align="center">

*Built at UT Austin. Flown only when it's safe.*

<sub>Longhorn eVTOL is a student organization. Its views and activities are its own and do not represent The University of Texas at Austin.</sub>

</div>
