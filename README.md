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


* [Viewer](https://github.com/nhn/tui.editor/tree/master/docs/en/viewer.md) : Supports a mode to display only markdown data without an editing area.
* [Internationalization (i18n)](https://github.com/nhn/tui.editor/tree/master/docs/en/i18n.md) : Supports English, Dutch, Korean, Japanese, Chinese, Spanish, German, Russian, French, Ukrainian, Turkish, Finnish, Czech, Arabic, Polish, Galician, Swedish, Italian, Norwegian, Croatian + language and you can extend.
* [Widget](https://github.com/nhn/tui.editor/tree/master/docs/en/widget.md) : This feature allows you to configure the rules that replaces the string matching to a specific `RegExp` with the widget node.
* [Custom Block](https://github.com/nhn/tui.editor/tree/master/docs/en/custom-block.md) : Nodes not supported by Markdown can be defined through custom block. You can display the node what you want through writing the parsing logic with custom block.

## 🐾 Board Presentation 

* [Basic](https://nhn.github.io/tui.editor/latest/tutorial-example01-editor-basic)
* [Viewer](https://nhn.github.io/tui.editor/latest/tutorial-example04-viewer)
* [Using All Plugins](https://nhn.github.io/tui.editor/latest/tutorial-example12-editor-with-all-plugins)
* [Creating the User's Plugin](https://nhn.github.io/tui.editor/latest/tutorial-example13-creating-plugin)
* [Customizing the Toobar Buttons](https://nhn.github.io/tui.editor/latest/tutorial-example15-customizing-toolbar-buttons)
* [Internationalization (i18n)](https://nhn.github.io/tui.editor/latest/tutorial-example16-i18n)

Here are more [examples](https://nhn.github.io/tui.editor/latest/tutorial-example01-editor-basic) and play with TOAST UI Editor!


## 🌏 Bill of Materials

| <img src="https://user-images.githubusercontent.com/1215767/34348387-a2e64588-ea4d-11e7-8267-a43365103afe.png" alt="Chrome" width="16px" height="16px" /> Chrome | <img src="https://user-images.githubusercontent.com/1215767/34348590-250b3ca2-ea4f-11e7-9efb-da953359321f.png" alt="IE" width="16px" height="16px" /> Internet Explorer | <img src="https://user-images.githubusercontent.com/1215767/34348380-93e77ae8-ea4d-11e7-8696-9a989ddbbbf5.png" alt="Edge" width="16px" height="16px" /> Edge | <img src="https://user-images.githubusercontent.com/1215767/34348394-a981f892-ea4d-11e7-9156-d128d58386b9.png" alt="Safari" width="16px" height="16px" /> Safari | <img src="https://user-images.githubusercontent.com/1215767/34348383-9e7ed492-ea4d-11e7-910c-03b39d52f496.png" alt="Firefox" width="16px" height="16px" /> Firefox |
| :---------: | :---------: | :---------: | :---------: | :---------: |
| Yes | 11+ | Yes | Yes | Yes |


## 🔧 Fabrication Files

TOAST UI products are open source, so you can create a pull request(PR) after you fix issues. Run npm scripts and develop yourself with the following process.

### Setup

Fork `main` branch into your personal repository. Clone it to local computer. Install node modules. Before starting development, you should check if there are any errors.

```sh
$ git clone https://github.com/{your-personal-repo}/tui.editor.git
$ npm install
$ npm run build toastmark
$ npm run test editor
```

> TOAST UI Editor uses [npm workspace](https://docs.npmjs.com/cli/v7/using-npm/workspaces/), so you need to set the environment based on [npm7](https://github.blog/2021-02-02-npm-7-is-now-generally-available/). If subversion is used, dependencies must be installed by moving direct paths per package.

### Develop

You can see your code reflected as soon as you save the code by running a server. Don't miss adding test cases and then make green rights.

#### Run snowpack-dev-server
[snowpack](https://www.snowpack.dev/) allows you to run a development server without bundling.

``` sh
$ npm run serve editor
```

#### Run webpack-dev-server
If testing of legacy browsers is required, the development server can still be run using a [webpack](https://webpack.js.org/).

``` sh
$ npm run serve:ie editor
```

#### Run test

``` sh
$ npm test editor
```

### Pull Request

Before uploading your PR, run test one last time to check if there are any errors. If it has no errors, commit and then push it!

For more information on PR's steps, please see links in the Contributing section.

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
