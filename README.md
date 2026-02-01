# StackEye Scoop Bucket

Scoop bucket for installing [StackEye CLI](https://github.com/StackEye-IO/stackeye-cli) on Windows.

## Installation

```powershell
# Add bucket
scoop bucket add stackeye-io https://github.com/StackEye-IO/scoop-bucket

# Install
scoop install stackeye
```

## Update

```powershell
scoop update stackeye
```

## Uninstall

```powershell
scoop uninstall stackeye
scoop bucket rm stackeye-io
```

## Available Tools

| Package | Description |
|---------|-------------|
| `stackeye` | CLI for StackEye uptime monitoring platform |

## Requirements

- Windows 10 or later
- [Scoop](https://scoop.sh/) package manager

## About StackEye

[StackEye](https://stackeye.io) is a full-stack uptime monitoring platform. The CLI provides command-line access for managing monitors, alerts, and integrating with automation workflows.

## License

MIT License - see individual package licenses for details.
