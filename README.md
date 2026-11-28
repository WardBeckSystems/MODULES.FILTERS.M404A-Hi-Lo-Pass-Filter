# M404A Hi-Lo Pass Filter · Filters

Ward-Beck Systems M404A, 1968|1. Wiki page: [M404A on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/WBSps.ca/Github.WardBeckSystems/MODULES.FILTERS.M404A-Hi-Lo-Pass-Filter/)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 25 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 1 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 5 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 37 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 4 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 6 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 48 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [1 topic](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1968 - M404A - 3.jpg](MANUALS/1968%20-%20M404A%20-%203.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Ambient temperature** | Ooto 60oc FREQUENCY RESPONSE +0 5dB from 20Hz to 20kHz (effects control at zero position) |
| **Dimensions** | 1.58W X 6.625L X 6D (depth below panel) inches EQUIVALENT INPUT NOISE -l15dBm (1OHz to 100kHz bandwidth) |
| **Weight** | 1glbs net |
| **Harmonic distortion** | Less than 0.59 from 3OHz to 20kHz (measured at +l8dBm output level) |
| **Source impedance** | ohms balanced or unbalanced |
| **Input impedance** | ohms +10% |
| **Input level** | -38dBm nominal ~20dBm maximum |
| **Load impedance** | ohms |
| **Output impedance** | ohms (150 ohms available) +1OF |
| **Output level** | +18dBm maximum |
| **Phasing** | The low terminal number of the input pair and the low terminal number of the output pair are in phase EQUALIZING CHARACTERISTICS In accordance with specified curves within +0.5dB |
| **Power requirements** | volts dc regulated from M648 or equivalent 10OmA |

<!-- /module data -->

## Photos

_Photographs of the module itself: front, back, inside, racked._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKY1VkaUNPa05mVGc/view?resourcekey=0-Qg1zVInbBPtoPVbtM4fzQw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKY1VkaUNPa05mVGc&resourcekey=0-Qg1zVInbBPtoPVbtM4fzQw" width="240" alt="1968 - M404A - wbsps - module - m404a - HP LP filter.jpg"></a><br><sub>1968|1 · wbsps - module - m404a - HP LP filter</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRUFaNkJ1eFlFWGM/view?resourcekey=0-7_5ie748VU9xGd4CE2Gu9g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRUFaNkJ1eFlFWGM&resourcekey=0-7_5ie748VU9xGd4CE2Gu9g" width="240" alt="1968 - M404A - wbsps - promo - m404a hplp filter - full.jpg"></a><br><sub>1968|1 · wbsps - promo - m404a hplp filter - full</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [1968|1 · wbsps - promo - m404a hplp filter - front_small](https://drive.google.com/file/d/0B0yR0b5T78SKanV3WVVLSE5paWs/view?resourcekey=0-EqHvnUPK9OMrE9YZyVYeWA)

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTDdTTW42eDYtTTA/view?resourcekey=0-NxKJA6AkQlBuKPD7OBrmQw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTDdTTW42eDYtTTA&resourcekey=0-NxKJA6AkQlBuKPD7OBrmQw" width="240" alt="1968 - M404A - 129-06-002 - PLACES GIVEN ANGLES MIN BEND RAD UNLESS SPECIFIED.jpg"></a><br><sub>1968|1 · 129-06-002 - PLACES GIVEN ANGLES MIN BEND RAD UNLESS SPECIFIED · <a href="SCHEMATICS/1968%20-%20M404A%20-%20129-06-002%20-%20PLACES%20GIVEN%20ANGLES%20MIN%20BEND%20RAD%20UNLESS%20SPECIFIED%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSzBabUF6Mmkybmc/view?resourcekey=0-5DH-BIwgH5IIODdkszNlxw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSzBabUF6Mmkybmc&resourcekey=0-5DH-BIwgH5IIODdkszNlxw" width="240" alt="1968 - M404A - 402-02-011 - FINE MIN BEND RAD UNLESS SPECIFIED.jpg"></a><br><sub>1968|1 · 402-02-011 - FINE MIN BEND RAD UNLESS SPECIFIED · <a href="SCHEMATICS/1968%20-%20M404A%20-%20402-02-011%20-%20FINE%20MIN%20BEND%20RAD%20UNLESS%20SPECIFIED%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKckY3Z295aHFPWDQ/view?resourcekey=0-1eUxzObRfKORBqTTmrmRXA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKckY3Z295aHFPWDQ&resourcekey=0-1eUxzObRfKORBqTTmrmRXA" width="240" alt="1968 - M404A - 402-02-012 - WATER PIPE.jpg"></a><br><sub>1968|1 · 402-02-012 - WATER PIPE · <a href="SCHEMATICS/1968%20-%20M404A%20-%20402-02-012%20-%20WATER%20PIPE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/19ILCGrWXC79Bs6LlVkQUuFfM922j6LtO/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=19ILCGrWXC79Bs6LlVkQUuFfM922j6LtO" width="240" alt="1968 - M404A - 404-02-010 - CUT NOTES.png"></a><br><sub>1968|1 · 404-02-010 - CUT NOTES · <a href="SCHEMATICS/1968%20-%20M404A%20-%20404-02-010%20-%20CUT%20NOTES%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1odFqX_ahZ8GxqXBBOedVUuv-PTwouZ47/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1odFqX_ahZ8GxqXBBOedVUuv-PTwouZ47" width="240" alt="1968 - M404A - 404-02-010 - HI-LO EQUALIZER SCHEMATIC.png"></a><br><sub>1968|1 · 404-02-010 - HI-LO EQUALIZER SCHEMATIC · <a href="SCHEMATICS/1968%20-%20M404A%20-%20404-02-010%20-%20HI-LO%20EQUALIZER%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbmxsNlRZR29IRUk/view?resourcekey=0-MJNIaNK-fXhXgA0qmwR1gQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbmxsNlRZR29IRUk&resourcekey=0-MJNIaNK-fXhXgA0qmwR1gQ" width="240" alt="1968 - M404A - 404-02-010.jpg"></a><br><sub>1968|1 · 404-02-010 · <a href="SCHEMATICS/1968%20-%20M404A%20-%20404-02-010%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1y-1PSFgNRaXMsn8SUaDursKu1JS45nUy/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1y-1PSFgNRaXMsn8SUaDursKu1JS45nUy" width="240" alt="1968 - M404A - 404-02-010.png"></a><br><sub>1968|1 · 404-02-010 · <a href="SCHEMATICS/1968%20-%20M404A%20-%20404-02-010%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it); the RTO-144 sheet agrees on 10 of 10 contacts. Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

**Inserts:** EXTERNAL PAD: PAD IN → PAD OUT

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 1 | PAD IN A | insert_send | PAD IN | medium |
| 2 | PAD IN B | insert_send | PAD IN | medium |
| 3 | PAD OUT A | insert_return | PAD OUT | medium |
| 4 | PAD OUT B | insert_return | PAD OUT | medium |
| 5 | TRANSFORMER INPUT | in | INPUT | medium |
| 6 | TRANSFORMER INPUT STRAP | strap | INPUT | medium |
| 7 | TRANSFORMER INPUT STRAP | strap | INPUT | medium |
| 8 | TRANSFORMER INPUT | in | INPUT | medium |
| 9 | INPUT SHIELD | shield | INPUT shield | medium |
| 13 | OUTPUT 1 A | out | OUTPUT 1 | medium |
| 14 | OUTPUT 1 B | out | OUTPUT 1 | medium |
| 15 | OUTPUT 2 A | out | OUTPUT 2 | medium |
| 16 | OUTPUT 2 B | out | OUTPUT 2 | medium |
| 18 | -GND / COMMON | ground |  | medium |
| 19 | CHASSIS GROUND / LAMP - | ground |  | medium |
| 20 | +24 V | power |  | medium |
| 21 | LAMP FEED STRAP | strap |  | medium |
| 22 | +48 V | power |  | medium |

**Straps:** 600Ω: P1-6 P1-7 · 150Ω: P1-5 P1-6 · PAD BYPASS: P1-3 P1-5 · LAMP 48V: P1-21 P1-22 · JMP.6.7: 6 7 · JMP.15.16 = 300Ω-&gt;620Ω-&gt;300Ω: 15 15

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMFpNRldlaXV1QTQ/view?resourcekey=0-dT-1xz6vnPNFlFlcqohAtg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMFpNRldlaXV1QTQ&resourcekey=0-dT-1xz6vnPNFlFlcqohAtg" width="240" alt="1968 - M404A - 1.jpg"></a><br><sub>1968|1 · 1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNmtHQmdCaGtIblE/view?resourcekey=0-T95Bn0eDV8ih_Ww1Ttv2_Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNmtHQmdCaGtIblE&resourcekey=0-T95Bn0eDV8ih_Ww1Ttv2_Q" width="240" alt="1968 - M404A - 10.jpg"></a><br><sub>1968|1 · 10</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRjBIWjVZOUpIekk/view?resourcekey=0-6QNUn1n5o_XeUPGz081sKw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRjBIWjVZOUpIekk&resourcekey=0-6QNUn1n5o_XeUPGz081sKw" width="240" alt="1968 - M404A - 11.jpg"></a><br><sub>1968|1 · 11</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaWtPV0gxWC1YYlE/view?resourcekey=0-yqpP6JMwKyqBLbl-YHKv4g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaWtPV0gxWC1YYlE&resourcekey=0-yqpP6JMwKyqBLbl-YHKv4g" width="240" alt="1968 - M404A - 12.jpg"></a><br><sub>1968|1 · 12</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSTI0M0hrb1VvWVk/view?resourcekey=0-wqx8ZE-O_vLb_LRgLVONng" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSTI0M0hrb1VvWVk&resourcekey=0-wqx8ZE-O_vLb_LRgLVONng" width="240" alt="1968 - M404A - 2.jpg"></a><br><sub>1968|1 · 2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWXhmbE8tdXBqMUk/view?resourcekey=0--kdGr6T5gGFaHcIzJx6sLQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWXhmbE8tdXBqMUk&resourcekey=0--kdGr6T5gGFaHcIzJx6sLQ" width="240" alt="1968 - M404A - 3.jpg"></a><br><sub>1968|1 · 3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKc1daY29OdHJRV0E/view?resourcekey=0-tDdtAAuAMZDqf3EU34bOAg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKc1daY29OdHJRV0E&resourcekey=0-tDdtAAuAMZDqf3EU34bOAg" width="240" alt="1968 - M404A - 4.jpg"></a><br><sub>1968|1 · 4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRTFodzNuNGJaWnc/view?resourcekey=0-WRZfJV5C3o55HGa--qAvhw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRTFodzNuNGJaWnc&resourcekey=0-WRZfJV5C3o55HGa--qAvhw" width="240" alt="1968 - M404A - 5.jpg"></a><br><sub>1968|1 · 5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbWE5b2o3TGpHOU0/view?resourcekey=0-KONSyU-nvJzIZbW7AtyTMg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbWE5b2o3TGpHOU0&resourcekey=0-KONSyU-nvJzIZbW7AtyTMg" width="240" alt="1968 - M404A - 6.jpg"></a><br><sub>1968|1 · 6</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOWIzaHdoQ0RnVjA/view?resourcekey=0-xAHztsjfukTrR23wFBYXHA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOWIzaHdoQ0RnVjA&resourcekey=0-xAHztsjfukTrR23wFBYXHA" width="240" alt="1968 - M404A - 7.jpg"></a><br><sub>1968|1 · 7</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa0ZtWjlWam5reHc/view?resourcekey=0-mdvNwhQd_SNKvxXzQ5_WZA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa0ZtWjlWam5reHc&resourcekey=0-mdvNwhQd_SNKvxXzQ5_WZA" width="240" alt="1968 - M404A - 8.jpg"></a><br><sub>1968|1 · 8</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNjIxM2psZ3VjV2M/view?resourcekey=0-CAcGub6TADH5rQjJ2KRibA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNjIxM2psZ3VjV2M&resourcekey=0-CAcGub6TADH5rQjJ2KRibA" width="240" alt="1968 - M404A - 9.jpg"></a><br><sub>1968|1 · 9</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbUFkbGlFOGR5cTA/view?resourcekey=0-q1WKukQbcSMyz25xPlMNlA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbUFkbGlFOGR5cTA&resourcekey=0-q1WKukQbcSMyz25xPlMNlA" width="240" alt="1968 - M404A - BM128-06-004.jpg"></a><br><sub>1968|1 · BM128-06-004</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKclhhQVA3VVhJWXc/view?resourcekey=0-UVX4hZq268R0zHGswkhVjQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKclhhQVA3VVhJWXc&resourcekey=0-UVX4hZq268R0zHGswkhVjQ" width="240" alt="1968 - M404A - P1.jpg"></a><br><sub>1968|1 · P1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMXFSa1Z3VFd1WXM/view?resourcekey=0-JdG5SLdyML5CqnX02YKdNA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMXFSa1Z3VFd1WXM&resourcekey=0-JdG5SLdyML5CqnX02YKdNA" width="240" alt="1968 - M404A - P10.jpg"></a><br><sub>1968|1 · P10</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdUxRNmtSY0dDS0U/view?resourcekey=0-hOiz_4ueBT-U2bfW8nlyrA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdUxRNmtSY0dDS0U&resourcekey=0-hOiz_4ueBT-U2bfW8nlyrA" width="240" alt="1968 - M404A - P11.jpg"></a><br><sub>1968|1 · P11</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRjlvaU5oclhrLVk/view?resourcekey=0-36DU-UCLTyI0PO3-tWZNQA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRjlvaU5oclhrLVk&resourcekey=0-36DU-UCLTyI0PO3-tWZNQA" width="240" alt="1968 - M404A - P12.jpg"></a><br><sub>1968|1 · P12</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRTBncDl5MkNZVUU/view?resourcekey=0-nJ-0ChWFrRI7LavLVDDb4w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRTBncDl5MkNZVUU&resourcekey=0-nJ-0ChWFrRI7LavLVDDb4w" width="240" alt="1968 - M404A - P13.jpg"></a><br><sub>1968|1 · P13</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT3ZhLUF3WGg2cDg/view?resourcekey=0-4u_d7crqHcBaUFOxLf463g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT3ZhLUF3WGg2cDg&resourcekey=0-4u_d7crqHcBaUFOxLf463g" width="240" alt="1968 - M404A - P14.jpg"></a><br><sub>1968|1 · P14</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcVFtYTR1SEVxMlk/view?resourcekey=0-j9KQtcHUnZRKZw-htK83-Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcVFtYTR1SEVxMlk&resourcekey=0-j9KQtcHUnZRKZw-htK83-Q" width="240" alt="1968 - M404A - P15.jpg"></a><br><sub>1968|1 · P15</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKczdSRFdjZEk3ZHM/view?resourcekey=0-4iV5uLe0zRxwXLX_nfCd_Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKczdSRFdjZEk3ZHM&resourcekey=0-4iV5uLe0zRxwXLX_nfCd_Q" width="240" alt="1968 - M404A - P16.jpg"></a><br><sub>1968|1 · P16</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOGVMU2VIblAtX3c/view?resourcekey=0-mIUot6sGgXTQs4mKZRq77A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOGVMU2VIblAtX3c&resourcekey=0-mIUot6sGgXTQs4mKZRq77A" width="240" alt="1968 - M404A - P17.jpg"></a><br><sub>1968|1 · P17</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZ3ZjemMxeDBDWjQ/view?resourcekey=0-UjvGXwAifw5qluEm8GrzNA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZ3ZjemMxeDBDWjQ&resourcekey=0-UjvGXwAifw5qluEm8GrzNA" width="240" alt="1968 - M404A - P18.jpg"></a><br><sub>1968|1 · P18</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS0pyNGdXbGYwREk/view?resourcekey=0-iuWA0NfQTeVBqAsbJJD_Xw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS0pyNGdXbGYwREk&resourcekey=0-iuWA0NfQTeVBqAsbJJD_Xw" width="240" alt="1968 - M404A - P2.jpg"></a><br><sub>1968|1 · P2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbGtNdFZCOWw4U2c/view?resourcekey=0-x_WFHzPmvjkASszf0hgZgQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbGtNdFZCOWw4U2c&resourcekey=0-x_WFHzPmvjkASszf0hgZgQ" width="240" alt="1968 - M404A - P3.jpg"></a><br><sub>1968|1 · P3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTHNLZUt1NGxPbUk/view?resourcekey=0-1LsdwvXbEAlWAFxpcqFNcA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTHNLZUt1NGxPbUk&resourcekey=0-1LsdwvXbEAlWAFxpcqFNcA" width="240" alt="1968 - M404A - P4.jpg"></a><br><sub>1968|1 · P4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYTdhbVFQVVdiNUU/view?resourcekey=0-8fbB7x50eJL2SJCcq073GQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYTdhbVFQVVdiNUU&resourcekey=0-8fbB7x50eJL2SJCcq073GQ" width="240" alt="1968 - M404A - P5.jpg"></a><br><sub>1968|1 · P5</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKem1PNEtkNWk5QlE/view?resourcekey=0-bsw1dgW7ghYWkg0yyqfLOw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKem1PNEtkNWk5QlE&resourcekey=0-bsw1dgW7ghYWkg0yyqfLOw" width="240" alt="1968 - M404A - P6.jpg"></a><br><sub>1968|1 · P6</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOEJIT1ZPMWl4ZVU/view?resourcekey=0-wREw-TsBSQnu3ZkHuxvWHQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOEJIT1ZPMWl4ZVU&resourcekey=0-wREw-TsBSQnu3ZkHuxvWHQ" width="240" alt="1968 - M404A - P7.jpg"></a><br><sub>1968|1 · P7</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTkJLU2xGZWxkZzA/view?resourcekey=0-yzNJHiWkmhvvHUKYcNX20w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTkJLU2xGZWxkZzA&resourcekey=0-yzNJHiWkmhvvHUKYcNX20w" width="240" alt="1968 - M404A - P8.jpg"></a><br><sub>1968|1 · P8</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKanB1MFhHeHJzZnc/view?resourcekey=0-CUcxiI8S2qLXGDNNecrILQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKanB1MFhHeHJzZnc&resourcekey=0-CUcxiI8S2qLXGDNNecrILQ" width="240" alt="1968 - M404A - P9.jpg"></a><br><sub>1968|1 · P9</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKXzhYX016VFU5Y00/view?resourcekey=0-narIYIxor8LbrJfXjOPb3Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKXzhYX016VFU5Y00&resourcekey=0-narIYIxor8LbrJfXjOPb3Q" width="240" alt="1968 - M404A - Ward Beck Systems M404A 2.jpg"></a><br><sub>1968|1 · Ward Beck Systems M404A 2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQlp3RDFFWG53b0k/view?resourcekey=0-i4JL1-l1mw-UkM1aMqfavA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQlp3RDFFWG53b0k&resourcekey=0-i4JL1-l1mw-UkM1aMqfavA" width="240" alt="1968 - M404A - Ward Beck Systems M404A.jpg"></a><br><sub>1968|1 · Ward Beck Systems M404A</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcndoSmpUQW9oWFk/view?resourcekey=0-aW2ucfC-KK8zb7zUE7W8_Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcndoSmpUQW9oWFk&resourcekey=0-aW2ucfC-KK8zb7zUE7W8_Q" width="240" alt="1968 - M404A - wbsps - module - m404a hplp filter - front.jpg"></a><br><sub>1968|1 · wbsps - module - m404a hplp filter - front</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcm1pU1Q3OTJDbGc/view?resourcekey=0-PMblouHqnD80xjAN6ytEKA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcm1pU1Q3OTJDbGc&resourcekey=0-PMblouHqnD80xjAN6ytEKA" width="240" alt="1968 - M404A - wbsps - promo - m404a hplp filter - front.jpg"></a><br><sub>1968|1 · wbsps - promo - m404a hplp filter - front</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B9I0nu1MPkm6Z2lLNEZYQ3ZoUDQ/view?resourcekey=0-5DX4cvFxAiR-D4EmHB4zQg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B9I0nu1MPkm6Z2lLNEZYQ3ZoUDQ&resourcekey=0-5DX4cvFxAiR-D4EmHB4zQg" width="240" alt="1975 - M404A - PRICE LIST - PRICE LIST.jpg"></a><br><sub>1975|8 · PRICE LIST - PRICE LIST</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1968 - M404A - 402-02-011 - FINE MIN BEND RAD UNLESS SPECIFIED.kicad_sch](KICAD/1968%20-%20M404A%20-%20402-02-011%20-%20FINE%20MIN%20BEND%20RAD%20UNLESS%20SPECIFIED.kicad_sch)
- [1968 - M404A - 402-02-012 - WATER PIPE.kicad_sch](KICAD/1968%20-%20M404A%20-%20402-02-012%20-%20WATER%20PIPE.kicad_sch)
- [1968 - M404A - 404-02-010 - CUT NOTES.kicad_sch](KICAD/1968%20-%20M404A%20-%20404-02-010%20-%20CUT%20NOTES.kicad_sch)
- [1968 - M404A - 404-02-010 - HI-LO EQUALIZER SCHEMATIC.kicad_sch](KICAD/1968%20-%20M404A%20-%20404-02-010%20-%20HI-LO%20EQUALIZER%20SCHEMATIC.kicad_sch)
- [1968 - M404A - 404-02-010.kicad_sch](KICAD/1968%20-%20M404A%20-%20404-02-010.kicad_sch)
- [M404A.kicad_sym](KICAD/M404A.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
