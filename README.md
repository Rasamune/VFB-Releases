# VFB Releases Repository

This private repository contains releases and update information for the Video File Browser (VFB) application.

## Repository Structure

\\\
VFB-Releases/
 releases/           # Release archives organized by version
    v2.0.7/
       VFB-Setup-v2.0.7.exe
    v2.0.8/
        VFB-Setup-v2.0.8.exe
 version.json        # Current version info for auto-updater
 changelog.md        # Version history and changes
 README.md          # This file
\\\

## Files

- **\ersion.json\**: Contains current version information that the VFB application checks for updates
- **\eleases/\**: Contains all version releases organized by version number
- **\changelog.md\**: Human-readable version history

## Auto-Update System

This repository is used by the VFB application's auto-update system:

1. **Version Check**: VFB periodically checks \ersion.json\ to see if a new version is available
2. **Update Prompt**: If a newer version is detected, the user is prompted to update
3. **Download**: If the user agrees, the new installer is downloaded from the appropriate release folder
4. **Install**: The new version is automatically installed

## Security

This repository is private to ensure only authorized VFB distributions are available.