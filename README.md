# Imperfect Gamers [IG] - Models Plugin

A plugin for handling player models for CounterStrikeSharp.

---

## Requirements
- [CounterStrikeSharp](https://github.com/roflmuffin/CounterStrikeSharp)

---

## Installation
- Download the latest release from [here](https://github.com/razpbrry/Imperfect-Models/releases)
- Unzip and place into your servers `game/csgo/` directory

---

## Configuration

After installation and initial run of the plugin, a configuration file will be created in the `game/csgo/addons/counterstrikesharp/configs/plugins/ImperfectModels/` directory.

`DefaultAlpha` - This will be the default setting of the alpha (transparency) value for all player models. Use a number between 1 and 255. Any value under 254 will disable legs from being visible in first-person view.

---

## Commands

### Set All Player Models Alpha
**This will set the model alpha value for all connected player models**

Type `css_setmodelalpha <number>` in console (server or client)

Type `!setmodelalpha <number>` in chat

`<number>` must be a number between 1 and 255