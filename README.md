# Universal Defense

Universal Defense is a space-themed, 3D tower defense mission prototype that runs in a browser. Build orbital towers, start enemy waves, and protect the core.

Play it here:

https://archonlancelot.github.io/Universal-Defense/

## What is included

- A playable tower defense prototype in `index.html`
- A 3D WebGL battlefield with a tilted tactical camera, glowing route, low-poly towers, and spider enemies
- Three tower types: Laser Node, Pulse Cannon, and Gravity Well
- Three enemy types: Void Scout, Ion Raider, and Bulwark Carrier
- Tower hover stats for damage, cooldown, range, cost, and role
- An enemy information tab
- An in-game update log

## How to play

1. Open the game link.
2. Choose a tower in the **Towers** tab.
3. Hover over towers to read their short stats.
4. Click empty space on the map to place a tower.
5. Press **Start Wave**.
6. Stop enemies before they reach the end of the path.

## Notes

This is currently a mission-testing prototype, not an incremental save game. The goal is to make the defense mission fun first, then add more systems once the core gameplay feels good. The 3D renderer uses Three.js from a CDN, so GitHub Pages can host the complete game without a build step or backend.

## Update log

See `CHANGELOG.md` or press **Update Log** inside the game.

## Ideas for later

- Add custom enemy and turret images.
- Add tower upgrades.
- Add bosses, special enemy abilities, and more maps.
- Add mission select or challenge modes.
