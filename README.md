# onex-emotes_list

A free, open-source emote data package for FiveM. This repository contains emote configuration files, animation references, prop definitions, and localization data. It is designed to be used as a dependency by emote menu resources such as [onex-emotes](https://onexscripts.com).

## Disclaimer

This repository contains references to native GTA V animation dictionaries and clips which are assets provided by Rockstar Games through the FiveM platform. This repository does not contain any proprietary code from any third party. Emote configuration data is community-maintained.

## Credits & Acknowledgments

Emote animation data in this repository was originally compiled by the community and includes contributions inspired by projects such as [rpemotes-reborn](https://github.com/alberttheprince/rpemotes-reborn). This repository is licensed under GPL-3.0 in compliance with upstream licensing.

## Important Notice

This is a free, standalone data package. It is **NOT** the Onex Emote Menu product. The paid onex-emotes resource (menu UI, frontend, backend logic) is a separate, independently developed product by Onex Scripts.

## Repository Structure

- **`config/`** — Core emote configuration files
  - `emotes/` — Categorized emote definitions (animal, consumable, dance, exit, general, prop, shared)
  - `expressions.lua` — Facial and character expression definitions
  - `scenarios.lua` — Scenario-based emote and action definitions
  - `walks.lua` — Walk style definitions
  - `scenario_models.lua` — Model definitions used in scenarios

- **`locales/`** — Localization and translation files
  - Supported languages: English, French, German, Spanish, Arabic, Polish, Turkish

- **`stream/`** — Streamed GTA/FiveM asset files
  - `[Animations]/` — Custom animation packs from various creators
  - `[Props]/` — Custom prop assets

## Contributing

Community contributions and translations are welcome! Please submit pull requests to improve emote definitions, add new animations, or fix issues.

## License

This project is licensed under the **GNU General Public License v3.0**. See the [LICENSE](./LICENSE) file for full details.
