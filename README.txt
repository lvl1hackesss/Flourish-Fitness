FLOURISH — mobile fitness tracker prototype

To run locally on a Mac:
1. Unzip this folder.
2. In Terminal, cd into the flourish folder.
3. Run: python3 -m http.server 8000
4. Open http://localhost:8000 on your Mac.

To use on your iPhone, upload the contents of the flourish folder to a free static web host (e.g. GitHub Pages), visit the HTTPS website in Safari, tap Share, then Add to Home Screen.

IMPORTANT: All data is saved locally in browser localStorage (not IndexedDB). This is a functional zero-backend prototype. Export a backup regularly from Settings. Browser storage can be cleared, and it will not automatically sync across devices. Do not use private browsing.

This initial version includes daily energy check-in, A–D workout templates, short workout, rest day, set tracking, local history, saved breakfast templates, nutrition estimates, measurements, and JSON backup/restore. It does not yet include editable templates, automatic plate calculations, or progress charts.
