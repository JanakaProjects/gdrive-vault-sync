# GDrive Vault Sync

An Obsidian plugin for two-way sync between your vault and Google Drive.

## Features
- Two-way sync (upload & download)
- Auto-sync on startup and on interval
- File event watchers (create, modify, delete, rename)
- Android compatible
- Auto-update from GitHub on startup

## Installation

1. Download `main.js` and `manifest.json` from this repository
2. Place them in `[YourVault]/.obsidian/plugins/gdrive-vault-sync/`
3. Enable the plugin in Obsidian Settings → Community Plugins
4. Enter your Google OAuth credentials in the plugin settings

## Building from source

```bash
npm install
npm run build
```
