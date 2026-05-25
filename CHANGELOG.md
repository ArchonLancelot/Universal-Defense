# Changelog

## v0.2.3 - Voidweaver Arrives

- Removed all placeholder enemies from the game.
- Added Voidweaver as the only active enemy type.
- Voidweaver is now the basic first spider enemy: fast, light, and worth 12 cash.
- Updated enemy waves so every spawn is currently Voidweaver.
- Updated the enemy database to focus on spider class information.

## v0.2.2 - Tower Menu and Web Terrain

- Fixed menu hover and tab switching so the page no longer nudges around.
- Core now starts at 100% instead of 25%.
- Removed the yellow planet from the top right of the map.
- Clicking a placed tower now opens a tower menu instead of selling instantly.
- Added a manual Sell button in the tower menu. Towers still sell for half their placement cost.
- Tower ranges now appear only while placing a tower or inspecting a placed tower.
- Changed the buildable terrain into a silky space-web landscape for the future spider enemy theme.

## v0.2.1 - Control and Polish Pass

- After placing a tower, the cursor now clears instead of holding another tower.
- Added tower selling: with an open cursor, click a tower to sell it for half its placement cost.
- Added an Open Cursor button so tower placement can be manually cancelled.
- Added Auto Wave so the next wave can start by itself after a short delay.
- Renamed enemy Reward to Cash.
- Replaced unclear enemy Type letters with clear class names: Scout, Raider, and Bulwark.
- Added more spacing inside stat cards so labels and numbers are easier to read.
- Improved battlefield graphics with a tactical grid, nebula glow, engine trails, stronger tower silhouettes, and brighter path effects.

## v0.2.0 - Mission Overhaul

- Expanded the battlefield from 800x600 to 1200x720 so the map can support larger paths and more tower room.
- Added a longer winding space route for enemies.
- Reworked the game into a mission-testing prototype instead of a progress-save game.
- Added Towers and Enemies tabs in the side panel.
- Added tower hover and selection details for damage, cooldown, range, cost, and role.
- Added an enemy database with HP, speed, reward, and behavior notes.
- Added a tower placement preview showing range and blocked placement areas.
- Added new enemy types: Void Scout, Ion Raider, and Bulwark Carrier.
- Improved HUD readability, map polish, mission controls, and combat readability.
- Removed cloud-save UI from the game screen for now.

## v0.1.0 - First Launch

- Added the first playable space tower defense prototype.
- Added three tower types: Laser Node, Pulse Cannon, and Gravity Well.
- Added waves, lives, credits, enemy rewards, and wave clear bonuses.
- Added local browser autosave.
- Added export/import save text.
- Added optional GitHub cloud saving to `saves/player-save.json`.
- Added an in-game update log panel.
