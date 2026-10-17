# Deadlock Dialogue Player — Simplified Chinese

[简体中文](README.md) · [Download on GameBanana](https://gamebanana.com/mods/728026)

An unofficial Simplified Chinese text patch for Deadlock's in-game Dialogue Player.

The project targets character conversations and the voice-line categories actually available in the player, including hero selection, abilities, items, kills, allies, enemies, reactions, match lines, and pings. It does not aim to translate every text resource in the game.

## Download

Download the current package from [GameBanana](https://gamebanana.com/mods/728026). This repository currently contains documentation, progress records, and feedback templates. It does not include a VPK download, the full translation source, or build source code.

The maintainer-provided current release version is **3.1**. Check the download page and archive before installing.

## Translation and review

According to the maintainer's production notes, this edition was translated from the game's original English material using DeepL, with selected entries and complete conversations manually proofread by H4R3, Sixseven, and Mina. Official Chinese terminology was used as a reference for names and established terms.

Manual review does not cover every entry, and not every voice line has been manually checked against its audio. Translation errors, missing subtitles, and unresolved entries may remain. See [production and review notes](docs/PROVENANCE.md).

## Progress

These figures reproduce the maintainer-provided release 3.1 notes, recorded on 2026-10-17. They have not been independently recounted from the current download package.

| Measure | Count |
|---|---:|
| Target scope | 74,269 subtitle keys |
| Translated | 72,235 subtitle keys |
| Manually reviewed | 9,222 subtitle keys |
| Complete conversations manually reviewed | 360 |
| Pending or unresolved | 3,047 subtitle keys |

Pending entries include translated entries that still require confirmation, so these counts overlap. Do not add them to calculate coverage. Conversation groups and subtitle keys are different units. See [progress.json](progress.json).

## Installation

1. Download and extract the ZIP archive from GameBanana.
2. Import the included VPK into your Deadlock mod loader.
3. Disable any older version of this patch, then enable the new version.
4. Set the game language to Simplified Chinese and launch through your mod loader.
5. Open the Dialogue Player.

To uninstall, disable or remove this patch in your mod loader. DeepL, Python, and translation models are not required to use the patch.

The patch replaces the shared `citadel_generated_vo_schinese.txt` resource, so matching subtitles may also change outside the player. Do not enable conflicting mods or multiple versions of this patch simultaneously.

Text only: no replacement audio, character models, or mod loader is included. Game updates may require a patch update.

## Feedback

Chinese and English reports are welcome through this repository's Issue templates or on [GameBanana](https://gamebanana.com/mods/728026).

Include the patch version, character names, category, full conversation, and a screenshot. The original English line or a short audio clip is helpful when available. Do not upload account information, credentials, or entire game resource archives.

## Credits

- **H4R3** — Project coordination, manual proofreading, playtesting, and release management.
- **Sixseven and Mina** — Manual proofreading and playtesting.
- Original game and content — **Valve / Deadlock**. This is an unofficial project and is not endorsed by Valve.

## Repository scope and permissions

The initial repository contains documentation and feedback templates. AI assistance was used to organize the repository copy; this note is not a technical verification of the translation's production history.

Original game audio, models, complete localization source files, working databases, and translation models are not included. No open-source license has been designated for this repository. Public visibility does not itself grant unrestricted reuse or redistribution. Original game content belongs to its respective rights holders.

[Changelog](CHANGELOG.md) · [Contributing](CONTRIBUTING.md) · [Maintenance](docs/MAINTENANCE.md)
