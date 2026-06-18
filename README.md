# JF BIOS for Batocera

A personal collection of BIOS files for my Batocera retrogaming setup.

## About

BIOS files are firmware dumps required by certain emulators to function correctly. Without them, some systems simply won't boot or will have missing features. This repo contains the BIOS files I personally use with [Batocera Linux](https://batocera.org) on my old laptop, covering classic systems up to PS1 era.

## Notes

- These BIOS files are configured for my specific Batocera build. Some may work out of the box, others might not, as I'm still actively tweaking and testing things.
- I'm running this on an **old laptop**, so I stick to consoles up to **PS1 quality** (PlayStation 1 era and below). No demanding emulators here.
- Consoles I focus on include things like PS1, Neo Geo, PC Engine/TurboGrafx, and similar era systems.

## Changelog

### 2026-06-18
- **NeoGeo** — Updated `neogeo.zip` with a complete BIOS set: added `sp-s3.sp1`, all regional MVS/AES variants, and UniBIOS 1.0–4.0. All BIOS files also extracted as loose files in `bios/` for compatibility.
- **GBA / NDS** — Added Game Boy Advance (`BIOSGBA.ROM`) and Nintendo DS BIOS files (`biosnds7.rom`, `biosnds9.rom`, DSi firmware & NAND).
- **C64 ROMs** — Cleaned up the C64 game library: removed 163 hacked/alternate `[a]` tagged ROMs and 9 non-English (Spanish/German) versions.

## Disclaimer

BIOS files are provided for personal use with hardware I own. Compatibility is not guaranteed, use at your own risk.
