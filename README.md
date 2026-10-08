# ULTRAKILL // Web Remake - GitHub files

You keep ONE small file on your device: `ULTRAKILL.html` (~4 KB). It shows a loading screen, downloads the game
from your GitHub repo, and starts it. No web page is hosted on GitHub - the repo only holds data files:

- `game.txt`  the game code (plain text, not a web page)
- `assets/`   boom.mp3, call.jpg, boc.jpg, yui.jpg, cat.jpg

## Setup
1. github.com -> New repository (e.g. `ultrakill`) -> **Public** -> Create.
2. "uploading an existing file" -> drag in `game.txt` and the `assets` folder -> Commit. (Do not enable Pages.)
3. Open `ULTRAKILL.html` in a text editor and set `GITHUB_USER` (and `GITHUB_REPO` / `GITHUB_REF` if different).
4. Open `ULTRAKILL.html` in your browser. That's the file you keep or send to people.

## Updating
Upload a new `game.txt`. jsDelivr caches the `main` branch for up to ~12 h; to see changes right away set `GITHUB_REF`
to a commit id, or purge at https://www.jsdelivr.com/tools/purge.
Note: the repo must be public, and anyone who finds it can read the game code.
