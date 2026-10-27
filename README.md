# Exile Election: English Translation Patch (PS Vita)

An unofficial English fan translation of **追放選挙 (Exile Election)** for the
PlayStation Vita (title ID `PCSG01023`).

**Current version: v0.9.0 (beta).** The whole story is translated and has been
tested in an emulator, but nobody has finished a full playthrough on a real
Vita yet. Expect some rough edges, and please report them.

**About this translation:** The English was produced with AI and checked
against the Japanese in several full review passes. It hasn't been reviewed by
a professional translator. If a line reads wrong or seems off, please report
it.

## Download

Get `Exile_Election_English_v0.9.0.zip` from the
[Releases page](https://github.com/gabew100/Exile-Election-English/releases).

## What's translated

- All story text: 38,708 lines across 255 scenes
- Menus, settings, and scene titles
- The in-game controls and help screens

## Still in Japanese

- Text drawn into some background and event pictures
- The two movies
- The title logo (kept on purpose)
- The home-screen (LiveArea) bubble and trophies
- The game manual

## Requirements

- The rePatch plugin. Tested with rePatch reLoaded; rePatch reDux0 uses the
  same folder and should also work.
- Your own copy of 追放選挙 (`PCSG01023`). The game never received an update,
  so any copy works.

## Install

1. Download the ZIP from the Releases page and unzip it on your PC. You'll get
   a `rePatch` folder.
2. Copy the `rePatch` folder to the root of `ux0:` (for example with VitaShell
   over USB or FTP), so the files end up in `ux0:rePatch/PCSG01023/`. If you
   already have a `rePatch` folder, merge them.
3. Start the game.

**Saves:** back up your save data first. Starting a new game is recommended.
Saves from the Japanese version haven't been tested with the patch.

**Controls:** like most Japanese games, Circle (○) confirms and Cross (×)
cancels or goes back.

## Uninstall

Delete `ux0:rePatch/PCSG01023/`.

## Known issues

- No full playthrough on real hardware yet.
- Some lines may still be slightly off from the Japanese. Reports are welcome.

## Troubleshooting

- **Nothing changed in the game:** check that the rePatch plugin is enabled in
  your taiHEN `config.txt` and that the files are under
  `ux0:rePatch/PCSG01023/`.
- **A line reads wrong:** open an issue with the line's text (or a
  screenshot), what's wrong, and what you think it should say.

## Checksums

Each release lists the SHA-256 of its ZIP in the release notes.

## License

The patch is distributed under the terms in [LICENSE](LICENSE). The game and
its original assets remain the property of their respective rights holders.
This is an unofficial fan project, not affiliated with or endorsed by Nippon
Ichi Software. You need your own copy of the game.
