# PocketOMP downloads

Signed launcher APKs and runtime components for PocketOMP.

Download the launchers from [Releases](https://github.com/Fanorisky/PocketOMP-runtime/releases).

- **Online:** small launcher that downloads the engine and data needed by your server. Android prompts you to install the signed engine APK; installed components then work offline.
- **Full:** includes the pinned runtimes and data for offline setup.

The launcher authenticates the stable catalog, checks component sizes and SHA256 hashes, and stages runtime updates in the other installed slot for rollback. Game and database runtimes have separate slots.

Engines require compatible ARM hardware. The x86 emulator can test downloads, the interface and the execution probe.

`components-N` releases contain immutable, content-addressed APKs and data packs. `components-stable` contains the signed catalog pointing to the current component release.

This repository hosts download files, not the app source or signing keys.
