# Awesome JITX

[JITX](https://www.jitx.com/) is a EDA tool for making Software Defined Electronics.


# Contents

*  [How to Use](#how-to-use) - Instructions for using Packages
*  [Components](#components) - Component Libraries, Generators, etc
*  [Circuit Interfaces](#circuit-interfaces) - Standardized Circuit Interface for Interop
*  [Specifications](#specifications) - Standard body definitions such as PCIe, MIPI, HDMI, etc
*  [Fabrication](#fabrication) - Stackups and Constraints for Fabricators
*  [Libraries](#libraries) - 

# How To Use

The best way to use many of these projects is through the [slm](https://github.com/stanzaorg/slm) library manager. Typically, you would run the following command in your JITX project: 

```bash
$> slm add -git JITx-Inc/xilinx
```


# Components

*  [Xilinx Pinout Generator](https://github.com/JITx-Inc/xilinx) - Xilinx FPGA Component and Circuit Generator
*  [STM32 Generator](https://github.com/JITx-Inc/stmicro) -  STM32 microcontrollers Component Generator
*  

# Circuit Interfaces

*  [555 Timer Circuits](https://github.com/JITx-Inc/timers) - 555 Circuit Interface & Function Definitions
*  [Opamp Filters](https://github.com/JITx-Inc/OpAmpFilters) - OpAmp-based Active Filters
*  [Passive Filters](https://github.com/JITx-Inc/PassiveFilters) - Passive RC and LC Filters
*  

# Specifications

*  [PCIe Interface](https://github.com/JITx-Inc/PCIe-spec) - PCIe Bundle and Constraints
*  [HDMI Interface](https://github.com/JITx-Inc/HDMI-spec) - HDMI Bundle and Constraints
*  [MIPI Interface](https://github.com/JITx-Inc/MIPI-spec) - MIPI Bundle and Constraints

# Fabrication

*  [Sierra Circuits](https://github.com/JITx-Inc/SierraCircuits) - Stackups and Routing Structures
*  [Advanced Circuits](https://github.com/JITx-Inc/AdvancedCircuits) - Stackups and Routing Structures
*  [JLC PCB](https://github.com/JITx-Inc/JLC-PCB) - Stackups and Routing Structures

# Libraries

*  [libcurl](https://github.com/StanzaOrg/slm-curl) - Make HTTPS requests
*  [libarchive](https://github.com/StanzaOrg/slm-libarchive) - Create Tar/Zip files
*  [libjson](https://github.com/StanzaOrg/slm-json) - Parse/Create [JSON](https://www.json.org/json-en.html) files/strings
*  [term-colors](https://github.com/StanzaOrg/term-colors) - Create Colored Text in the Commandline Terminal
*  [maybe-utils](https://github.com/StanzaOrg/maybe-utils) - Tools for working with `Maybe<>` types
*  [stanza-toml](https://github.com/StanzaOrg/stanza-toml) - Parse/Create [TOML](https://toml.io/en/) files/strings