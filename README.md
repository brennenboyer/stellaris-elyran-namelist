# 🌌 Elyran Name List (Planetary Diversity Dependency)

Welcome to the official repository for the **Elyran Name List** mod for Stellaris. This page contains the complete source code, folder layout, and interactive database files cataloging every name in the compilation.

## 🚀 Steam Workshop Link
* 👉 **[Click here to view this Mod on the Steam Workshop](https://steamcommunity.com)**

---

## 📋 Complete Scrollable Namelist Sheets
Because the Elyran dataset contains thousands of separate custom variations, the full content is broken up into completely scrollable interactive matrices below. Click on any file to open up the scroll screens natively inside your web browser:

* 🪐 **[Click here to view the complete Planet Biome & World Dataset](./planetary-diversity-database.csv)** *(Featuring all Planetary Diversity variants, Cavern worlds, Eyeball/Tidally Locked biomes, and unique sub-classes!)*
* 🛸 **[Click here to view Starship Classes & Combined Fleets](./starships-and-fleets.csv)**
* 👥 **[Click here to view Character Nomenclature & Royal Dynasties](./characters-and-dynasties.csv)**
* 🪖 **[Click here to view Combined Ground Forces & Catalyst Systems](./armies-and-species-catalyst.csv)**

---

## 🔍 Quick Previews
Click on any of the categories below to expand a short preview snippet of the database layout.

<details>
<summary>🪐 1. Planetary Diversity Biome Matrix Preview (Click to expand)</summary>

| Climate Zone | Core Planet Biome | PD Regional Variant | Designation Variant Alpha | Designation Variant Beta |
| :--- | :--- | :--- | :--- | :--- |
| **WET** | Continental | Retinal | Iris | Aurora |
| **WET** | Continental | Lake | Halea | Eden |
| **WET** | Continental | Forest | Verdant | Sylvaris |
| **WET** | Ocean | Mushroom | Myrkr | Iskera |
| **DRY** | Desert | Dune | Surtr | Haven |
| **DRY** | Arid | Mesa | Mesa | Byss |
| **COLD** | Arctic | Ice Spike | Crythe | Glacien |
| **CAVERN** | Gaia Cavern | Wet Cavern | Eden | Eden |

*(The complete layout features deep optimization rules automatically naming custom variants including Superhabitables, Subglacial Hydrocarbons, Chthonian relics, and Ringworld fragments!)*
</details>

<details>
<summary>🛸 2. Spacecraft & Fleet Title Preview (Click to expand)</summary>

| Construction | Science | Colonizer | Corvette | Destroyer | Cruiser | Battleship | Titan |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Sanctuary | Inspiration | Haven | Who Dares Wins | Point of No Return | Crusading Spirit | Wrath | Spirit of Fire |
| Sojourner | Faith | Solace | Shall Not Perish | Unto the Breach | Light of Faith | Revelation | Shadow of Intent |
| Opportunity | Wonder | Sanctuary | Only the Good | Dying Light | Light of Ascension | Judgement | Forward unto Dawn |

</details>

---

## 🛠️ Mod Architecture & Structure
Other modders are free to look over the directory layout below to see how localization files tie into the **Planetary Diversity** hooks:
* `/common/name_lists/` — Contains the internal backend game variables matching structural lists.
* `/localisation/` — Holds the translated string descriptions for seamless in-game rendering.
* `elyrannamelistnscpd.zip` — Compiled binary build ready for production profiling.

## 📄 License
This project is shared under the **MIT License**. You are entirely free to copy, modify, and integrate this code into your own Stellaris creations, provided original attribution credit is maintained.
