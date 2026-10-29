# Fit135

A retro, Roblox-inspired calorie tracker and game, in one HTML file (`index.html`).

## Tabs

- **Home**: the landing page, with your calories-left card, the top players and who's online.
- **Tracker**: the boss fight. The big calories-left countdown is in the middle, where calories left = (current weight − target weight) × 3,500. Log food, enter your own maintenance and calories burned each day, track weigh-ins and see your deadline pace.
- **Quests**: earn coins for hitting your calorie goal, keeping streaks, finishing fitness challenges (runs, pushups, planks…) and reaching weight milestones.
- **Catalog**: spend coins on hats, shirts, pants, shoes, backpacks and gear.
- **Island**: a 3D multiplayer world with chat and emotes.
- **Avatar**: change your outfit, skin, hair and build, and edit your stats.
- **Ranks**: leaderboards for losing or gaining weight, streaks and coins earned.

## Running it

Open `index.html` in a browser. On its own the page runs in guest mode, and your progress is saved in that browser's `localStorage`.

Accounts, multiplayer, the shared leaderboard and the calorie-estimating oracle only work when the page is published as a claude.ai Artifact. That's because they use the Artifact runtime (`db`, `user`, `room`, `sample`).

Built with three.js r128, loaded from cdnjs.
