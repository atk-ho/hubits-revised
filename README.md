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
