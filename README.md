# OctoLogin — hosted for EqUpdater

**OctoLogin** is a small DLL mod for [OctoWoW](https://octowow.st) by
**Mustafa Yaman** (fmustafayaman), released under the [MIT License](LICENSE).
It connects the game to whichever OctoWoW login server answers first, and
picks the world server with the fewest dropped tests and the lowest ping.

Its original repository, `github.com/fmustafayaman/OctoLogin`, is no longer
online. This repository keeps the last published release, **v1.1.0**,
available so that [EqUpdater](https://github.com/Equadis/EqUpdater) — which
lists OctoLogin as a recommended mod — can keep installing it. The files are
the original release, unchanged:

| File | SHA-256 |
|---|---|
| `OctoLogin.dll` | `fed726cc910084ec4191d7c02763f094a43c30b6944194136af70823865dabd9` |
| `OctoLogin-v1.1.0.zip` | `70f126dd6c4748b1420d7db9977531496719bbc1dc7935cd4cd5ae78a639d1e2` |

Both match the checksums the original v1.1.0 release published. The DLL in
the zip (`mods/OctoLogin.dll`) is the same file.

## Install

**With EqUpdater:** open the **Mods** tab, tick **OctoLogin** (★) and click
**Apply**. EqUpdater installs it to `mods/OctoLogin.dll` and adds it to
`dlls.txt`.

**By hand:**

1. Download `OctoLogin.dll` from the [latest release](../../releases/latest).
2. Put it in your game folder's `mods` folder (create it if needed).
3. Add this line to the end of `dlls.txt` in your game folder:
   ```
   mods/OctoLogin.dll
   ```
4. Start the game with `VanillaFixes.exe`.

It needs a DLL loader that reads `dlls.txt` (VanillaFixes). Settings are
optional: copy [`OctoLogin.ini.example`](OctoLogin.ini.example) to
`mods/OctoLogin.ini` to change them. What it does at each login is written
to `mods/OctoLogin.log`.

## About this copy

- Nothing here was rebuilt or modified. The author's own README for v1.1.0
  is kept in [`original/README.md`](original/README.md); its install
  scripts and links point at the original repository, which is gone.
- The source code was not mirrored: it is not part of the v1.1.0 release
  files. If the author republishes OctoLogin, EqUpdater will point to the
  author's repository again.
- Releases of this repository are OctoLogin builds: EqUpdater installs the
  `OctoLogin.dll` asset of the latest release here.

---

OctoLogin © 2026 Mustafa Yaman, MIT License — see [LICENSE](LICENSE).
Hosted by Equadis for EqUpdater users.
