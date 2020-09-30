# Kerbal Space Program - Paxriel's Mission Files

## Prefixes

| Letter | Definition |
|--------|------------|
| A | Ship |
| B | Plane |
| C | Lander |
| D | Rovers |
| E | Base |
| F | Station |
| G | Lab |
| H | Scanners |
| I | EVA |
| J | Flags |
| P | Probe (Short Term) |
| R | Relay |
| N.A. | Debris |

| Letter Groups | Definition |
|---------------|------------|
| A-D | Temporary crafts |
| E-G | Permenant structures |
| I-J | Other objects |
| P / R | Permenant structures (Legacy Naming) |

## Planet / Orbital Object Codes (POOC)

| Code | Object | Type |
|------|--------|------|
| BO | Bop | Moon |
| DU | Duna | Planet |
| DR | Dres | Planet |
| EV | Eve | Planet |
| GI | Gilly | Moon |
| IK | Ike | Moon |
| JO | Jool | Planet |
| K | Kerbin (Legacy) | Planet |
| KB | Kerbin | Planet |
| KO | Kerbol | Star |
| LA | Laythe | Moon |
| M | Mun (Legacy) | Moon |
| MH | Moho | Planet |
| MM | Minmus | Moon |
| MU | Mun | Moon |
| PO | Pol | Moon |
| TY | Tylo | Moon |
| VA | Vall | Moon |

## Naming Schema

| Prefix | Schema | Hyphen after Prefix | Capacity |
|--------|--------|---------------------|----------|
| A-B | Suffix YYYY, where YYYY is the launch number, starting from 0001 up to 9999. | No | 9999 |
| C | Suffix XXXX-YY, where XXXX is the launch number of the parent craft, and YY is the numerical code for the craft starting from 01 to 09. | No | 9 per parent |
| D / P / R | Suffix XXYYY, where XX is the POOC and YYY is the order of the craft, starting from 001 up to 999. | Yes | 999 per POOC |
| E-H | Suffix XX-YYY-ZZZ, where XX is the POOC, YY is the 3-letter code for the station, and ZZZ is the numerical code for the part of the station, starting from 001 up to 999. ZZZ is optional for the main control craft within the station. If a lab and a station are combined, the station takes prioity over the lab. | Yes | 999 per station |
| I-J | No naming schema. | | |

All dockable objects have a additional -DX at the end, where X represents the size of the docking port.
If there are multiple types of docking ports within the object, it is represented by multiple numbers at the back, in ascending order.
For instance, -D13 would signify that the object has docking ports of type 1 and 3.

| Number | Size |
|--------|------|
| 1 | Small |
| 2 | Medium |
| 3 | Large |

## Base Codes

| Code | Base | Status | Docking |
|------|------|--------|---------|
| HAL | Minmus "HAL" Science Transfer Base | Landed at Greater Flats on Minmus | |

## Station Codes

The command stations on Moho and Eve have RTGs, solar panels and cooling systems, while the command stations on the remaining planets only have RTGs and solar panels.

| Code | Station | Status | Docking |
|------|---------|--------|---------|
| KPS | Kerbin Prototype Station | Controlled Flight into Kerbin | D2 |
| ETS | Moho "Ember Twin" Command Station | Planned | D23 |
| ATS | Eve "Ash Twin" Command Station | Controlled Flight into Kerbin | D2 |
| AT2 | Eve "Ash Twin" Command Station v2 | Planned | D23 |
| DCS | Duna Command Station | Controlled Flight into Kerbin | D2 |
| DC2 | Duna Command Station v2 | Planned | D23 |
| PCS | Dres "Pluto" Command Station | In Kerbin Orbit, deorbit planned | D2 |
| PC2 | Dres "Pluto" Command Station v2 | Planned | D23 |

## Lab Codes

| Code | Lab | Status | Docking |
|------|-----|--------|---------|
| KSL | Kerbin Small Lab | In Kerbin Orbit | D1 |
| MSL | Mun Small Lab | In Mun Orbit | D1 |
| MCL | Minmus Cool Lab | In Minmus Orbit | D2 |
| KPL | Kerbin Prototype Lab | Equivalent to F-KB-KPS | D2 |
| ETL | Moho "Ember Twin" Lab | Equivalent to F-MH-MCS | D2 |
| ATL | Eve "Ash Twin" Lab | Equivalent to F-EV-ATS | D2 |
| AT2 | Eve "Ash Twin" Lab v2 | Equivalent to F-EV-AT2 | D2 |
| DRL | Duna Research Lab | Equivalent to F-DU-DCS | D2 |
| DR2 | Duna Research Lab v2 | Equivalent to F-DU-DC2 | D2 |
| PRL | Dres "Pluto" Research Lab | Equivalent to F-DR-PCS | D2 |
| PR2 | Dres "Pluto" Research Lab v2 | Equivalent to F-DR-PCS | D2 |

## Scanner Codes

| Code | Station | Status | Docking |
|------|---------|--------|---------|
| MUS | Mun Survey Station | In Mun Orbit | |
| MMS | Minmus Survey Station | In Minmus Orbit | |
| KES | Kerbin "Earhart" Station | In Kerbin Orbit | |
| KAT | Kerbin Asteroid Detector | Planned | |
| KOS | Kerbin Observation Satellite | Controlled Flight into Kerbin | |
| EAT | Eve Asteroid Detector | Planned | |
| DAT | Duna Asteroid Detector | Planned | |
| PAT | Dres "Pluto" Asteroid Detector | Planned | |

