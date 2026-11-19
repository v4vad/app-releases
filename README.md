# app-releases

Downloads and update feeds for Porthole and better-menu.

- Disk images are attached to this repository's Releases (tags like `porthole-v0.1`).
- Each app checks its own feed for updates: `porthole/appcast.xml`, `better-menu/appcast.xml`.
- These files are written by each app's `scripts/release.sh --publish`. Don't edit them by hand.
