# Project definition — Sakura Succubus 2 Vita

## Product and boundary
A PS Vita Ren'Py package shell for **Sakura Succubus 2**, the sequel to the first game. It supplies Vita metadata, LiveArea assets and installation guidance, not the original game content.

## Upstream and runtime
- Original game: [Sakura Succubus 2 on Steam](https://store.steampowered.com/app/1326000/Sakura_Succubus_2/).
- Runtime/tool lineage: [Ren'Py PSVita Distribution Tool](https://github.com/SonicMastr/renpy-vita).
- Original `game/` data is user-supplied and must not be redistributed from this repository.

## Users and target
PS Vita users installing through VitaShell. Firmware/runtime support remains a device-test claim.

## Install contract
The README specifies `ux0:/app/RNPYSS002/` as the original game's data destination. Keep the SFO identity aligned with this path.

## Architecture and dependencies
The repository is a static package shell: SFO, icon and background images, LiveArea template, startup image and instructions. The Ren'Py Vita runtime and licensed game data are external.

## Security and quality
The package validator checks SFO signature, PNG headers and safe LiveArea asset references. Keep the upstream boundary and source attribution explicit; English installation guidance is the supported documentation language.

## Verified baseline
Package metadata and wiki source are present; the original PC game is not. Automated structure checks do not prove Vita boot or gameplay.

## Release acceptance
Valid metadata/assets, consistent app identity and install path, source attribution, and recorded real-device install, boot, save/load and suspend/resume results.