# pikpak-terabox-migration
# PikPak to TeraBox Migration

This project provides a script to migrate data from PikPak storage to TeraBox using rclone.

## Requirements

- [rclone](https://rclone.org/downloads/) installed
- PikPak and TeraBox API keys

## Usage

1. Configure your rclone settings in the `rclone_config/rclone.conf` file.
2. Run the migration script:

```bash
bash scripts/migrate.sh
