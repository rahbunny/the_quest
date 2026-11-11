# The Quest — consolidated site files

This folder contains the latest assembled public game, assets and Quest Studio admin dashboard from our conversation.

**GitHub Pages:** https://rahbunny.github.io/thequest/  
**Quest Studio:** https://rahbunny.github.io/thequest/admin/

See `../START_HERE_BEGINNER_GUIDE.md` in the delivery ZIP before uploading.

## Main files
- `index.html`: the page structure, including the tutorial popup.
- `styles.css`: the complete game look (tutorial, Guild font, Gnoll sizing, death effects, slower fades).
- `game.js`: branching story interface, choices, animation and public Guild display.
- `quest.js`: Supabase-backed quest progress, claims, inventory and publishing integration.
- `auth.js`: username checks, Supabase sign-in, returning-player recovery.
- `supabase-config.js`: public Supabase URL and publishable key; **never use a service-role/secret key here**.
- `assets/`: PNG character, background, reward and tutorial images.
- `admin/index.html`, `admin/studio.css`, `admin/studio.js`: Quest Studio interface, layout and publishing/edition-management logic.
- `admin/autumn-template.json`: ORIGINAL Autumn starting template, not your current saved Autumn draft.

## Data storage
GitHub only hosts site files. Supabase holds live editions, drafts, profiles, run records, and prize inventory. Uploading these files does not copy or reset those records.
