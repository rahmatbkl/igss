# IGSS — ITERA Geotechnical and Seismic Suite

Official Windows installers for the geotechnical and earthquake engineering
software developed at Institut Teknologi Sumatera (ITERA).

**Website:** https://igss.pages.dev

| Product | Latest release | Status |
|---|---|---|
| **SITERA** — Seismic SIte Response Analyzer | [sitera-v1.19.0](https://github.com/rahmatbkl/igss/releases/tag/sitera-v1.19.0) | Stable |
| **GEOTERA** — Geotechnical Toolkit for Earth Retention & slope Analysis | [geotera-v0.1.0-prototipe](https://github.com/rahmatbkl/igss/releases/tag/geotera-v0.1.0-prototipe) | Prototype (pre-release) |

This repository hosts **releases only**. Source code is not published here.

## Before you run an installer

1. **Verify the checksum.** Every release lists the SHA-256 of each file in its
   notes and in `SHA256SUMS.txt`:

   ```powershell
   Get-FileHash .\SITERA_Setup_1.19.0.exe -Algorithm SHA256
   ```

   If the value differs from the one in the release, do not run the file.

2. **Expect a SmartScreen warning.** The installers are not code-signed yet, so
   Windows may show "Windows protected your PC". After verifying the checksum,
   choose *More info → Run anyway*.

Both installers install **per user**: no administrator rights and no UAC prompt.

## Requirements

Windows 10 or 11, 64-bit.

## Licence

SITERA and GEOTERA are released under the MIT licence. GEOTERA documentation is
under CC BY 4.0.

## Reporting problems

Calculation errors and ordinary bugs are welcome as issues — include the complete
numeric example and the reference you compared against. Please **do not** report
security problems in public issues; contact the developers through Institut
Teknologi Sumatera (ITERA).

---

Design software, to be used under the supervision of a qualified engineer.