## Launched Temporary Crafts

### Ships

| Craft | Status | Docking |
|-------|--------|---------|
| A0001 | Not Recorded | |
| A0002 | Not Recorded | |
| A0003 | Not Recorded | |
| A0004 | Not Recorded | |
| A0005 | Not Recorded | |
| A0006 | Not Recorded | |
| A0007 | Not Recorded | |
| A0008 | Not Recorded | |
| A0009 | Not Recorded | |
| A0010 | Not Recorded | |
| A0011 | Not Recorded | |
| A0012 | Landed at Kerbin | |
| A0013 | Landed at Kerbin | |
| A0014 | Landed at Kerbin | |
| A0015 | Landed at Kerbin | |
| A0016 | Landed at Kerbin | |
| A0017 | Landed at Kerbin | |
| A0018 | Controlled flight into Mun | |
| A0019 | Out of fuel | |
| A0020 | Landed at Kerbin \[Reusable model\] | |
| A0021 | Controlled flight into Minmus | |
| A0022 | Out of fuel | |
| A0023 | Controlled flight into Minmus | |
| A0024 | Converted to E-MM-HAL \[Reusable model\] | |
| A0025 | Landed at Kerbin | D2 |
| A0026 | Landed at Kerbin | D2 |
| A0027 | Planned | D2 |

### Planes

| Craft | Flights | Purpose | Docking |
|-------|---------|---------|---------|
| B0001 | 1 | Simple Prototype | |
| B0002 | 1 | High range (24000 m/s), slow speed travel (200 m/s cruising speed) | |

### Landers

| Craft | Status | Docking |
|-------|--------|---------|
| C0014-01 | Out of fuel | D1 |
| C0015-01 | Out of fuel | D1 |
| C0016-01 | Controlled flight into Minmus | |
| C0018-01 | Controlled flight into Mun | |
| C0024-01 | Equivalent to A0024 | |

### Probes

| Craft | Status |  
|-------|--------|
| P-MU001 | Landed on Kerbin |
| P-MU002 | Landed on Kerbin |
| P-MU003 | Out of fuel |

## Launched Permenant Crafts

### Relays (000x Series)

The 000x series relays are short range relays, only capable of transmitting data within the Kerbin system.
All the relays on each planet are 90 degrees to the plane of the other relays.
This series is only used within the Kerbin system. It is superseded by the 001x Series relays and are terminated in Event 1.

| Craft | Status |
|-------|--------|
| R-KB001 | Terminated in Event 1 |
| R-KB002 | Terminated in Event 1 |
| R-KB003 | Terminated in Event 1 |
| R-MU001 | Terminated in Event 1 |
| R-MU002 | Terminated in Event 1 |
| R-MU003 | Terminated in Event 1 |
| R-MM001 | Terminated in Event 1 |
| R-MM002 | Terminated in Event 1 |
| R-MM003 | Terminated in Event 1 |

### Relays (001x Series)

The 001x series relays are long range relays, capable of transmitting large quantities of data.
For planets, each would have 3 relay groups, with each group having 90 degrees of rotation from the plane of other groups. Within each group, all the relays are 45 degrees to each other.
For moons, the relay system would be similar to that of the 000x series, with all the relays being at 90 degrees to the plane of other relays.
This series is only used within the Kerbin system and is now superseded by the 002x and 003x series.

| Craft | Status |
|-------|--------|
| R-MU010 | Orbiting Mun \[Reusable model\] |
| R-MU011 | Orbiting Mun |
| R-MU012 | Orbiting Mun |
| R-MM010 | Orbiting Minmus |
| R-MM011 | Orbiting Minmus |
| R-MM012 | Orbiting Minmus |
| R-KB010 | Orbiting Kerbin |
| R-KB011 | Orbiting Kerbin |
| R-KB012 | Orbiting Kerbin |
| R-KB013 | Orbiting Kerbin |
| R-KB014 | Orbiting Kerbin |
| R-KB015 | Orbiting Kerbin |
| R-KB016 | Orbiting Kerbin |
| R-KB017 | Orbiting Kerbin |
| R-KB018 | Orbiting Kerbin |

### Relays (002x Series)

The 002x series relays has the same communication system as the 001x relays. However, they have no solar panels, and instead consist of RTGs and upgraded batteries, allowing them to function in places without sufficient sunlight.
Its deployment system is exactly the same as that of the 001x relays.
This series is deployed to all moons and satellites within the Duna, Dres, Jool and Eeloo systems.

| Craft | Status |
|-------|--------|
| R-DR020 | Orbiting Kerbin |
| R-DR021 | Orbiting Kerbin |
| R-DR022 | Orbiting Kerbin |
| R-DR023 | Orbiting Kerbin |
| R-DR024 | Orbiting Kerbin |
| R-DR025 | Orbiting Kerbin |
| R-DR026 | Orbiting Kerbin |
| R-DR027 | Orbiting Kerbin |
| R-DR028 | Orbiting Kerbin |

### Relays (003x Series)

The 002x series relays would be similar to the 002x relays, except it also contains cooling systems to allow it to survive in high temperature environments.
Its deployment system is exactly the same as that of the 001x relays.
This series is deployed to Moho and Eve due to its proximity to Kerbol.

| Craft | Status |
|-------|--------|
