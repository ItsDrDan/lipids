# Lipid Lab (CHEM 3B Chapter 9 (lipids))

Study game for CHEM 3B Chapter 9 (lipids). Live at https://itsdrdan.github.io/lipids/ once this repo is published with GitHub Pages (branch `main`, root).

- `index.html` — the whole game (no build step). Built from the shared engine in ItsDrDan/metabolism (`tools/build_game.py` there assembles
  `content.js` + `config.json` into `index.html`; edit `content.js` for questions, re-run the builder). Loads the brand kit
  (`games/brand/itsdrdan.css`, `icons.js`, `embed.js`), `games/track.js` for anonymous stats, and the Exam Practice module from the
  textbook repo (`textbook/js/fbx.js`, `textbook/css/widget-base.css`, questions from `textbook/bank/lipids.json`).
- `meta.json` — study hub card. `logo.svg` — badge used in the hero.
- `?mode=<id>` opens a mode directly; `?course=3B` is accepted and ignored (3B-only game).

Game design and chemistry by ItsDrDan. Code written with AI assistance (Claude) and checked by the author. CC BY-NC-SA 4.0.
