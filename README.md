# Panel firmware

Public builds for the N.I.N.A. observatory panel. The source lives elsewhere and
is private; this repository carries nothing but the binaries and the small feed
the panels read to find them.

`latest.json` names, for each board, the newest version and where to fetch it.
A panel checks it from its own SYS page and installs what it finds.

| Board | Binary |
|---|---|
| `jc4880p443c` | ESP32-P4, 4.3" 480x800 |
| `esp32-8048s070` | ESP32-S3, 7" 800x480 |