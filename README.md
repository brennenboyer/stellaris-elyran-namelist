# 🌌 Elyran Name List (Planetary Diversity Dependency)

Welcome to the official repository for the **Elyran Name List** mod for Stellaris. This page contains the complete source code, folder layout, and links to interactive databases for every custom name included in this pack.

## 🚀 Steam Workshop Link
* 👉 **[Click here to view this Mod on the Steam Workshop](https://steamcommunity.com)**

---

## 📋 Comprehensive Namelist Worksheets
The complete Elyran dataset contains thousands of names! Since the dataset stretches down hundreds of rows, you can browse the fully scrollable, interactive databases directly inside your web browser here:

* 🛸 **[Click here to view Starship & Fleet Class Names](./starships-and-fleets.csv)**
* 👥 **[Click here to view Character Names & Imperial Dynasties](./characters-and-dynasties.csv)**
* 🪖 **[Click here to view Armies, Species, & Celestial Catalyst Registries](./armies-and-species-catalyst.csv)**

---

## 🔍 Quick Previews
Click on any of the categories below to expand a short preview sample of what is inside the data files.

<details>
<summary>🛸 1. Spacecraft & Starship Class Preview (Click to expand)</summary>

| Construction | Science | Colonizer | Sponsored Colonizer | Corvette | Destroyer | Cruiser | Battleship | Titan | Colossus | Juggernaut | Transport | Defense Platform | Ion Cannon |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Sanctuary | Inspiration | Haven | Haven | Who Dares Wins | Point of No Return | Crusading Spirit | Wrath | Spirit of Fire | Leviathan | Marathon | Conveyance | Redoubt | Obliterator |
| Sojourner | Faith | Solace | Solace | Shall Not Perish | Unto the Breach | Light of Faith | Revelation | Shadow of Intent | Harbinger | Justice | Lifter | Ward | Anvil |
| Opportunity | Wonder | Sanctuary | Sanctuary | Only the Good | Dying Light | Light of Ascension | Judgement | Forward unto Dawn | Overlord | Fury | Carrier | Palisade | Thunderhead |
| Providence | Hope | Promise | Promise | Seeker of Fortune | To Boldly Go | Guiding Hand | Retribution | All Under Heaven | Paragon | Dominion | Convoy | Strongpoint | Hammerfall |
| Salvation | Curiosity | Dawn | Dawn | Arm of the Law | Swift Reckoning | Steadfast Resolve | Vengeance | Pillar of Autumn | Cataclysm | Sentinel | Transitor | Shieldpost | Starbreaker |

*(Note: Hundreds of additional custom tactical titles like "Hold the Line", "No Retreat Given", and "Edge of Reason" are built dynamically into the main data file!)*
</details>

<details>
<summary>🪐 2. Planetary Diversity & World Preview (Click to expand)</summary>

| Planet Class | Regional Variant | Mythological Designation (A) | Mythological Designation (B) | Faction Anchor (C) | System Hub (D) | Sector Hub (E) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Continental | Retinal | Iris | Aurora | Auralis | Kaleido | Lucent |
| Continental | Lake | Halea | Eden | Haven | Harmony | Demeter |
| Continental | Forest | Verdant | Sylvaris | Harvest | Veridian | Verdan |
| Continental | Tepid | Eden | Harmonis | Harmony | Haven | Gaea |
| Ocean | Mushroom | Myrkr | Iskera | Soryth | Karkaris | Sarkosis |

*(Fully integrated to handle specialized Planetary Diversity variants including Cavern Worlds, Tidally Locked Hemispheres, Exotic/Exogol classes, Relic Worlds, and Artificial Megastructures!)*
</details>

<details>
<summary>👥 3. Character Names & Regnal Dynasties Preview (Click to expand)</summary>

### Standard Citizen Nomenclature
* **Male First Names:** Aren, Calen, Darik, Joren, Kael, Larek, Maren, Rykon, Sethis, Torin, Varek, Xalen...
* **Female First Names:** Aria, Lyra, Vela, Nyra, Kira, Alara, Selene, Maris, Talia, Elira, Rynna, Saren...
* **Surnames / Second Names:** Valeris, Kaelorn, Soryn, Tavrek, Orendis, Halvek, Cindral, Varyx, Telmar, Avenor...

### Imperial Regnal Formats
* **Male Monarchs:** Aleron, Aurek, Caelor, Edrik, Daarion, Maeron, Rhaelor, Theron, Tiberan, Vaelor...
* **Female Monarchs:** Aelyra, Aurelia, Calyra, Elaria, Elaryn, Ilyra, Kaerith, Lyssara, Maerith, Naelyra...
* **Royal Dynasty Surnames:** Valecor, Caelorn, Teryndor, Loraven, Talvaren, Vaelorn, Ardelon, Otharyn...
</details>

---

## 🛠️ Mod Architecture & Structure
Other modders are free to look over the directory layout below to see how localization files tie into the **Planetary Diversity** hooks:
* `/common/name_lists/` — Contains the internal backend game variables matching structural lists.
* `/localisation/` — Holds the translated string descriptions for seamless in-game rendering.
* `elyrannamelistnscpd.zip` — Compiled binary build ready for production profiling.

## 📄 License
This project is shared under the **MIT License**. You are entirely free to copy, modify, and integrate this code into your own Stellaris creations, provided original attribution credit is maintained.
