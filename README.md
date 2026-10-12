# CMC HMS — Updates & Releases

This repository holds only signed update packages for CMC HMS.
No source code is published here.

Each GitHub Release contains:
- `HMS_update_<version>.zip` — the update package (built program only)
- `update.json` — version, notes, SHA-256 and Ed25519 signature

The HMS Updater verifies the signature before installing anything.
