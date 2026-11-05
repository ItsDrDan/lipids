# Lipid Lab (CHEM 3B Chapter 9: Lipids)

Study game for CHEM 3B lipids. Live at https://itsdrdan.github.io/lipids/

- `index.html` is the whole game (no build step). It loads the brand kit (`games/brand/itsdrdan.css`, `icons.js`, `embed.js`), `games/track.js` for anonymous stats, and the Final Boss lipid questions from `textbook/bank/lipids.json` for Final-exam review.
- Every molecule is drawn by the game's code (fatty acid line structures with real cis/trans geometry, triacylglycerols, waxes, phospholipids, sphingolipids, steroids, prostaglandins, leukotrienes, vitamin A, bilayers, transport diagrams).
- `ASSETS.md` lists the ChatGPT art (logo, 16 badges, 5 Lipo mascot moods) and where each file goes. Missing art falls back to brand-kit badges and a code-drawn mascot.
- Links: `?topic=<id>` opens one topic (e.g. `?topic=omega`, `?topic=lab` for the hands-on build-and-break bench); the old `?mode=fa|bb|lip|mem|clin|exam` links from the textbook still work. `?course=3B` is accepted and ignored.
- `meta.json` is the study hub card.

Game design and chemistry by ItsDrDan. Code written with AI assistance (Claude) and checked by the author. CC BY-NC-SA 4.0.
