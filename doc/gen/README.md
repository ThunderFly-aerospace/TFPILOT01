# PCB

Board size: 61.5x47.5 mm (2.42x1.87 inches)

- This is the size of the rectangle that contains the board
- Thickness: 4.69 mm (185 mils)
- Material: FR4
- Finish: None
- Layers: 4
- Copper thickness: 35 µm

Solder mask: TOP / BOTTOM

- Color: Green

Silk screen: TOP / BOTTOM

- Color: White


Stackup:

| Name                 | Type                 | Color            | Thickness [µm]| Material        | Er        | Loss tan     |
|----------------------|----------------------|------------------|---------------|-----------------|-----------|--------------|
| F.SilkS              | Top Silk Screen      |                  |               |                 |           |              |
| F.Paste              | Top Solder Paste     |                  |               |                 |           |              |
| F.Mask               | Top Solder Mask      | Green            |            10 |                 |           |              |
| F.Cu                 | copper               |                  |            35 |                 |           |              |
| dielectric 1         | core                 |                  |          1510 | FR4             |       4.5 |        0.020 |
| In1.Cu               | copper               |                  |            35 |                 |           |              |
| dielectric 2         | prepreg              |                  |          1510 | FR4             |       4.5 |        0.020 |
| In2.Cu               | copper               |                  |            35 |                 |           |              |
| dielectric 3         | core                 |                  |          1510 | FR4             |       4.5 |        0.020 |
| B.Cu                 | copper               |                  |            35 |                 |           |              |
| B.Mask               | Bottom Solder Mask   | Green            |            10 |                 |           |              |
| B.Paste              | Bottom Solder Paste  |                  |               |                 |           |              |
| B.SilkS              | Bottom Silk Screen   |                  |               |                 |           |              |

# Important sizes

Clearance: 0.1 mm (4 mils)

Track width: 0.15 mm (6 mils)

- By design rules: 0.15 mm (6 mils)

Drill: 0.25 mm (10 mils)

- Vias: 0.25 mm (10 mils) [Design: 0.25 mm (10 mils)]
- Pads: 0.6 mm (24 mils)
- The above values are real drill sizes, they add 0.1 mm (4 mils) to plated holes (PTH)

Via: 0.45/0.15 mm (18/6 mils)

- By design rules: 0.15/0.15 mm (6/6 mils)
- Micro via: yes [0.2/0.1 mm (8/4 mils)]
- Buried/blind via: yes
- Total: 145 (thru: 145 buried/blind: 0 micro: 0)

Outer Annular Ring: 0.1 mm (4 mils)

- By design rules: 0.13 mm (5 mils)

Eurocircuits class: 8E
- Using min drill 0.2 mm for an OAR of 0.13 mm


# General stats

Components count: (SMD/THT)

- Top: 62/11 (SMD + THT)
- Bottom: 0/0 (NONE)

Defined tracks:

- 0.16 mm (6 mils)
- 0.2 mm (8 mils)

Used tracks:

- 0.15 mm (6 mils) (68) defined: no
- 0.16 mm (6 mils) (744) defined: yes
- 0.2 mm (8 mils) (173) defined: yes
- 0.25 mm (10 mils) (30) defined: no

Defined vias:

- 0.5/0.15 mm (20/6 mils)

Used vias:

- 0.45/0.15 mm (18/6 mils) (Count: 145, Aspect: 10.4 C) defined: no

Holes (excluding vias):

- 0.5 mm (20 mils) (1)
- 0.65 mm (26 mils) (11)
- 1.0 mm (39 mils) (62)

Oval holes:

- 0.5x1.65 mm (20x65 mils) (8)

Drill tools (including vias and computing adjusts and rounding):

- 0.25 mm (10 mils) (145)
- 0.6 mm (24 mils) (9)
- 0.65 mm (26 mils) (4)
- 0.75 mm (30 mils) (7)
- 1.1 mm (43 mils) (62)

Solder paste stats:

Using a paste with 87.75 % alloy, that has an specific gravity for the alloy of 7.4 g/cm³
and 1.0 g/cm³ for the flux. This paste has an specific gravity of  4.15 g/cm³.

The stencil thickness is  0.12 mm.

| Side   | Pads with paste | Area [mm²] | Paste [g] |
|--------|-----------------|------------|-----------|
| Total  |             406 |     166.59 |      0.83 |

Note: this is just an approximation to the theoretical value. Margins of the solder mask and waste aren't computed.



