# StarLance App artwork

Image files the StarLance App uses at build time. The app is at
[SC2-StarLance/starlance-app](https://github.com/SC2-StarLance/starlance-app).

## Contents

- `leagues/`: StarCraft II ladder league emblems, rank layers and the unranked mark.
- `races/`: the Terran, Protoss, Zerg and random race emblems.
- `bg.jpg`: the window background.

Paths mirror `frontend/dist/` in the app repository (`leagues/x.png` here becomes
`frontend/dist/leagues/x.png` there).

## Ownership and license

The StarCraft II artwork here is the property of Blizzard Entertainment and is
used without license by StarLance, a free, non-commercial fan project, so its
app can show ladder rank and race art. No license is granted for these files,
and the AGPL-3.0 license of the StarLance App does not extend to them.

If you hold the rights to a file here and want it removed, email
sc2-starlance@proton.me and it will be removed.

## How the app uses this repository

The app build downloads these files from one pinned commit and verifies each
file's SHA-256 before use. The pinned commit and the hashes live in the app
repository (`assets.lock`). Do not add code or unrelated files here.
