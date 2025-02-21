# Awesome JITX

This is a collection of helpful code libraries for designing circuit boards with [JITX](https://www.jitx.com/).

# Contents

*  [How to Use](#how-to-use) - Instructions for using Packages
*  [Frameworks](#frameworks) - Framework Libraries to speed up design development
*  [Circuits](#circuits) - Code for generating common circuits like filters, and power regulators
*  [Components](#components) - Component Libraries, Generators, etc
*  [Fabrication](#fabrication) - Stackups and Constraints for Fabricators
*  [Libraries](#libraries) - Common utilities like curl

# How To Use

The best way to use many of these projects is through the [slm](https://github.com/stanzaorg/slm) library manager. To add a dependency, use the Github path to that project, for example:

```
$>  $SLM add -git JITx-Inc/debug
```

Run this command from your VSCode project. This will result in a line added to the `slm.toml` file of your JITX project that looks like this:

```
[dependencies]
debug = { git = "JITx-Inc/debug", version = "0.3.3" }
```


# Frameworks

*  [JSL](https://github.com/JITx-Inc/jsl) - JITX standard library (JSL) which contains landpattern generators, symbol generators, protocols, and many other packages for supporting designs in JITX.

# Circuits
*  [power-systems](https://github.com/JITx-Inc/power-systems) - Architectures and solvers for DC/DC power regulation, and power filters
*  [debug](https://github.com/JITx-Inc/debug) - Debugging circuits for JTAG, SWD, test points, etc.
*  [voltage-divider](https://github.com/JITx-Inc/voltage-divider) - Voltage divider circuit solver and generator

# Components

*  [connectors](https://github.com/JITx-Inc/connectors) - Helpful connectors like USB, and terminal blocks, mapped to standard interfaces
*  [diodes](https://github.com/JITx-Inc/diodes) - Diodes including zeners and ESD arrays.
*  [FTDI](https://github.com/JITx-Inc/FTDI) - Circuits for [FTDI](https://ftdichip.com/) components, including parts like the FT2232HL
*  [microchip-networking](https://github.com/JITx-Inc/microchip-networking/tree/main) - Circuits for [Microchip](https://www.microchip.com/) networking devices, including ethernet switches
*  [TI-vreg](https://github.com/JITx-Inc/TI-vreg) - Voltage regulators from [Texas Instruments](https://www.ti.com/)
*  [stmicro](https://github.com/JITx-Inc/stmicro) - Microcontrollers from [STMicro](https://www.st.com)
*  [mechanical](https://github.com/JITx-Inc/mechanical) - Mechanical components like mounting holes, fiducials, layer legends, etc.
*  [passives](https://github.com/JITx-Inc/passives) - Passive part generators, eg ferrites, crystals, etc.
*  [switches](https://github.com/JITx-Inc/switches) - Library of switch components, such as tactile switches, DIP switches, etc.
*  [inductors](https://github.com/JITx-Inc/inductors) - Library of inductor components
*  [EEPROM](https://github.com/JITx-Inc/EEPROM) - Library of EEPROM components


# Fabrication

*  [jlc-pcb](https://github.com/JITx-Inc/jlc-pcb) - Stackups, vias, and impedance controlled designs for JLCPCB

# Libraries

*  [libcurl](https://github.com/StanzaOrg/slm-curl) - Make HTTPS requests
*  [libarchive](https://github.com/StanzaOrg/slm-libarchive) - Create Tar/Zip files
*  [libjson](https://github.com/StanzaOrg/slm-json) - Parse/Create [JSON](https://www.json.org/json-en.html) files/strings
*  [term-colors](https://github.com/StanzaOrg/term-colors) - Create Colored Text in the Commandline Terminal
*  [maybe-utils](https://github.com/StanzaOrg/maybe-utils) - Tools for working with `Maybe<>` types
*  [stanza-toml](https://github.com/StanzaOrg/stanza-toml) - Parse/Create [TOML](https://toml.io/en/) files/strings

# Utilities

* [jitx-emn-importer](https://github.com/JITx-Inc/jitx-emn-importer) - Import EMN files to code
