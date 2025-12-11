# WrathCombo - API Level 12 Version

This is a modified version of WrathCombo that has been downgraded from Dalamud API Level 13 to API Level 12 for compatibility with older Dalamud installations.

## Changes Made

- **API Level**: Downgraded from 13 to 12
- **Author**: Updated to Yukari
- **DalamudPackager**: Downgraded from 13.0.0 to 12.0.0
- **Repository URLs**: Updated to point to this repository

## Installation

1. Add this repository to your Dalamud plugin repositories:
   ```
   https://github.com/Yukari/WrathCombo/raw/main/repo.json
   ```

2. Install the plugin through the Dalamud plugin installer

## Original Project

This is based on the original WrathCombo project by Team Wrath:
https://github.com/PunishXIV/WrathCombo

## Building

Requires .NET SDK 9.0 or later.

```bash
dotnet build WrathCombo/WrathCombo.csproj -c Release
```

## License

Same license as the original project.