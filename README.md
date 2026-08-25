# Official BOXROOM Mod Catalogue

This repository is BoxMate's built-in catalogue of generally available BOXROOM mods.

BoxMate loads this root `manifest.json` automatically. Users can browse and install any listed mod without adding individual repository links. Required infrastructure such as ModsPanel and BR-MediaAPI is resolved from each mod's own manifest and installed automatically when needed.

Boxroom Books is intentionally excluded because BR-BookSystem replaces it. Boxroom TV can be added after its upstream manifest is available.

## Deprecated mods

- **[Deprecated] Boxroom Plus** — Custom game launching, launch arguments, and case colors are now built into BOXROOM. Its platform-icon feature continues as [BOXROOM Platform Icons](https://github.com/MidgetBrony/Boxroom-Platform-Icons).

Deprecated entries remain in `deprecatedMods` for catalogue history but are not offered as new installations.

## Adding a mod

Add its public GitHub repository to the `mods` array. The repository must contain a valid BoxMate `manifest.json` at the root of its `main` or `master` branch.
