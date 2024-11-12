# Energy Monitoring with LoRaWAN
> The first iteration of a small, efficient, powerful monitoring package.
<img src="https://github.com/user-attachments/assets/55031c5b-47f4-44da-be43-cbea9d6fc508" />

## 🚩 Table of Contents

- [Project Description](#-project-description)
- [Schematics](#-schematics)
- [PCB Design Properties and Specifications](#-pcb-design-properties-and-specifications)
- [Board Presentation](#-board-presentation)
- [Bill of Materials](#-bill-of-materials)
- [Fabrication Files](#-fabrication-files)
- [Version History](#-version-history)
- [Project File](#-project-file)
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

| <img src="https://user-images.githubusercontent.com/1215767/34348387-a2e64588-ea4d-11e7-8267-a43365103afe.png" alt="Chrome" width="16px" height="16px" /> Chrome | <img src="https://user-images.githubusercontent.com/1215767/34348590-250b3ca2-ea4f-11e7-9efb-da953359321f.png" alt="IE" width="16px" height="16px" /> Internet Explorer | <img src="https://user-images.githubusercontent.com/1215767/34348380-93e77ae8-ea4d-11e7-8696-9a989ddbbbf5.png" alt="Edge" width="16px" height="16px" /> Edge | <img src="https://user-images.githubusercontent.com/1215767/34348394-a981f892-ea4d-11e7-9156-d128d58386b9.png" alt="Safari" width="16px" height="16px" /> Safari | <img src="https://user-images.githubusercontent.com/1215767/34348383-9e7ed492-ea4d-11e7-910c-03b39d52f496.png" alt="Firefox" width="16px" height="16px" /> Firefox |
| :---------: | :---------: | :---------: | :---------: | :---------: |
| Yes | 11+ | Yes | Yes | Yes |


## 🔧 Fabrication Files
If you wish you print this board for yourself, you can navigate to the folder containing the Gerber files for this project.

#### Altium 365 Project

``` sh
$ https://oreofeoluwa-ayoola.365.altium.com/designs/1BFC9E72-5E92-4F1D-BF10-B9AC457842F1
```

## 💬 Version History

* [Code of Conduct](https://github.com/nhn/tui.editor/blob/master/CODE_OF_CONDUCT.md)
* [Contributing Guideline](https://github.com/nhn/tui.editor/blob/master/CONTRIBUTING.md)
* [Commit Convention](https://github.com/nhn/tui.editor/blob/master/docs/COMMIT_MESSAGE_CONVENTION.md)
* [Issue Guidelines](https://github.com/nhn/tui.editor/tree/master/.github/ISSUE_TEMPLATE)


## 🍞 Download Project Files (Schematics and PCB)

- [TOAST UI Calendar](https://github.com/nhn/tui.calendar)
- [TOAST UI Chart](https://github.com/nhn/tui.chart)
- [TOAST UI Grid](https://github.com/nhn/tui.grid)
- [TOAST UI Image Editor](https://github.com/nhn/tui.image-editor)
- [TOAST UI Components](https://github.com/nhn)


## 🚀 Used By

* [NHN Dooray! - Collaboration Service (Project, Messenger, Mail, Calendar, Drive, Wiki, Contacts)](https://dooray.com)
* [UNOTES - Visual Studio Code Extension](https://marketplace.visualstudio.com/items?itemName=ryanmcalister.Unotes)


## 📜 License

This software is licensed under the [MIT](https://github.com/nhn/tui.editor/blob/master/LICENSE) © [NHN Cloud](https://github.com/nhn).
