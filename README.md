# 👋 MoErgo Layer Buddy

[![Launch Layer Buddy](https://img.shields.io/badge/Launch-Layer_Buddy-0ea5e9?style=for-the-badge&logo=rocket)](https://moosylog.github.io/layerbuddy/)

A smart, beginner-friendly diagnostic tool for your MoErgo / Glove80 keyboard layouts. 

ZMK layer logic can be confusing. Layer Buddy analyzes your JSON layout backup, instantly finds hidden stacking bugs, and gives you a simple drag-and-drop Action Plan to fix them.

## ✨ What it catches

* 🥞 **Layer Stacking Bugs:** Finds keys trying to shift to lower layers (which get invisibly blocked by your current layer).
* 🚨 **Critical Logic Errors:** Catches empty parameters, broken references, and ghost layers.
* 🖱️ **Trackpad Priority Bugs:** Ensures Cirque trackpad speed modifiers aren't overridden by broad base layers.
* 🕸️ **Global Combo Traps:** Detects combos that trigger on *all* layers and accidentally lock up your board.
* 👻 **Orphaned Layers:** Identifies unused layers taking up memory.

## 🚀 How to use

1. Open the [MoErgo Web Editor](https://my.moergo.com/).
2. Go to **Settings** (⚙️) and click **Download Layout Backup** (it will save as a `.json` file).
3. Drop that file into [MoErgo Layer Buddy](https://moosylog.github.io/layerbuddy/).
4. Follow the green "Target Order" list to fix your layout!

---

*Note: This is an AI-assisted diagnostic tool designed to help you learn ZMK. While highly accurate, always double-check your setup in the official MoErgo editor!*
