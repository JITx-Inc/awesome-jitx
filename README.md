# Awesome JITX

This is a collection of helpful code libraries for designing circuit boards with [JITX](https://www.jitx.com/).

# Contents

*  [How to Use](#how-to-use) - Instructions for using Packages
*  [Circuits](#circuits) - Code for generating common circuits like filters, and power regulators
*  [Components](#components) - Component Libraries, Generators, etc
*  [Fabrication](#fabrication) - Stackups and Constraints for Fabricators
*  [Libraries](#libraries) - Common utilities like curl

# How To Use

The best way to use many of these projects is through the [slm](https://github.com/stanzaorg/slm) library manager. Each repository will include installation instructions

# Circuits
*  [Power Systems](https://github.com/JITx-Inc/power-systems) - Architectures and solvers for DC/DC power regulation, and power filters

# Components

*  [Connectors](https://github.com/JITx-Inc/connectors) - Helpful connectors like USB, and terminal blocks, mapped to standard interfaces
*  [Diodes](https://github.com/JITx-Inc/diodes) - Diodes including zeners and ESD arrays.
*  [FTDI](https://github.com/JITx-Inc/FTDI) - Circuits for FTDI components, including parts like the FT2232HL
*  [Microchip Networking](https://github.com/JITx-Inc/microchip-networking/tree/main) - Circuits for Microchip networking devices, including ethernet switches
*  [TI-vreg](https://github.com/JITx-Inc/TI-vreg) - Voltage regulators from Texas Instruments

# Fabrication

*  [JLC PCB](https://github.com/JITx-Inc/jlc-pcb) - Stackups, vias, and impedance controlled designs for JLCPCB

# Libraries

*  [libcurl](https://github.com/StanzaOrg/slm-curl) - Make HTTPS requests
*  [libarchive](https://github.com/StanzaOrg/slm-libarchive) - Create Tar/Zip files
*  [libjson](https://github.com/StanzaOrg/slm-json) - Parse/Create [JSON](https://www.json.org/json-en.html) files/strings
*  [term-colors](https://github.com/StanzaOrg/term-colors) - Create Colored Text in the Commandline Terminal
*  [maybe-utils](https://github.com/StanzaOrg/maybe-utils) - Tools for working with `Maybe<>` types
*  [stanza-toml](https://github.com/StanzaOrg/stanza-toml) - Parse/Create [TOML](https://toml.io/en/) files/strings
