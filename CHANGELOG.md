# Changelog

## v2.2
- **Remembers your settings** between launches — the last save folder and the option toggles (Smart backup, Compress, Verify, Smart restore, Quick format) are restored next time. (NAS share passwords are never stored.)
- **SHA-256 checksums** — an optional toggle computes a backup's SHA-256 and saves a `.sha256` file next to it. When you later restore that image, DiskImager offers to re-check it first and aborts on a mismatch.
- **Operation log** — each operation and any errors are written to `%APPDATA%\DiskImager\log.txt` for troubleshooting.
- **Smoother mode switches** — tab changes now cross-fade instead of snapping.

## v2.1
- **Automatic updates** — checks for a newer release on launch and updates itself in one click.

## v2.0
- Complete redesign of the interface.
- **Network shares (NAS / SMB)** — back up to or restore from a share, with credentials or a UNC path.
- Drag-and-drop, keyboard shortcuts, live speed/ETA telemetry, and many fixes.

## v1.0
- Initial release — backup, restore, mount, and FAT32 format.
