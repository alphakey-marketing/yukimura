# Roadmap — 戦国クロニクル：幸村伝

## Phase 0 ✅ (Current)
- Single `index.html` — everything inline
- All 10 chapters with story + combat
- Full combat system (Crimson Mode, Wave Mode, Fort Defense)
- Companion system (story-guaranteed + gacha)
- Equipment system (5 rarity tiers)
- Shrine gacha (pity system)
- localStorage save/load

## Phase 1
- Extract `story/book1.js`, `story/book2.js`, `story/book3.js`
- Load via `<script>` tags
- Add `assets/img/` — character portraits

## Phase 2
- Extract `data/companions.js`, `data/equipment.js`, `data/locations.js`
- Add `styles/theme.css` — design tokens
- Equipment shop (buy with Mon)
- Companion skill upgrades (buy with Mon)

## Phase 3
- `localStorage` save manager with versioning
- itch.io DLC payment hooks (Koku bundles, cosmetics)
- Localisation: 繁體中文, 日本語 (native speaker translations)
- Audio: shamisen/shakuhachi ambient, taiko battle tracks
- Pity system cross-session persistence

## Phase 4
- Optional: Express + Postgres for leaderboard and cross-device sync
- Seasonal event banners (Date Masamune, Ishida Mitsunari)
