# Chijil

A minimal desktop app that tidies up cluttered folders.

## Features

- **Timestamp-based renaming** — Each file is renamed to its modification date and time (e.g. `20261027_135735.jpg`).
- **Structured sorting** — Files are organized into `YEAR/MONTH/TYPE` directories (e.g. `2026/OCTOBER/JPG`).
- **Broad format support** — Handles JPG/JPEG, PNG, PDF, DOC/DOCX, and XLS/XLSX files.
- **Collision-safe** — Duplicate filenames receive numeric suffixes (`-1`, `-2`, …) so no existing file is overwritten.
- **Non-destructive workflow** — Files are moved and renamed only; original content is never modified.

## Install

Download the latest `.deb` from [Releases](../../releases/latest), then run:

```bash
sudo apt install ./chijil_1.1.0_all.deb
```

Requires Debian 12+ or Ubuntu 22.04+. Dependencies are installed automatically.

## Uninstall

```bash
sudo apt remove chijil
```

## License

MIT © 2026 Chanakya Kumar Das
