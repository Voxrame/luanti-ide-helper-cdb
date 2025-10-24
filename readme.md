# Luanti IDE Helper as Mod
[![Maintained By: Lord Team](https://img.shields.io/badge/Maintained%20By-Lord%20Team-659b4b?style=for-the-badge)](https://github.com/lord-server/lord?tab=readme-ov-file#contributors--%D1%83%D1%87%D0%B0%D1%81%D1%82%D0%BD%D0%B8%D0%BA%D0%B8)
[![Donate: Boosty](https://img.shields.io/badge/Donate-Boosty-f15f2c?style=for-the-badge)](https://boosty.to/lord-server)
[![License: MIT](https://img.shields.io/badge/License-MIT-444?style=for-the-badge)](./license.md)

This package is intended for developers only.  
Package for developers providing precise autocompletion and documentation for Luanti (Minetest) API in various IDEs.

![Demo](https://github.com/Voxrame/luanti-ide-helper/blob/master/luanti-ide-helper.gif?raw=true)

# Installation
## Prerequisites
Before installing, make sure you have one of the following extention/plugin installed:
 - for IntelliJ IDEA (or compatible): [EmmyLua2 Plugin](https://plugins.jetbrains.com/plugin/25076-emmylua2)
 - for VS Code:
   - [EmmyLua Extension](https://marketplace.visualstudio.com/items?itemName=tangzx.emmylua) (recommended for VS Code)
   - or [Lua Language Server](https://marketplace.visualstudio.com/items?itemName=sumneko.lua)
 - Any editor with LSP support.  
   Install Lua LS: `cargo install emmylua_ls` (or see [instalation guide](https://github.com/EmmyLuaLs/emmylua-analyzer-rust?tab=readme-ov-file#-installation))


## As a mod
> #### ⚠️ We do not recommend installing this package as a mod.

But this is the easiest way to quickly try out.
For complete installation instructions and IDE configuration, please visit [our GitHub repository](https://github.com/Voxrame/luanti-ide-helper).

If you installing this package as a mad in your game or modpack, we recommend to add it to git ignored files:
```conf
# .gitignore
mods/luanti_ide_helper
# or
luanti_ide_helper
```

## As a local copy
See ["For Mod Developers"](https://github.com/Voxrame/luanti-ide-helper?tab=readme-ov-file#for-mod-developers) section.

## As a part of project
See ["For Game Developers"](https://github.com/Voxrame/luanti-ide-helper?tab=readme-ov-file#for-game-developers) section.