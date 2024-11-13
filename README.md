# Energy Monitoring with LoRaWAN
> The first iteration of a small, efficient, powerful monitoring package.
<img src="https://github.com/user-attachments/assets/55031c5b-47f4-44da-be43-cbea9d6fc508" />

## 🚩 Table of Contents

- [Project Description](#-project-description)
- [Schematics](#-schematics)
- [PCB Design Properties and Specifications](#-pcb-design-properties-and-specifications)
- [Board Presentation](#-board-presentation)
- [Bill of Materials](#-bill-of-materials)
- [Version History](#-version-history)
- [Download Project Files](#-download-project-files)
- [Used By](#-used-by)
- [License](#-license)


##  Project Description 
The *energy monitoring* module shown above is an open-source project designed to help enthusiasts monitor energy consumed with the aid of current and voltage sensors. To help address the issue of unclear electric usage and tariffs, you can explore using this unit to wirelessly monitor energy consumption. To ensure easy access to the data acquired by the voltage and current sensors, two wireless communication modules were incorporated onboard. This includes a LoRa_E5 Module to initiate LoRaWAN Communication and a NINA module to provide access to data via WiFi or BLE. *Altium Designer* is the software used for this project.


## 🤖 Schematics?

The schematics are two sheets in total. Sheet 1 contains symbols and connections for highspeed USB-C, Atemga328 MCU, 6-pin headers, RGB module, USB to Serial IC, terminal blocks, and 12V to 5V power converter. Sheet 2 contains symbols for a LoRa_E5 module, a NINA-W102-00B, and a bidirectional 5V to 3V3 level translator.

### Energy Monitoring Schematic Sheet 1
This images is compressed. If you struggle with seeing certain details you can download the schematics in the Project files section below. Thanks!!
<img src="https://github.com/user-attachments/assets/da3b64b4-7132-490b-884f-687870abf510" />

### Energy Monitoring Schematic Sheet 2
This images is compressed. If you struggle with seeing certain details you can download the schematics in the Project files section below. Thanks!!
<img src="https://github.com/user-attachments/assets/e44891f0-4ea8-47d1-83c9-54377b72260e" />

## 🎨 PCB Design Properties and Specifications
| Category | Description |
| --- | --- |
| Board Thinkess | 1.612mm |
| Board Height | 10mm |
| Dimension | 40mm x 80mm |
| Number of Layers |  2  |
| Soldermask | Green |
| Silkscreen | White |
| mounting Holes | 4 |
| Edge Fillet Radius | 2mm |
| Impedance Profile (Antenna) | 50Ω |
| Impedance Profile (USB) | 90Ω |
| Minimum Trace Width  | 0.2mm|
| Maximum Trace Width | 0.2mm |
| Minimum Hole Size  | 0.2mm|
| Maximum Hole Size | 0.2mm |

## 🐾 Board Presentation 
Below is the board in different views. To see areas of the board not shown below , please visit the Altium 365 project link. 
<img src="https://github.com/user-attachments/assets/7185e227-41d2-4916-9e0d-90ed663ac18a" />



## 🌏 Bill of Materials

| S/N | Description         | Designator                 | Quantity | Footprint                      | Manufacturer           | Manufacturer Part Number      | Manufacturer Lifecycle       | Supplier Part Number       |
|:---------:| :---------:| :---------: |:---------:|:---------:|:---------: |:---------:| :---------:| :---------:|
| 1      | Tactile Switch       | BT1, BT2                   | 2        | OMRON-B3F-1000-4_V            | Omron                  | B3F-1000                       | Volume Production            | 36K7138                    |
| 2      | Chip Capacitor       | C1, C20                    | 2        | CAPC1005X55X25LL05T10          | Murata                 | GRM155R71A104KA01D            | Volume Production            | 490-6321-6-ND              |
| 3      | Multilayer Ceramic Capacitors | C2              | 1        | FP-C3216-160-0_2-IPC_A         | TDK                    | C3216X5R1H106K160AB           | Volume Production            | 05X9901                    |
| 4      | CAP CER             | C3, C14, C15, C16, C21, C22, C23, C24, C26 | 9 | FP-GRM15-MFG                | Murata                 | GRM155R71C104KA88D            | Volume Production            | 81-GRM155R71C104KA88       |
| 5      | Chip Multilayer Ceramic Capacitors | C5       | 1        | FP-GRM21B-0_2-e0_2_0_7-IPC_C   | Murata                 | GRM21BR61A226ME44L            | Volume Production            | 2104135                    |
| 6      | Schottky Barrier Diode | D1, D4                 | 2        | ONSC-SOD-323-2-477-02_V        | ON Semiconductor        | BAT54HT1G                     | Volume Production            | 863-BAT54HT1G              |
| 7      | Mono-Color Chip LED | D2, D3                     | 2        | WL-SMCW_0603_150060xx75020     | Wurth Electronics       | 150060AS75020                 | Volume Production            | 732-150060AS75020CT-ND     |
| 8      | CONN HEADER         | J1, J3, J4                 | 3        | FP-M20-9980346-MFG             | Harwin                 | M20-9980346                   | Volume Production            | 97K6200                    |
| 9      | CONN RCP USB2.0     | J2                         | 1        | FP-2130830005-MFG              | Molex                  | 213083-0005                   | Unknown                      | 3648630                    |
| 10     | Power Inductor      | L1                         | 1        | BOUR-SRN3015-2_V               | Bourns                 | SRN3015-3R3M                  | Volume Production            | 652-SRN3015-3R3M           |
| 11     | SMD Inductors       | L2                         | 1        | FP-CB3225-IPC_A                | Taiyo Yuden            | CBC3225T100MR                 | Not Recommended for New Design | 1463485                    |
| 12     | Chip Resistor       | R5, R10, R25               | 3        | RESC1609X50X30NL8T20           | Vishay                 | CRCW060310K0FKEA              | Volume Production            | 61M5335                    |
| 13     | Chip Resistor       | R6, R7, R13, R14, R26      | 5        | RESC1005X40X25LL05T05          | Panasonic              | ERJ-2GEJ221X                  | Volume Production            | 65T8267                    |
| 14     | Resistor            | R8, R9                     | 2        | RESC0805(2012)_N               | Yageo                  | RC0805FR-075K11L              | Volume Production            | 49AK3294                   |
| 15     | Chip Resistor       | R16, R17                   | 2        | RESC1005X40X25NL5T10           | Yageo / Phycomp        | RC0402JR-072K2L               | Unknown                      |                            |
| 16     | SMD Chip Resistor   | R19                        | 1        | FP-RN732A-MFG                  | TE Connectivity        | RN73C2A100KBTDF               | Unknown                      | 46AK9411                   |
| 17     | Crystal             | Y1                         | 1        | FP-ABM8AIG-MFG                 | Abracon                | ABM8AIG-16.000MHZ-12-2Z-T3    | Volume Production            | 56AC7507                   |
| 18     | Crystal             | Y2                         | 1        | FP-ABM7-MFG                    | Abracon                | ABM7-16.000MHZ-D2Y-T          | Unknown                      | 67P3843                    |

- 
#### Altium 365 Project

``` sh
$ https://oreofeoluwa-ayoola.365.altium.com/designs/1BFC9E72-5E92-4F1D-BF10-B9AC457842F1
```

## 💬 Version History
## 🍞 Download Project Files

- [Schematics](https://github.com/nhn/tui.calendar)
- [PCB Files]([https://github.com/nhn/tui.chart](https://github.com/Oreoluwa-IVT/-Energy-Monitoring-LoRaWAN-BLE-WiFi/blob/main/Altium%20PCB%20File.zip))
- [Gerber Files]([https://github.com/nhn/tui.grid](https://github.com/Oreoluwa-IVT/-Energy-Monitoring-LoRaWAN-BLE-WiFi/blob/main/GerberX2.zip))

## 📜 License
This software is licensed under the [MIT](https://github.com/nhn/tui.editor/blob/master/LICENSE) © [NHN Cloud](https://github.com/nhn).
