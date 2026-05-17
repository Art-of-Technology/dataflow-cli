# dataflow-cli

Public binary distribution for the [dataflow](https://data-flow.oros.boo) CLI.
The source code for the CLI (and the wider data-flow platform) lives in a
private repo; this repo only holds tagged binary releases so anonymous
installers can fetch them.

## Install

### macOS / Linux

```bash
curl -fsSL https://data-flow.oros.boo/install.sh | sh
```

### Windows (PowerShell)

```powershell
irm https://data-flow.oros.boo/install.ps1 | iex
```

## Available commands

For the full list of commands, slash commands (TUI), and the chat panel,
see the documentation site: <https://data-flow.oros.boo/docs/cli>

(Or run `dataflow --help` after installing.)

## Releases

Binaries are published here automatically when the upstream repo tags
`cli-vX.Y.Z`. Pre-built binaries for:

- `dataflow-darwin-arm64`
- `dataflow-darwin-x64`
- `dataflow-linux-arm64`
- `dataflow-linux-x64`
- `dataflow-windows-x64.exe`

Pick the asset for your OS/arch from the latest release.

## Reporting issues

This repo is binaries-only; please file issues on the upstream:
<https://github.com/Art-of-Technology/data-flow/issues>