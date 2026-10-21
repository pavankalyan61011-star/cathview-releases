# CathView releases

Installers, update manifests and the signed revocation list for CathView. This repository holds no source code.

- **Releases**: each version's installers — `CathView-<version>-mac.dmg` (Apple silicon), `-mac-intel.dmg` (Intel Mac),
  `-windows.exe` (Windows, x64) — each with its CathView signature (`.sig`), and the manifests the app's updater reads
  (`latest-mac.json`, `latest.yml`).
- **revocations.json**: the signed list of withdrawn or locked licence keys (key IDs only), which the app checks.

Published by CathView's release workflow on each version tag.
