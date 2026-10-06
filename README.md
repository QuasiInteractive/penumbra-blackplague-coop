# Penumbra: Black Plague + Requiem Co-op

Online co-op for up to four players in **Penumbra: Black Plague** and **Penumbra: Requiem**, running on the original, untouched games. Nothing in the game folder is changed: the add-on lives in its own `coop` folder next to the game.

By [Quasi Interactive](https://quasi-interactive.com). Join the [Discord](https://discord.gg/Hbxchnyr3) to find people to play with or to report problems.

Looking for *Penumbra: Overture* co-op? That is its own project: [penumbra-overture-coop](https://github.com/QuasiInteractive/penumbra-overture-coop).

## Download

Grab the zip from the [latest release](https://github.com/QuasiInteractive/penumbra-blackplague-coop/releases/latest).

## Install

1. Open your Penumbra: Black Plague folder and go into `redist` (the folder with `Penumbra.exe` and `Requiem.exe` in it).
2. Drag the `coop` folder from the zip into `redist`.
3. Play from `coop\Black Plague Co-op.exe` or `coop\Requiem Co-op.exe`.

There is also a `secret` folder in the zip. Have a look.

## Play

Main menu, then **Multiplayer**. One player hosts (**Host**, then **Start**), the others **Join** by IP or pick the game from the server browser. The host needs UDP port 7790 open or forwarded. Hold **V** to talk.

- Up to four players, each a different character, with voice chat that comes from where they stand.
- Items one player picks up go into everyone's inventory. Doors, switches, levers and scripted events are shared.
- Enemies hunt whoever is closest.
- Die while a teammate lives and you watch them for a minute, then get back up beside them.
- Late joining: anyone can join a game already in progress.

Settings (name, port, voice key, respawn time and more) are in `coop\bpcoop.cfg`.

## Requirements

- Penumbra: Black Plague (GOG version, which includes Requiem). Windows.
- Everyone in a game needs the same version of the add-on.
