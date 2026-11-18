# SUDOKILLMEOS

v1 — the start of an era.

A custom Linux ISO I built from scratch, bundled with the Calamares graphical installer. Doesn't have a ton of features yet (literally like 6 things), and I'm not listing them here — boot it up and go figure them out yourself.

## Download

Grab the `v1` ISO on the [Releases](../../releases/latest) page (~1.85 GB, x86_64).

## How to run it

**In a VM (easiest):**
Load the `.iso` into VirtualBox, VMware, or QEMU with at least 4 GB RAM and boot it up. You can test the live session or install it with Calamares.

**On a USB stick:**
Flash it with Rufus, BalenaEtcher, or `dd`:
```bash
sudo dd bs=4M if=SUDOKILLMEOS-v1.iso of=/dev/sdX status=progress
```
*(Make sure `/dev/sdX` is actually your USB drive before running that.)*

## Next up (v2)
- Custom theme and default configs
- Better branding / boot screen
- More than 6 features (maybe)

If something breaks, open an [Issue](../../issues).


