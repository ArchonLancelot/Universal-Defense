# Universal Defense

Universal Defense is a small space-themed tower defense game that runs in a browser. Build towers, start waves, earn credits, and keep your progress after closing the game.

## What is included

- A playable tower defense prototype in `index.html`
- Three tower types: Laser Node, Pulse Cannon, and Gravity Well
- Local browser autosave
- Export/import save text
- Optional GitHub cloud saving to `saves/player-save.json`
- An in-game update log

## How to play

1. Open `index.html` in a browser or host it with GitHub Pages.
2. Click a tower type in the right panel.
3. Click empty space on the map to place the tower.
4. Press **Start Wave**.
5. Stop enemies before they reach the end of the path.

## Saving progress

The game always saves locally in the browser using `localStorage`. That means your progress stays after you close the tab or browser, as long as you use the same browser profile.

For a backup, open **GitHub Save / Load** in the game and use **Export Current Save**. You can paste that save text back later with **Import Save Text**.

## Optional GitHub cloud save

The game can save progress into this private repository, but you need to provide a GitHub token inside your own browser.

Recommended token setup:

1. Create a fine-grained personal access token on GitHub.
2. Give it access only to this repository: `ArchonLancelot/Universal-Defense`.
3. Give it **Contents: Read and Write** permission.
4. Open the game, click **GitHub Save / Load**, paste the token, and press **Remember Token**.
5. Use **Save to GitHub** and **Load from GitHub** from that same panel.

The token is not committed to the repo. It is only stored in your browser if you press **Remember Token**.

## Update log

See `CHANGELOG.md` or press **Update Log** inside the game.

## Ideas for later

- Add custom turret and enemy images.
- Add upgrade buttons for towers.
- Add bosses, planets, and more maps.
