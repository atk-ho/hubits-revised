# HUBITS: Revised — offline arcade prototype v0.1

A playable **early prototype**, not the complete game. Includes multiple offline profiles, stage mode, Endless, Daily, Custom, simplified VS AI, Learn/Practice, collection, settings, backup export/import, and synthesized 8-bit-inspired sounds. Online multiplayer is not implemented.

## Phone-only GitHub Pages deployment
1. Extract the ZIP on your phone.
2. Create a public GitHub repository.
3. Upload the **extracted files and assets folder** to the repository root (not the ZIP alone).
4. Go to repository Settings → Pages → Deploy from branch → main → / (root) → Save.
5. Open the GitHub Pages URL once while online. Add to Home Screen where supported. Cached files can then load offline.

## Limits
- No payment cards, packages, API keys, or build tools needed.
- LocalStorage is used for this initial prototype, not IndexedDB yet. Export backups regularly.
- VS AI is a simplified scoring bot, not a complete independent opponent board.
- Sample question bank only; advanced coding editor, full lessons, secure execution, online accounts, multiplayer, and cloud sync are future work.
- Browser data can be deleted. Imported saves are untrusted for competitive play.
- Service workers require HTTPS or localhost.

## v0.1.2 changes
- Added a welcome/title screen before profile selection.
- Replaced browser prompt/confirm/alert dialogs with themed in-game dialogs.
- Updated service worker cache version so existing installs fetch the revised files.
- Upload **all files**, or at least `app.js`, `style.css`, and `sw.js`, to GitHub Pages.

## v0.1.3 changes
- Faster block pressure (quarter-second simulation updates; blocks roughly every 1.25 seconds at normal speed, increasing over time).
- In-game victory/game-over overlay with replay and main-menu buttons.
- Glossy but restrained 3D arcade panels, aligned board and coding questions.
- Collectible ✦ blocks: tap to collect Slow, Freeze, or Clear buffs; activate from the power bar.
- VS AI debuffs: Haste, Drop, Rush, Scramble. Correct answers charge the attack meter; spend 100% and one debuff to attack.
- Solo modes automatically trigger a random debuff hazard about every 18 seconds (Haste, Drop, Rush, or Scramble). VS AI attack effects are simplified until the second board is implemented.
- AI is still a prototype simulation, not a complete independent second board.
- Existing local profiles are retained.


## v0.1.4 — Animation & audio update
- Retro chiptune synthesized in Web Audio (no MP3s, no external API, works offline). Menu and gameplay tracks are distinct. Music starts after a user tap, subject to browser autoplay rules.
- Synthesized sounds for clicks, correct/wrong answers, block landing, clears, power-ups, attacks, victory and defeat.
- Music/SFX toggles and independent volume sliders in Settings. Existing profile data and storage key preserved.
- Landing pop, board impact, clear pixel burst, danger flash, results modal entrance and victory confetti. Respect reduced-motion preference.
- Animations are short UI effects on landed blocks, **not yet a continuous physics-based falling block sprite**. That will require a larger game-board engine redesign.
- On GitHub, future updates generally require replacing only `app.js`, `style.css`, `sw.js` unless stated otherwise.


## Official icon update
This complete package includes the approved HUBITS coding-block icon, favicon and PWA icons. Upload the extracted contents to the repository root.
