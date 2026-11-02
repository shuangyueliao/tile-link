# Tile Link — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

Tap two tiles with the same pattern and a link that turns at most twice —
they pop. Clear the board before time runs out. Boosters, glowing paths,
bigger boards. Free connect puzzle!
(182 characters)

## Details

- Genre: Puzzle / Casual / Match-connect (onet / mahjong link)
- Controls: Mouse or touch — tap a tile, then tap its twin. Tap the same tile
  again to deselect. SHUFFLE and HINT buttons on screen; no keyboard needed
  (Enter/Space confirms dialogs, Esc deselects).
- Features:
  - 24 procedurally drawn tile patterns (14 shapes x 8-color palette)
  - Glowing polyline shows the winning path in real time
  - Wrong match costs 5 points; each link scores +10
  - Shuffle (x2 per level) and Hint (x1 per level) boosters
  - Auto-shuffle with a notice whenever no moves remain — never dead-ends
  - 180-second timer per level; clear the board for a time bonus (seconds x 2)
  - Boards grow 8x6 -> 10x7 -> 10x8 as levels advance
  - Best score and best level saved locally (localStorage)
  - Procedural graphics & synthesized WebAudio sounds, mute toggle
  - Single-file HTML5 (no external assets), works offline once loaded
- Tech: Vanilla JavaScript, Canvas, WebAudio. No frameworks, no tracking.

## Tags

connect, onet, match, pairs, puzzle, casual, mahjong, link, timer, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (canvas rescales to viewport, portrait & desktop friendly)
- [x] Mobile touch + desktop mouse input, no external links inside gameplay, no analytics
- [ ] Cover: cover-16x9.png (1280x720)
- [ ] Screenshots: screenshot-raw.png (1280x800)

## GameDistribution
- Upload tile-link-gd.zip (contains only index.html), entry file: index.html

## itch.io
- Upload tile-link-itch.zip, mark "This file is playable in browser",
  entry file: index.html, viewport 420x760, kind: html
- Pricing: $0 (donations optional)
