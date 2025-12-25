# tuirandr
A simple tui wrapper of `xrandr` with vim movements.
It is especially suited for tiling window manager users (i3, bspwm, etc.) who want fast, scriptable display management without relying on a mouse.

## Features

- Pure TUI interface (Textual)
- Vim-style navigation (`h j k l`)
- Lists **only connected outputs**
- Per-output configuration:
  - Enable / disable
  - Resolution (mode) selection
  - Relative positioning (`right-of`, `left-of`, `above`, `below`)

## Requirements

- Python ≥ 3.9
- X11 with `xrandr`
- Python dependency:
  - `textual`

To install dependency:
```bash
pip install textual
```

## Installation

Make the script executable:

```bash
chmod +x tuirandr
```

Move it into your `PATH`:

```bash
sudo mv tuirandr /usr/local/bin/
```

---

## Usage

Run:

```bash
tuirandr
```

---
