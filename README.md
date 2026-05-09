# askpaul Marketing Report — data

This repository hosts the JSON datasets that the **askpaul Marketing Report**
dashboard fetches at runtime when opened from the desktop.

The data is regenerated weekly by a cron job on Carlos's Mac and pushed here
automatically by `scripts/push-data-to-github.sh` from the dashboard project.

The folder containing the actual data has a name derived from the dashboard's
shared password (SHA-256 + salt → 12 hex chars), so even though this repo is
public the URL is not discoverable without the password.
