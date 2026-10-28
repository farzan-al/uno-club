# Uno Club

A mobile-friendly UNO scorekeeper with a dark theme, custom elimination limits, secret scores, cartoon avatars, round history, and automatic browser saving.

## House rules
- Number cards: face value
- Reverse / Skip: 10 points
- Draw two: 20 points
- Wild / Draw four: 40 points
- Round winner: 0 points

## Deploy on Vercel
1. Import this GitHub repository into Vercel.
2. Select **Other** as the framework preset.
3. Leave the root directory at the repository root.
4. No install or build command is required. The included vercel.json configures static hosting.
5. Click Deploy.

Game progress is stored in localStorage on each browser, not synced between devices. Secret-score mode hides scores in the interface; it is not encrypted storage.

## Run locally
Open index.html in a browser, or serve the folder using any static web server.
