# M473A Submaster Module · Summing

Ward-Beck Systems M473A, 1977|10. Wiki page: [M473A on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M473A.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 39 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 6 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 11 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 201 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 2 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 13 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 36 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [6 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1977 - M473A - P05 - 1-1.jpg](MANUALS/1977%20-%20M473A%20-%20P05%20-%201-1.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** | dB ±0.5 dB (with fader in 15 dB &quot;in-hand&quot; position). |
| **Frequency responses** | 40.25 dB from 20 Hz to 20 klz. 80 dB below +8 dBm nominal output Teve (20 Hz to 20 kHz) |
| **Harmonic distortion** | Less than 0.258 from 30 Hz to 20 kHz +28 dBm output or Tess. (Typically Tess than 0.05% across mOs to f bandwidth. |
| **Source impedance** |  |
| &nbsp;&nbsp;Summing | 30,000 ohms balanced |
| **Input impedance** | Output Impedances: |
| **Summing** | Less than ohms At 8-1094 output and DIRECT output, pins 15/5 Less than 100 ohms At MONITOR outputs pins 16/T &amp;nd 17/U: 150 ohms |
| **Load impedance** | 600 ohms balanced (at insertion point and DIRECT output) |
| **Output level** | dBm nomina ] at insert point +8 dBm nomina 1 at DIRECT output 15/5 +30 dBm max mum t DIRECT output 15/5 |
| **Phasing** | Input and output termina ]s designated by numbers are in phase. |
| **Power requirements** | +25 vo ]ts dc 60 ma nomina] 200 MAma ximum; |
| **Ambient temperature** | to 60 degrees Celsius 6 &quot; wide 7&quot; high deep (41 X 178 X 165 Mm5&quot; MTIIT MM |

## Circuit description

From [1977 - M473A - Submaster Module (2).pdf](MANUALS/1977%20-%20M473A%20-%20Submaster%20Module%20(2).pdf) pages 3-8 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

3 Parts List 3-1 to 3-4

4 Appe ndl lt 8-109 Description 8-109-1-1 to ·3 8-109 Parts List 8-109-2_ 1 to -S

5 Drawings M473A Front Panel A473-04-006 M473A Functional 84 73-0 1-002 H473A Schematic 8473·02-002 M4 73A Component Layout 8473· 06-002 M4 73A Connector Layout A473 -04-00S 8·109A s c beaa t tc 88-109-02-00 2 8-109A Component Layout 88 -109-06 -002 8-1D 9G Schematic 88·1 09-02· 008 8·1096 Co.ponent LayOut 88-109 -06 -008

&quot; A/f UAl ISSUE 17

**WARRANTY**

defective. ate r i a l sand wor k• • nshi p fora period of one year fro. de t e of sh lp. ent.

Ward·B eck Sys te.s will repair or rep lace. It Its option, without charge. all said products or p.rts thereof which. upon factory inspection. prove t o be defective during the warranty period provided that:

a) Original serial nUlllbers Ire intact and ha...e not been tampered with.

b) The purc hese r shall return any eQuipmen l or parts thereof toWard · Beck Sy s te ~s only after obtaining prior authorization and shipping instructions from the factory. War dBeck Systems reserves the right t o Inspector rep air on the purchase r's premises.

c) The purchaser I ssu ~es the obligation of.11 expenses incurred In connection with shipping andre turning such goods, once authorizatIon has been obtained.

This warranty does not cover items nor.all y considered e~ penda ble such as fuses and lamps.

This warranty does not cover da.. ages caused by et s ose, accident. neglect. unauthorized.l t er.ti on. repair by unauthorized personnel, or du•• ge clus ed by act of God, wlr or civil ins ur rec t ion.

In noe vent sh. 11 Wlrd-Beck Sys t e.s be liable fur co nse

of final de t e r.i nl t ion IS to the applicability oft his warrlnty.

Ward - Beck Sys t e.s rese r...es the r; ght, I tIny ti.e. t o. ake chlnges In equiplllen t. component specifications and design

.s ~ IY be warrln ted by progress int ec hnol ogy.

The warranty set forth herein is in lieu of all other war

r-en t te s, express or implied. including the w. r r l nt les of Merch antability and Fitness.

**TECHNICAL DATA**

Gain; 8 dB ±0.5 dB (wit h fader in 15 dB &quot;in hand &quot; position).

