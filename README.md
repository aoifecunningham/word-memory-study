# Word Memory Study

A static browser-based psychology experiment using plain HTML, CSS, and JavaScript.

## Run locally
1. Keep `index.html`, `styles.css`, and `script.js` in the same folder.
2. Open `index.html` in a current browser.
3. Complete all three encoding blocks, the 30-second distractor, and free recall.
4. Download the summary and trial-level CSV files from the results screen.

No server, database, package manager, framework, or build step is required.

## Publish with GitHub Pages
1. Create a new GitHub repository (for example, `word-memory-study`).
2. Upload all three files to the repository's root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)`, then save.
6. Wait for GitHub Pages to publish and open the public URL shown on the Pages settings screen.

## Notes on scoring
Recall is case-insensitive and ignores punctuation. The script accepts small spelling differences using a conservative edit-distance rule. Each studied word can score only once. This is a simple classroom demonstration, not a validated clinical or research instrument.

## Data
- Summary CSV: one row per completed session, including strategy scores and condition/list order.
- Trial CSV: 18 rows per completed session, one per studied word, with strategy assignment and recall accuracy.
- Files are generated in the participant's browser; no data are sent to a server.
