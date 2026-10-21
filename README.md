# beltmatic-exchange-mod
A mod to share machines of your beltmatic world with .bmx files (JSON) so you can copy paste the machine of someone esle in your world. I vibe coded a site [disponible soon] to make it work correctly and where you can share you machines with everyone ! 
# Beltmatic Exchange Mod

A MelonLoader mod for Beltmatic that lets you export and import machine blueprints using the `.bmx` / `BMX1:` format.

## Features

- **F7 — Export:** Export a copied in-game blueprint to a `.bmx` file and copy its `BMX1:` representation to the Windows clipboard.
- **F8 — Import:** Import a `BMX1:` string from the system clipboard, or load the most recently modified `.bmx` file from the Imports folder.
- **Ctrl+V — Paste:** Place the imported blueprint using Beltmatic's native paste functionality.

## Requirements

- Beltmatic
- MelonLoader 0.7.3
- For compiling from source: .NET 6 SDK

## Installation

1. Install MelonLoader and launch Beltmatic once.
2. Download `BeltmaticExchange.dll` from the latest GitHub Release.
3. Place the DLL in the game's `Mods` folder.
4. Launch the game and load a save.

## Usage

### Export a blueprint

1. Copy a machine in Beltmatic with `Ctrl+C`.
2. Press `F7`.
3. Find the exported `.bmx` file in `UserData/BeltmaticExchange/Exports`, or paste the `BMX1:` string into Beltmatic Exchange site : bloubidi.eu

### Import a blueprint

1. Copy a `BMX1:` string from the website, or place a `.bmx` file in `UserData/BeltmaticExchange/Imports`.
2. Press `F8` in-game.
3. Press `Ctrl+V` to paste the blueprint.

## Compatibility

Tested by the author with Beltmatic 1.0.5 and MelonLoader 0.7.3.

## Disclaimer

This is a community-made mod and is not affiliated with the developers of Beltmatic.
