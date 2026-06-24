# 🪟 Atenea Furniture Fix — .ytyp Packages

Alternative `.ytyp` files to fix dark or pitch-black furniture assets inside custom MLOs with broken or aggressive timecycles.

![version](https://img.shields.io/badge/version-v2026-orange) ![platform](https://img.shields.io/badge/platform-Windows%20%2F%20FiveM-blue) ![license](https://img.shields.io/badge/license-Atenea%20Store%20Tools-yellow)

---

## 🔍 Why Do Furniture Props Appear Dark or Black?

By default, all our furniture assets are perfectly configured with the standard GTA V interior flag called **Use Ambient Scale**. This flag is strictly necessary for standard interiors; without it, textures would glow intensely in the dark as if they were emissive or neon when placed via housing systems.

However, certain custom MLOs from specific creators use broken, unoptimized, or extremely aggressive timecycles. In these specific maps, the custom timecycle overrides and breaks the ambient multipliers. Because of how those maps are coded, having **Use Ambient Scale** enabled backfires, causing the game engine to render our furniture as completely pitch black or unlit.

---

## 📦 Repository Contents

| File / Folder | Description |
| :--- | :--- |
| `[ytyp_files]` | ⚠️ **Fixed files** with **Use Ambient Scale** deactivated for custom MLOs. |
| `README.md` | This documentation file. |

> ⚠️ **Important Note:** Only apply this patch if you experience the pitch-black texture issue inside specific custom maps. If your furniture looks correct, you do not need this fix.

---

## 🚀 How to Use & Apply the Fix

### Step 1 — Locate your resource
* Go to your server's `resources` folder.
* Open the `stream` folder of the **Atenea Store®** furniture pack that is rendering dark or black.

### Step 2 — Get the fixed file
* Look inside this repository and download the specific `.ytyp` file that matches the name of your package.

### Step 3 — Overwrite and Replace
* Drag and drop the fixed `.ytyp` file into your asset's `stream` folder.
* Confirm and **overwrite** the original file.

### Step 4 — Clear Cache and Restart
* Delete your server's `cache` folder to force FiveM to reload the new asset metadata.
* Restart the furniture resource or restart your server.
