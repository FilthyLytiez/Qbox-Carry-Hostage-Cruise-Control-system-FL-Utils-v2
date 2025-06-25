# 🚀 FL Utils v2 — Qbox Optimized Utility Pack

Welcome to **FL Utils v2**, a South African–flavoured utility script designed for **Qbox** (QBCore-based) servers. This all-in-one pack includes Carry, Hostage, and Cruise Control systems — fully optimized, fully synced, and full of kasi vibes. 🇿🇦🔥


## 📦 Features

### 🏋️ Carry System
- Carry or be carried like a true bru
- Works with animation syncing
- Distance checks and cancel handling
- `/carry` command or keybind (`Y` by default)

### 🎯 Hostage System
- Take NPCs or players hostage with any strap
- Kill or release them with intuitive controls
- Includes cooldowns, max range, weapon checks, and immersive animations
- `/takehostage` or keybind (`F10` by default)

### 🏎️ Cruise Control
- Toggle cruise on the fly
- Automatic max-speed detection
- `/cruisecontrol` or keybind (`F9` by default)

---

## 🛠️ Requirements

- [ox_lib](https://overextended.dev/)
- [qbx_core](https://github.com/qbox-project/qbx-core)

---

## ⚙️ Configuration

Edit `config.lua` to adjust:
- Keybinds
- Animation dictionaries
- Enabled features
- Localised South African-style notifications 🗣️

Example:

carryStarted = "Awu jita! You're now carrying this laaitie",
hostageKilled = "Jerr! You just dropped that one like it's hot",


🔧 Installation

To install **fl_utils_v2**, follow these steps carefully:

1. 🗂️ Drag & Drop
Place the entire `fl_utils_v2` folder into your `resources/[local]/` directory.


2. 📜 Ensure Dependencies

You **must** have the following installed and started **before** this script:
- [`ox_lib`](https://overextended.dev/)
- [`qbx_core`](https://github.com/qbox-project/qbx-core)

3. 🧾 Add to server.cfg

In your `server.cfg`, start the script **after** `ox_lib` and `qbx_core` like this:

-cfg
ensure ox_lib
ensure qbx_core
ensure fl_utils_v2
4. 🛠️ Configure (Optional)
Open config.lua and:

Enable/disable features: carry, cruise control, hostage

Adjust keybinds

Customize notifications with your own slang and style

5. ✅ You're Done
Restart your server or use /restart fl_utils_v2 in console.
You should now be able to:

Use /carry or press Y

Use /takehostage or press F10

Use /cruisecontrol or press F9

If you run into issues, join our support server:
👉 https://discord.gg/FDKudWACcQ

Danko for installing! May your RP be wild, synced, and full of moering. 🇿🇦

