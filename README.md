# XEGA Phone — Windows installer releases

Public download host for the XEGA Phone Windows desktop installer.

This repository contains **compiled installers only**. No source code is
published here. See `LICENSE` — all rights reserved.

## Latest

| File | Version | Size | SHA-256 |
|---|---|---|---|
| `XEGA-Phone-Setup-1.0.1.exe` | 1.0.1 | 78,562,282 bytes | `BAE1F8FC7795ED96B0A5D898C97ACF00DE25C47002F656009A677ABB06F846A7` |

## Requirements

- Windows 10 (build 22621 / Windows 11 recommended) or later, 64-bit
- A valid XEGA CRM account — the application requires sign-in and will not
  function without one

## Install

1. Download `XEGA-Phone-Setup-<version>.exe`.
2. Verify the SHA-256 against the table above.
3. Run the installer. It installs per-user to
   `%LOCALAPPDATA%\Programs\cion-phone-desktop` and does not require
   administrator rights.

## Verification

```powershell
Get-FileHash .\XEGA-Phone-Setup-1.0.1.exe -Algorithm SHA256
```
