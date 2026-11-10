# Penumbra: Black Plague + Requiem Co-op

Online co-op for up to four players in **Penumbra: Black Plague** and **Penumbra: Requiem**, running on the original, untouched games. None of the game's own files are changed: the add-on lives in its own `coop` folder next to the game, plus one small loader file.

By [Quasi Interactive](https://quasi-interactive.com). Join the [Discord](https://discord.gg/Hbxchnyr3) to find people to play with or to report problems.

Looking for *Penumbra: Overture* co-op? That is its own project: [penumbra-overture-coop](https://github.com/QuasiInteractive/penumbra-overture-coop).

## Download

Grab the zip from the [latest release](https://github.com/QuasiInteractive/penumbra-blackplague-coop/releases/latest).

## Install

1. Open your Penumbra: Black Plague folder and go into `redist` (the folder with `Penumbra.exe` and `Requiem.exe` in it).
2. Drag **both** the `coop` folder and `wsock32.dll` from the zip into `redist`.
3. Play from `coop\Black Plague Co-op.exe` or `coop\Requiem Co-op.exe`.

`wsock32.dll` is the co-op loader. It passes everything on to Windows' own `wsock32.dll` and only loads the co-op when you start the game from a co-op launcher; started normally, the game is the plain game. To uninstall, delete `coop` and `wsock32.dll` from `redist`. Upgrading from v1.0: replace the old `coop` folder and add `wsock32.dll`.

There is also a `secret` folder in the zip. Have a look.

## Antivirus

Some antivirus programs flag new, unsigned mod files with "machine learning" or "heuristic" guesses. That is a false positive: the files are ours (Properties > Details shows Quasi Interactive) and contain no malware. Since v1.1 the launchers start the game normally and never write into it, which was what most scanners objected to in v1.0. If yours still removes a file, restore it and add the `coop` folder as an exception.

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
