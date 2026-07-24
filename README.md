# scoop-stformat

A [Scoop](https://scoop.sh) bucket for **[STFormat](https://github.com/elconfa/STFormat)** — a free,
open-source formatter for Structured Text (IEC 61131-3), for TwinCAT and CoDeSys.

## Install

```powershell
scoop bucket add stformat https://github.com/elconfa/scoop-stformat
scoop install stformat
```

This installs the `stformat` command line and a Start-menu shortcut for the **STFormat** GUI.
Because Scoop does the download (not the browser), you don't get the "this file could be dangerous"
prompt.

## Update

```powershell
scoop update stformat
```

New releases are picked up automatically: a scheduled [GitHub Action](.github/workflows/excavator.yml)
(the Scoop *excavator*) checks the [STFormat releases](https://github.com/elconfa/STFormat/releases)
and updates the manifest.

## License

The manifest is MIT-licensed, like STFormat itself.
