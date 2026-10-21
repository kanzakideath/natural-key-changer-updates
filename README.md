# natural-key-changer-updates

Signed update files for the **Natural Key Changer** Chrome extension. The extension reads
`latest.json` from here, checks its signature against the public key built into it, and downloads
only the files that changed (`files/<sha256>`). Nothing here is meant to be used by hand.

Published with `tools/publish-update.mjs` of the extension's project.

The phone edition (iPhone / Android userscript) lives in [`mobile/`](mobile/README.md).
