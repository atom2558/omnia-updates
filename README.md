# omnia-updates

Release feed for the OMNIA Desktop (Windows) self-updater. This repository holds **only signed installers
and `latest.json`** as release assets. No source code, no secrets.

Every installer is signed with a minisign key whose public half is built into the app; the app refuses any
file that does not verify, so hosting here does not need to be trusted.