Frequency Response: ±0.25 dB from 20 Hz t o 20 kHz. Noise: 80 dB below +8 dBm nominal output level (20 Hz t o 20 kHz).

Harmonic Distortion: Less than 0.251 from 30 Hz t o 20 kHz at +28 dBm output or less, (Typical l y less than 0.05 ~ across most of band.... i dth. J Source Impedance: Summing: 30,000 ohms. balanced. Input Impedance; Summing: Less than 5 ohms. Out put Impedance s: At 8-109A output and DIRECT output, pins 15/ 5: Less than 100 ohms.

At MONITOR out puts, pins 16/T and l7 /li: 150 ohms.

Load Impedance: 600 ohms. balanced (a t insertion point and DIRECT ou tput), Output Level: o dBm nominal at insert point. +8 dBm nominal a t DIRECT out put 15{S.

+30 dBm maximum a t DIRECT output 15/ 5.

Phasing: Input and output terminal s designated by numbers are i n phase.

Power Requirements: ±25 volts de. 60 mA nominal, 200 mA maximum.

Ambient Temperature: 0 t o 60 degrees Celsius.

Dimensions: 1.6&quot;.... ide X 7&quot; high X 6.5 &quot; deep

(41 mm X 178 mm X 165 mm).

The M4 73A i s designed to accept combined o r II I)(ed feeds f r olll previously assigned mixing channel inputs. The assigned mi x1ng channel inputs are amplified and routed tot he appropriate points within the console sys te•.

Input and Su.mi ng Amplifier The signal originating from thee xt erna l. i xi ng network is applied to the summing current nodes oft he input amplifier via edge connector pins l /A.

Q1 through Q8 form a summing amplifier comprising a balanced input and an unba lan ct' d output. to correct for small system level variations, trim pot R7 is incorporated as part of the pr eampl i fie r. The differ e nt i alba lance adj us tllIe nt control R6 serves t o. i ni. i ze co• • on mode types i gnals originating ahead oft he amplifier. C12 couples the output oft he 5ummi ng allI pl i fie r to a l ow· pass filter consisting o f R2 2, R23. R2 4. C13, C14, C15 and II. The 3 dB roll off point i s located at approximately 40 kHz.

The output of IIi s coupled through CI B tot he output amplifier B-109A.

8· 109A Output Amplifier and INSERT The 8-1 09A amplifier raises the no.ina l signal level to 0 dB•. The output i sac t i vel y balanced and fed tot he &quot; insert point Mat pins 14/ Rafter passing thru ugh the SUBKASTER ON switch SWI. This switch controls all outputs of the -a dult and. therefore, perm f t s control over the complete SUBMAST ER group. Pins 14/ Rare usually connected t o a normal led set of insert jacks, with the output side connected tot he sub master fa der. The fa der output i s returned tot he module o n pins 8/J. The feed fort he PR EFADE AUXILIA RV outputs Is norlllally picked up a t t.ne llIix ing fa der input and is returned tot he 1lI0du le via

pins 13 / P.

8-109G Bos t e r A.pli f i er

This allI pl i fie rope rates with again of 23 dB. I t recovers the

15 dB Mi n_ha nd M loss incurred by the f ader and provides add it i on

alga l n to produce a nominal level of +B dBm a tits output.

DIRECT Output and MONITOR Outputs The DIRECT output appears at pins I S/S. Two ~o r e isolated out puts are provided a t pins 16/ T and 17/ U. The two latter outputs maybe utilized as metering and/ or monitor takeoffs. Cares houl d betaken tor est r ic t loading of these outputs t o Sk ohm or higher.

HASTE ROut puts Two assignable HAS TER outputs are made available via switches SW4 and SW5 t o pins lOlL and 111M respective l y. R3D is a level trim control allowing t o correct for s_a ll system level ve rte t fens •

AUXILIARY and SOLO Outputs Four AUXILIARY outputs are. ade available. each equipped with Its own assignment switch. AUXILIARY outputs I and 3 He preceded by level control R39. with control R42 feeding AUXILIARY outputs 2 and 4. R39 and R42 are preceded by PRE /POST selector swf tc hes SW2 and SW3 respectively. An additional feed iss uppl ied tot he SOLO output via assignment switch SWIO.

Control Functions A series dc control contact closure is provided through sl~ul tan eo u s operation o f the SUBHASTER ON switch SW land either one o f the MASTER ASSIGNMENT switches SW4 or SWS. A further control contact is available on the SOLO switch SWIO. Power Supply Decoupl l n9 An active power supply decoupl ing network consisting of Qg through Ql 4 provides isolation between the module and the !2S volts uppl y rails. Transistors Q13 and Q1 4 monitor the supply current. Int he event of excessive power supply de.an ds, such

a s fro~ component failure or amplifier overdrive. the current

flowing through Ql 1 and Ql2 will be limited.

**M47 3A SU8M ASTER MODULE**

PART OESCRl 1'1 lON

Cl C.pac, Ho r 330, u F/6 V

KtllI~ t

**1 390F33 7M00 6AS**

C3 • delete

C5 • 10 Phll i p s ZZ22-6 38 -101 0 9

C7 • 1 S pF • 2 222 -638 -10 15 9 C8 • 3.3 pF • ZZ22 -638-09338

C10 • 10 uF/2S V Keae t T39 0C10 6&quot;'02 SAS

C12 33 uFIlO V • 13900336M010A5 C13 • 1500 pF Ase1co CQ92-MC-1 52M Cl. • 2 20 pF Ph11 f ps 2222 -630 -0322 1 C15 • 100 p F • 2222-638 -70101

C16 • 10 p F • 2222 -638-10109 C17 • 4.7 pF • 2222 -638-09 4 78 CIS • 33 &quot;,FIlO V Ite.. e t. 13900336M010A5 C19 • delete C20 • 0.022 u F as e tcc (092 -&quot;'C -223P'1

C21 • 0.022 uF ase tce C092 -&quot;'C-2231'\ C22 • 22 &quot;,F /25 V Philips 426ETF22

CR) Diode delete CR2 • Motorola 1N4003

os, L f oh t bulb Sch ado w 18 V

Transistor Hat I ona 1 2N 4401

,3 •, PN36 45

&quot;OS,&quot; 2N440 1

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd2lCQi1kMlJxRlE/view?resourcekey=0-Zc6nPnHSQ94C_yMOGdLIlw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd2lCQi1kMlJxRlE&resourcekey=0-Zc6nPnHSQ94C_yMOGdLIlw" width="240" alt="1977 - M473A - 473-04-006 - WHEN DEPRESSED FEEDS SUBHA STER.jpg"></a><br><sub>1977|10 · 473-04-006 - WHEN DEPRESSED FEEDS SUBHA STER · <a href="MECHANICAL/1977%20-%20M473A%20-%20473-04-006%20-%20WHEN%20DEPRESSED%20FEEDS%20SUBHA%20STER%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ0h2Rm1MQ1h0cm8/view?resourcekey=0-PLTMFunN8TWkC7p0BEVzCQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ0h2Rm1MQ1h0cm8&resourcekey=0-PLTMFunN8TWkC7p0BEVzCQ" width="240" alt="1977 - M473A - 473-01-002 - TROLS MODIFIED REDRAWN REVISION.jpg"></a><br><sub>1977|10 · 473-01-002 - TROLS MODIFIED REDRAWN REVISION · <a href="SCHEMATICS/1977%20-%20M473A%20-%20473-01-002%20-%20TROLS%20MODIFIED%20REDRAWN%20REVISION%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTUpDUEtwc1VIek0/view?resourcekey=0-F9Xxgqo9RKSDaxZIUGPLYw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTUpDUEtwc1VIek0&resourcekey=0-F9Xxgqo9RKSDaxZIUGPLYw" width="240" alt="1977 - M473A - 473-06-002 - SOLDER SIDE COMPONENT SIDE.jpg"></a><br><sub>1977|10 · 473-06-002 - SOLDER SIDE COMPONENT SIDE · <a href="SCHEMATICS/1977%20-%20M473A%20-%20473-06-002%20-%20SOLDER%20SIDE%20COMPONENT%20SIDE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZm9uSzNYWUo3UGc/view?resourcekey=0-xyWe7DjvPwI4WJ2nGfHO7g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZm9uSzNYWUo3UGc&resourcekey=0-xyWe7DjvPwI4WJ2nGfHO7g" width="240" alt="1977 - M473A - 8-109-02-002 - OUTPUT AMPLIFIER SCHEMATIC.jpg"></a><br><sub>1977|10 · 8-109-02-002 - OUTPUT AMPLIFIER SCHEMATIC · <a href="SCHEMATICS/1977%20-%20M473A%20-%208-109-02-002%20-%20OUTPUT%20AMPLIFIER%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX0lNd2xmUTJDeWc/view?resourcekey=0-RLeVJ_zPSxFzC1c-B6lDYw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX0lNd2xmUTJDeWc&resourcekey=0-RLeVJ_zPSxFzC1c-B6lDYw" width="240" alt="1977 - M473A - BOOSTER AMPLIFIER SCHEMATIC.jpg"></a><br><sub>1977|10 · BOOSTER AMPLIFIER SCHEMATIC · <a href="SCHEMATICS/1977%20-%20M473A%20-%20BOOSTER%20AMPLIFIER%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKekUzcTBPckZ2RW8/view?resourcekey=0-w5ZAe9bnin86wQYO-jmoNQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKekUzcTBPckZ2RW8&resourcekey=0-w5ZAe9bnin86wQYO-jmoNQ" width="240" alt="1977 - M473A - P27 - 8-109A Output Amp Layout.jpg"></a><br><sub>1977|10 · P27 - 8-109A Output Amp Layout · <a href="SCHEMATICS/1977%20-%20M473A%20-%20P27%20-%208-109A%20Output%20Amp%20Layout%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKck9pWWJ4VmVlMG8/view?resourcekey=0-qPcwqgpg4wrUegrevffe0A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKck9pWWJ4VmVlMG8&resourcekey=0-qPcwqgpg4wrUegrevffe0A" width="240" alt="1977 - M473A - P28 - 8-109G Booster Amp Layout.jpg"></a><br><sub>1977|10 · P28 - 8-109G Booster Amp Layout · <a href="SCHEMATICS/1977%20-%20M473A%20-%20P28%20-%208-109G%20Booster%20Amp%20Layout%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV2h4bnZpVUwwdWM/view?resourcekey=0-kaYSywnviTLYR8bPBcNnsA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV2h4bnZpVUwwdWM&resourcekey=0-kaYSywnviTLYR8bPBcNnsA" width="240" alt="1977 - M473A - SUB MASTER MODULE SCHEMATIC.jpg"></a><br><sub>1977|10 · SUB MASTER MODULE SCHEMATIC · <a href="SCHEMATICS/1977%20-%20M473A%20-%20SUB%20MASTER%20MODULE%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `M473A - P22 - Functional Diagram.jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVkF2UFc1cjR3c2c/view?resourcekey=0-yTyzR69SMZAXM-4R4oJmNA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVkF2UFc1cjR3c2c&resourcekey=0-yTyzR69SMZAXM-4R4oJmNA" width="240" alt="1977 - M473A - P25 - Pin Out.jpg"></a><br><sub>1977|10 · P25 - Pin Out · <a href="PINOUTS/1977%20-%20M473A%20-%20P25%20-%20Pin%20Out%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `M473A - RTO-144 Connections.pdf`

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it); the RTO-144 sheet agrees on 15 of 17 contacts; 2 to check (`conflicts`). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

**To check:**

- disagree P1-J: kept ATT OUT (out); RTO-144 sheet says Insert Return - (in)
- disagree P1-R: kept SUB ON OUT (control_out); RTO-144 sheet says Insert Return + (in)

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 1 | INPUT | in | INPUT | high |
| 2 | INPUT SHIELD | shield | INPUT shield | high |
| 3 | AUX 4 OUT | out | AUX 4 OUT | high |
| 4 | AUX 2 OUT | out | AUX 2 OUT | high |
| 5 | AUX 3 OUT | out | AUX 3 OUT | high |
| 6 | AUX 1 OUT | out | AUX 1 OUT | high |
| 7 | SOLO OUT | out | SOLO OUT | high |
| 8 | ATT OUT | out | ATT OUT | high |
| 9 | GND | ground |  | high |
| 10 | M1 OUT | out | M1 OUT | high |
| 11 | M2 OUT | out | M2 OUT | high |
| 12 | GND | ground |  | high |
| 13 | AUX PRE-FADE IN | in | AUX PRE-FADE IN | high |
| 14 | SUB ON OUT | control_out | SUB ON OUT | high |
| 15 | DIRECT OUT | out | DIRECT OUT | high |
| 16 | MONITOR OUT | out | MONITOR OUT | high |
| 17 | MONITOR OUT | out | MONITOR OUT | high |
| 18 | CONTROL COM | ground |  | high |
| 19 | -25 V | power |  | high |
| 20 | ±COMMON | ground |  | high |
| 21 | +25 V | power |  | high |
| 22 | CHASSIS | ground |  | high |
| A | INPUT | in | INPUT | high |
| B | INPUT SHIELD | shield | INPUT shield | high |
| C | AUX 4 OUT | out | AUX 4 OUT | high |
| D | AUX 2 OUT | out | AUX 2 OUT | high |
| E | AUX 3 OUT | out | AUX 3 OUT | high |
| F | AUX 1 OUT | out | AUX 1 OUT | high |
| H | SOLO OUT | out | SOLO OUT | high |
| J | ATT OUT | out | ATT OUT | high |
| K | GND | ground |  | high |
| L | M1 OUT | out | M1 OUT | high |
| M | M2 OUT | out | M2 OUT | high |
| N | GND | ground |  | high |
| P | AUX PRE-FADE IN | in | AUX PRE-FADE IN | high |
| R | SUB ON OUT | control_out | SUB ON OUT | high |
| S | DIRECT OUT | out | DIRECT OUT | high |
| T | MONITOR OUT | out | MONITOR OUT | high |
| U | MONITOR OUT | out | MONITOR OUT | high |
| V | SOLO CONTROL | control_in | SOLO CONTROL | high |
| W | M1 CTL | control_in | M1 CTL | high |
| X | M2 CTL | control_in | M2 CTL | high |
| Y | +24 V | power |  | high |
| Z | SUB CTL | control_in | SUB CTL | high |

**Straps:** JMP.Y.21: P2-Y P2-21 · JMP.20.18: P2-20 P2-18 · JMP.22.21: P2-22 P2-21 · JMP.Z.Y: P2-Z P2-Y

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSUhZakF0S2RtUW8/view?resourcekey=0-H8gKb0Ti1aitUHTK5nUAdw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSUhZakF0S2RtUW8&resourcekey=0-H8gKb0Ti1aitUHTK5nUAdw" width="240" alt="1977 - M473A - P01 - Cover.jpg"></a><br><sub>1977|10 · P01 - Cover</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNU03RkU4Um1FOFU/view?resourcekey=0-tC7KzmOKJ7xAWdCuxB7plw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNU03RkU4Um1FOFU&resourcekey=0-tC7KzmOKJ7xAWdCuxB7plw" width="240" alt="1977 - M473A - P02.jpg"></a><br><sub>1977|10 · P02</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWWRkRkVlRkdFV3c/view?resourcekey=0-5i6LhgeWg95UOlsTYihE9g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWWRkRkVlRkdFV3c&resourcekey=0-5i6LhgeWg95UOlsTYihE9g" width="240" alt="1977 - M473A - P04 - Warranty.jpg"></a><br><sub>1977|10 · P04 - Warranty</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdkc5RlBvQnFOSXM/view?resourcekey=0-TMYuLpJqWtZ5d-8lW02nQg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdkc5RlBvQnFOSXM&resourcekey=0-TMYuLpJqWtZ5d-8lW02nQg" width="240" alt="1977 - M473A - P05 - 1-1.jpg"></a><br><sub>1977|10 · P05 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKemVXaDdaSDBaWlk/view?resourcekey=0-bFhvinWFMbsuIAjxHy8bSw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKemVXaDdaSDBaWlk&resourcekey=0-bFhvinWFMbsuIAjxHy8bSw" width="240" alt="1977 - M473A - P06 - 2-1.jpg"></a><br><sub>1977|10 · P06 - 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaUVrTHNXUzgxakE/view?resourcekey=0-ejkN6Oal_jiaXSion6kTkQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaUVrTHNXUzgxakE&resourcekey=0-ejkN6Oal_jiaXSion6kTkQ" width="240" alt="1977 - M473A - P07 - 2-2.jpg"></a><br><sub>1977|10 · P07 - 2-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLVEtWV9xNUlnbjQ/view?resourcekey=0-jVteMnLZhNCt8SSRT3QbAA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLVEtWV9xNUlnbjQ&resourcekey=0-jVteMnLZhNCt8SSRT3QbAA" width="240" alt="1977 - M473A - P08 - 3-1.jpg"></a><br><sub>1977|10 · P08 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaF9PTU92X1J3dmc/view?resourcekey=0-iJNGZ7aYtkTgo2GZ2oe6cw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaF9PTU92X1J3dmc&resourcekey=0-iJNGZ7aYtkTgo2GZ2oe6cw" width="240" alt="1977 - M473A - P09 - 3-2.jpg"></a><br><sub>1977|10 · P09 - 3-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdkNlS05Qam1MQVE/view?resourcekey=0-u8Yp5PDvoki4W1kjhllzag" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdkNlS05Qam1MQVE&resourcekey=0-u8Yp5PDvoki4W1kjhllzag" width="240" alt="1977 - M473A - P10 - 3-3.jpg"></a><br><sub>1977|10 · P10 - 3-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcVNyMkViWEVXTWs/view?resourcekey=0-N9unAZbx-HSRqpz6-14S4w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcVNyMkViWEVXTWs&resourcekey=0-N9unAZbx-HSRqpz6-14S4w" width="240" alt="1977 - M473A - P11 - 3-4.jpg"></a><br><sub>1977|10 · P11 - 3-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYkkwMV8tYkxfclE/view?resourcekey=0-ak8Mw99JAi3NXwU9b72K5Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYkkwMV8tYkxfclE&resourcekey=0-ak8Mw99JAi3NXwU9b72K5Q" width="240" alt="1977 - M473A - P12.jpg"></a><br><sub>1977|10 · P12</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUUlmcmR6WGM1T2M/view?resourcekey=0-WyggI9THqsYVJMT9KvMzfQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUUlmcmR6WGM1T2M&resourcekey=0-WyggI9THqsYVJMT9KvMzfQ" width="240" alt="1977 - M473A - P13 - 8-109-1-1.jpg"></a><br><sub>1977|10 · P13 - 8-109-1-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN2JBd2NDVXdXNlE/view?resourcekey=0-Bdcr9RxVTdbRxWTqJHTB3g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN2JBd2NDVXdXNlE&resourcekey=0-Bdcr9RxVTdbRxWTqJHTB3g" width="240" alt="1977 - M473A - P14 - 8-109-1-2.jpg"></a><br><sub>1977|10 · P14 - 8-109-1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUzRBQkljQnhhSEU/view?resourcekey=0-7L6P97oyo-_2NyFMDcDXhA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUzRBQkljQnhhSEU&resourcekey=0-7L6P97oyo-_2NyFMDcDXhA" width="240" alt="1977 - M473A - P15 - 8-109-1-3.jpg"></a><br><sub>1977|10 · P15 - 8-109-1-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYlFTczRrRTBxaDg/view?resourcekey=0-J2-jgB9ja4dar07ws9_xVA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYlFTczRrRTBxaDg&resourcekey=0-J2-jgB9ja4dar07ws9_xVA" width="240" alt="1977 - M473A - P16 - 8-109-2-1.jpg"></a><br><sub>1977|10 · P16 - 8-109-2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcG1fMVV6S2RlaEk/view?resourcekey=0-AkxZBkaYCIfXIIf_t_obsw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcG1fMVV6S2RlaEk&resourcekey=0-AkxZBkaYCIfXIIf_t_obsw" width="240" alt="1977 - M473A - P17 - 8-109-2-2.jpg"></a><br><sub>1977|10 · P17 - 8-109-2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT2Z2Q2dwYWFHcWM/view?resourcekey=0-EVY9gJVPtj2l2ZZDSdOrRw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT2Z2Q2dwYWFHcWM&resourcekey=0-EVY9gJVPtj2l2ZZDSdOrRw" width="240" alt="1977 - M473A - P18 - 8-109-2-3.jpg"></a><br><sub>1977|10 · P18 - 8-109-2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSmd1eDZWZEhyeVE/view?resourcekey=0-mXn3ZGgPYc1N4RTgp-Pm7w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSmd1eDZWZEhyeVE&resourcekey=0-mXn3ZGgPYc1N4RTgp-Pm7w" width="240" alt="1977 - M473A - P19 - 8-109-2-4.jpg"></a><br><sub>1977|10 · P19 - 8-109-2-4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRGdMeUt0MGo4T0U/view?resourcekey=0-MZNcrRh6YzuDQ-ZOj0y3sg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRGdMeUt0MGo4T0U&resourcekey=0-MZNcrRh6YzuDQ-ZOj0y3sg" width="240" alt="1977 - M473A - P20 - 8-109-2-5.jpg"></a><br><sub>1977|10 · P20 - 8-109-2-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOGdad0NZS0pJMDA/view?resourcekey=0-yu5F43BuGA5JMtTvSsYT3g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOGdad0NZS0pJMDA&resourcekey=0-yu5F43BuGA5JMtTvSsYT3g" width="240" alt="1977 - M473A - Submaster Module (2).pdf"></a><br><sub>1977|10 · Submaster Module (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKak9Vc2Z6TXEyS1E/view?resourcekey=0-qOA7yXboFS5uvAACt_LX5Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKak9Vc2Z6TXEyS1E&resourcekey=0-qOA7yXboFS5uvAACt_LX5Q" width="240" alt="1977 - M473A - Submaster Module.pdf"></a><br><sub>1977|10 · Submaster Module</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT1Flb1pObG94dWs/view?resourcekey=0-mRM7C7MYlaHjN9606z3NlA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT1Flb1pObG94dWs&resourcekey=0-mRM7C7MYlaHjN9606z3NlA" width="240" alt="1979 - M473A - P03 - Toc.jpg"></a><br><sub>1979|12 · P03 - Toc</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1n63BsKGxgEex5tIHJA3IP6q4jbEEInje/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1n63BsKGxgEex5tIHJA3IP6q4jbEEInje" width="240" alt="19xx - M473A - DOC - 2021-3-16-19-51-24.jpg"></a><br><sub>19xx - M473A - DOC - 2021-3-16-19-51-24</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1LWDblL8K3AfUMzIqTU0k-OTo2Kbm7IlQ/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1LWDblL8K3AfUMzIqTU0k-OTo2Kbm7IlQ" width="240" alt="19xx - M473A - DOC - WILMA - monitor routing.jpg"></a><br><sub>19xx - M473A - DOC - WILMA - monitor routing</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/17ybd2QRnca7QwcUymQFe8AYWmyXsNgVi/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=17ybd2QRnca7QwcUymQFe8AYWmyXsNgVi" width="240" alt="19xx - M473A - DOC - WILMA - monitor section.jpg"></a><br><sub>19xx - M473A - DOC - WILMA - monitor section</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [19xx - M473A - DOC - what a module looks like 2](https://drive.google.com/file/d/0B0yR0b5T78SKcGczMHlUNmlMT1k/view?resourcekey=0-TOibSa3L_kf273NsrhFv2g)

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1977 - M473A - 473-01-002 - TROLS MODIFIED REDRAWN REVISION.kicad_sch](KICAD/1977%20-%20M473A%20-%20473-01-002%20-%20TROLS%20MODIFIED%20REDRAWN%20REVISION.kicad_sch)
- [1977 - M473A - 8-109-02-002 - OUTPUT AMPLIFIER SCHEMATIC.kicad_sch](KICAD/1977%20-%20M473A%20-%208-109-02-002%20-%20OUTPUT%20AMPLIFIER%20SCHEMATIC.kicad_sch)
- [1977 - M473A - BOOSTER AMPLIFIER SCHEMATIC.kicad_sch](KICAD/1977%20-%20M473A%20-%20BOOSTER%20AMPLIFIER%20SCHEMATIC.kicad_sch)
- [1977 - M473A - SUB MASTER MODULE SCHEMATIC.kicad_sch](KICAD/1977%20-%20M473A%20-%20SUB%20MASTER%20MODULE%20SCHEMATIC.kicad_sch)
- [1977 - M473A - Submaster Module (2) p19.kicad_sch](KICAD/1977%20-%20M473A%20-%20Submaster%20Module%20(2)%20p19.kicad_sch)
- [1977 - M473A - Submaster Module p22.kicad_sch](KICAD/1977%20-%20M473A%20-%20Submaster%20Module%20p22.kicad_sch)
- [1977 - M473A - Submaster Module p23.kicad_sch](KICAD/1977%20-%20M473A%20-%20Submaster%20Module%20p23.kicad_sch)
- [1977 - M473A - Submaster Module p27.kicad_sch](KICAD/1977%20-%20M473A%20-%20Submaster%20Module%20p27.kicad_sch)
- [1977 - M473A - Submaster Module p29.kicad_sch](KICAD/1977%20-%20M473A%20-%20Submaster%20Module%20p29.kicad_sch)
- [M473A - P22 - Functional Diagram.kicad_sch](KICAD/M473A%20-%20P22%20-%20Functional%20Diagram.kicad_sch)
- [M473A - P28 - 8-109G Booster Amp Schematic.kicad_sch](KICAD/M473A%20-%20P28%20-%208-109G%20Booster%20Amp%20Schematic.kicad_sch)
- [M473A.kicad_sym](KICAD/M473A.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
