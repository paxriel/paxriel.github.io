# Kerbal Space Program - Paxriel’s Mission Files

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
