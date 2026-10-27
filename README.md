# HUBITS: Revised v0.1.8 — Complete GitHub Pages Project

This package includes the entire offline prototype and the redesigned, phone-fitting main menu. It incorporates v0.1.7 gameplay changes: instant buff activation, effect countdowns, falling block animations, gravity, Double Clear, and End Game confirmation.

## Phone-only deployment
1. Extract this ZIP.
2. Upload the **contents** to your `atk-ho/hubits-revised` GitHub repository root, preserving the `assets/` folder.
3. Replace the older files, wait for GitHub Pages to deploy, then reload the game online once to update offline cache.
4. Existing browser saves use the same localStorage key, but exporting a backup first is strongly recommended.

This is an offline-first prototype; online multiplayer and cloud sync are not implemented. Sound starts after a user interaction. Layout uses viewport-height sizing to minimize scrolling on portrait and landscape phones, but mobile browser chrome may vary.
