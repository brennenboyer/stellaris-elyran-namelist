# 🌌 Elyran Name List

The **Elyran Name List** is a Stellaris mod with names for ships, planets, characters, species, stars, homeworlds, fleets, and armies. Its planet names cover vanilla worlds and **Planetary Diversity** variants.

This repository makes the name data easy to browse and reuse. Open any CSV below to see the full list in GitHub's file viewer, or download it for a spreadsheet program.

## 📋 Browse the names

| File | Contents |
| :--- | :--- |
| 🛸 [ships.csv](./ships.csv) | Ship names and ship class names, grouped by type. |
| 🪐 [planets.csv](./planets.csv) | One name per row, with climate zone, core biome, and planet variant. Includes generic names. |
| 👥 [people.csv](./people.csv) | First and second names, including regnal names. |
| 🧬 [species.csv](./species.csv) | Species names with plural and adjective forms. |
| ✨ [stars-homeworlds.csv](./stars-homeworlds.csv) | Star and homeworld name pools. |
| 🪖 [fleets-armies.csv](./fleets-armies.csv) | Fleet names and army names by type. |

Each file comes from the corresponding sheet in the Elyran workbook. Blank cells in the wide category sheets mean that category has no name on that row; they do **not** indicate a relationship between names in different columns. `planets.csv` rearranges the workbook's wide matrix into a searchable list. A blank biome or variant means the source did not specify one, as with generic names.

## 🔍 Quick previews

<details>
<summary>🪐 Planet names</summary>

| Climate Zone | Core Planet Biome | Planet Variant | Planet Name |
| :--- | :--- | :--- | :--- |
| WET | Continental | Retinal | Iris |
| WET | Continental | Retinal | Aurora |
| WET | Continental | Lake | Halea |
| WET | Continental | Forest | Verdant |
| DRY | Desert | Dune | Surtr |

</details>

<details>
<summary>🛸 Ship names</summary>

| Construction | Science | Colonizer | Corvette | Destroyer | Cruiser | Battleship | Titan |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Sanctuary | Inspiration | Haven | Who Dares Wins | Point of No Return | Crusading Spirit | Wrath | Spirit of Fire |
| Sojourner | Faith | Solace | Shall Not Perish | Unto the Breach | Light of Faith | Revelation | Shadow of Intent |

</details>

## 🛠️ Using the data

The CSVs are reference data. If you are adapting the names for a Stellaris mod, put them into the game's name list and localisation format; Stellaris does not load these CSVs directly. The columns in the wide files represent separate name pools, so keep their category labels when converting them.

## 🚀 Steam Workshop

👉 [Elyran Name List on the Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3806576947)

## 📄 License

Released under the [MIT License](./LICENSE). You may use, modify, and redistribute the data with the required copyright and license notice.

## 🕶️ Stealth Mod Menu (development build)

The Elyran development build also contains the **Meridian Stealth Mod Menu**, an optional set of multiplayer admin and testing controls. On a new multiplayer game, the first human player to receive configuration authority gets a choice to enable the controls or continue with standard settings. The edicts are hidden from AI and from players without admin access. This is an experimental compatibility mode; it may affect stability and save compatibility.

<details>
<summary>View Stealth Mod Menu features</summary>

- **Stealth and intelligence:** Omega Cloaking Theory and its +10 Cloaking Strength generator; cloak controls for supported juggernauts, civilian, colony, logistics, and engineer ships; a one-click Omega unlock; cloaking strength, encryption, codebreaking, sensor coverage, first-contact and spy-network acceleration, and espionage boosts. The Sensor Jamming unlock adds the Veilkeeper Array starbase building, which blocks outside sensor scanning into its system and weakens hostile ships there.
- **Exploration and travel:** Reveal or survey the galaxy, accelerate surveys and anomaly research, establish communications, boost movement, and enable long-range Tactical Jumps.
- **Economy and development:** Toggle resource and Influence generation, Minor Artifact and Astral Thread production, extra storage, research speed, faster construction, fleet upgrades, colony development, terraforming, and population growth. Planet decisions clear blockers, add district capacity, or apply Planetary Perfection.
- **Leaders and empire:** Expand leader capacity, adjust upkeep and experience gain, remove negative traits, raise leaders to level 10, increase Edict Fund, reduce Empire Size, control stability and crime, and boost naval and starbase capacity.
- **War and diplomacy:** Admin fleet sustainment, emergency war mobilization, several Diplomatic Weight tiers, Federation Cohesion and XP controls, Galactic Favors, and Galactic Community proposal controls.
- **Utilities:** Policy and relic cooldown controls, repeated relic activations, and a one-shot Stealth Reset that reduces unusually large stockpiles.

Most ongoing effects are toggleable edicts; one-shot unlocks and resets are labeled separately in game. The included Omega integration expects **NSC3** to load first and uses **First Contact** for the custom cloak controls. The development archive was used to document these features; its mod files are not included in this repository.

</details>
