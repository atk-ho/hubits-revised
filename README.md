HUBITS: Revised v0.2.2 — Solo Buff Separation

- Six columns, ten rows.
- Buffs are independent glowing overlays at grid coordinates, not attached to falling or landed blocks.
- Clearing a block and gravity never remove a buff. Only tapping the buff activates and removes it.
- One buff at a time, spawning roughly every 18–30 seconds.
- New cache version.

Upload the complete project or replace only app.js, style.css, sw.js.


## v0.2.4 hotfix
- Fixed Create Offline Profile modal clicks by handling actions on `document` (modal is appended to `body`, outside `#app`).
- Welcome screen displays the existing `assets/icon-512.png` game logo.
- Cache version updated; profile save key is unchanged.


v0.2.5: Borderless title artwork derived from existing icon, one title, responsive welcome screen. Existing app icon preserved.


## v0.2.6 gameplay timing fix
- Falling blocks now advance one cell approximately every 0.42 seconds (previously 2.6 seconds), making solo gameplay active.
- 6 columns x 10 rows retained; settled blocks stack, and block removal triggers column gravity.
- Floating buff icons remain independent of block clearing.
- New versioned asset URLs and service worker cache.
