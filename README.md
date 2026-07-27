# BepInExZips
Premade BepInEx Zips for LotusContinued's Release Workflow

## Information
- x64.zip is for Among Us releases which are 64-bit, which are currently the **Epic Games** and **Microsoft Store** versions of the game.
- x86.zip are for releases which are 32-bit, which are the **Steam** and **Itch.io** releases of the game.

These versions use BepInEx version 6.0.0-752, from https://builds.bepinex.dev<br />

However, they include a modified winhttp.dll and doorstop config from https://github.com/Pietrodjaowjao/UnityDoorstop, which disables the Incremental Garbage Collector due to issues it brought with version 17.4 of Among Us.

Other content in the zip files are for stuff related to Lotus (`/LOTUS_DATA`, `/addons/LotusCosmetics.dll`, etc.)
