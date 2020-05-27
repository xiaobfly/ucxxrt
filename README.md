# Universal C++ RunTime (UCXXRT)

[![LICENSE](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/MiroKaku/ucxxrt/blob/master/LICENSE)
[![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg)](https://github.com/996icu/996.ICU/blob/master/LICENSE)

## About UCXXRT

C ++ runtime library that supports both user-mode and kernel-mode.

### Support for kernel mode C ++ exceptions. Support STL for kernel mode

## How to used?

1. Build it
2. Copy ucxxrt/ucxxrt folder to your project.
3. Add Existing Property Sheet, select ucxxrt.props

    ![Add Property Sheet](https://github.com/MiroKaku/ucxxrt/raw/master/readme/add_props.png)

### If in driver mode, rename "**DriverEntry**" to "**DriverMain**".
