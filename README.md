# muttnik-config

Live game configuration for **Muttnik**, fetched by the game at runtime.

- `missions.json` - the 52 weekly missions.
- `catalog.json` - depot items: names, descriptions, prices, icons, shelf order.
- `tuning.json` - upgrade strengths, power-up durations, low-air warning point, babushka bonus.

Config data only. No source code or art lives here. The game bundles its own copy (or built-in defaults) and falls back to it if a fetch fails or a file is malformed.
