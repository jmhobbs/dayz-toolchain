---
title: DayZ Toolchain
summary: An open-source toolchain for building and packaging DayZ mods.
---
The DayZ Toolchain is a project to create a free, open-source toolchain for building and packaging DayZ mods, independent of Bohemia Interactive's official tools.

The goal is to provide modders with an alternative path to building their mods, encouraging the use of version control and CI/CD for mod development.

## Existing

- [pbotool](https://github.com/jmhobbs/go-pbo) - A tool for working with PBO files, including inspecting, packing and unpacking.
- [dayz-mod-build](https://github.com/jmhobbs/dayz-mod-build) - A tool for building DayZ mod files from source materials.

## In Progress

- [go-bisign](https://github.com/jmhobbs/go-bisign) - A tool for managing DayZ compatible RSA keys and signing PBO files.
- [go-raP](https://github.com/jmhobbs/go-raP) - A tool to convert between text and raP formats of config files.
- [go-bicpp](https://github.com/jmhobbs/go-bicpp) - A parser for Bohemia Interactive `.cpp` files.
- [go-p3d](https://github.com/jmhobbs/go-p3d) - A tool for working with P3D model files.

## Planned

- go-paa - A tool to work with PAA texture files.

## Go Modules

All tools (except dayz-mod-build) are also available ar Go modules, allowing for custom tooling or use in other contexts.
