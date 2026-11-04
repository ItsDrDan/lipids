# Lipid Lab: art

**Status (Nov 4, 2026):** all 22 images are in: logo, 16 badges and 5 Lipo moods. The study hub card image `games/assets/games/lipids.webp` is in the games repo copy.

## Original request

**22 images total: 1 game logo + 16 badges + 5 mascot moods.**

Every molecule in the game (fatty acid chains, fats, waxes, phospholipids, steroids, prostaglandins, the bilayer and transport pictures) is drawn by the game's code, because the bonds and cis/trans shapes have to be exact. Don't make those.

Until an image exists, the game shows a stand-in: brand-kit badges for the badges, `logo.svg` for the logo, and a code-drawn Lipo for the mascot. When a file with the exact name below is dropped in, the game uses it automatically. No code changes are needed.

Style: glossy cartoon, like the 35-badge sheet and the Sig Fig Sleuth set. Transparent background, thick dark-navy outlines, soft pastels with a warm butter-yellow / golden-oil accent. No text except the digits or symbols listed.

## 1 game logo

| File | Size | Subject |
|---|---|---|
| `logo.png` in this repo, `assets/logo-256.webp` in this repo, and `assets/games/lipids.webp` in the games repo (study hub card) | 1024 × 1024 (logo.png can be 512) | Round badge. A cheerful golden oil droplet with a face, wearing tiny safety goggles, sitting in a round-bottom flask. Behind it, a curved strip of phospholipid bilayer (two rows of pink balls with wavy tails) arcs like a rainbow. Name: Lipid Lab. |

Use the brand prompt from itsdrdan.github.io/games/brand and change only the Subject line.

## Mascot: Lipo the phospholipid (5 moods)

Lipo is a phospholipid: a round, glossy pink head (the phosphate head) with two little golden tails as legs. **One tail is straight (saturated) and one has a small bend in it (a cis kink).** Small stubby arms are fine. Same character, same size and position in every mood, so the game can swap them smoothly.

| File | Mood |
|---|---|
| `assets/mascot/lipo-idle.webp` | Calm, friendly smile, standing on both tails |
| `assets/mascot/lipo-thinking.webp` | Looking up, one hand on chin, small thought bubble |
| `assets/mascot/lipo-correct.webp` | Big happy grin, eyes closed in joy, a thumbs-up |
| `assets/mascot/lipo-oops.webp` | Worried brows, wobbly smile, one tail tangled |
| `assets/mascot/lipo-victory.webp` | Jumping with both arms up, sparkles and a little gold star |

Make them on one sheet if that's easier; they get cut to **320 × 320 transparent WebP**.

## 16 badges

Make them on one sheet, like your 35-badge set. Each badge is cut to **256 × 256 transparent WebP** and saved in `assets/` in this repo.

### 6 menu badges

| File | Used for | Subject |
|---|---|---|
| `cat-fatty.webp` | Fatty Acids | A zig-zag fatty acid chain with one bend (cis kink), a glossy COOH ball on one end and a small "ω" tag on the other |
| `cat-reactions.webp` | Fat Reactions | A bar of soap with bubbles next to a small flask of golden oil and a water droplet |
| `cat-families.webp` | Lipid Families | A family photo frame holding three cute molecules: a fat (comb shape with three tails), a steroid (four fused rings) and a phospholipid (pink head, two tails) |
| `cat-membranes.webp` | Membranes & Health | A slice of cell membrane (two rows of pink heads with tails) with a blue protein channel and a small heart beside it |
| `skillcheck.webp` | Skill Check Prep | A gold trophy holding a golden oil droplet, with a checkmark ribbon |
| `finalreview.webp` | Final-exam review | A thick review book with a small crown on top and a golden oil droplet bookmark |

### 10 achievement badges

| File | Achievement | Subject |
|---|---|---|
| `ach-first.webp` | First Drop | A single shiny golden oil drop with a sparkle |
| `ach-streak5.webp` | On a Roll | A row of 5 green check marks rolling like a wave |
| `ach-streak10.webp` | Unstoppable | A flaming rocket with a "10" on its side |
| `ach-omega.webp` | Omega Expert | A big glossy "ω" symbol wearing a gold medal |
| `ach-melt.webp` | Melting Point Master | A pat of butter melting on a thermometer |
| `ach-soap.webp` | Soap Maker | A bar of soap with a happy face and bubbles |
| `ach-family.webp` | Family Reunion | Eight tiny molecule characters in a group hug |
| `ach-gate.webp` | Gatekeeper | A membrane gate (protein channel) with a small key and a lock |
| `ach-clinic.webp` | Lipid Panel Pro | A clipboard lab report with a heart and a blood drop |
| `ach-skill.webp` | Skill Check Ready | A gold medal with a ribbon and a small zig-zag chain on it |

## Where the images go

- `lipids/logo.png` and `lipids/assets/logo-256.webp` (game header and Canvas)
- `lipids/assets/mascot/lipo-idle.webp` … `lipo-victory.webp` (5 files)
- `lipids/assets/cat-fatty.webp` … `lipids/assets/ach-skill.webp` (16 files)
- `games/assets/games/lipids.webp` (the study hub card; that file lives in the games repo)

Bring the sheets back to Claude and they'll be cut, sized and dropped in.
