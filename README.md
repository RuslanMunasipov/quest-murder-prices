# Quest Murder prices

Hourly WoW Forever auction house price files for the Quest Murder Gold plugin.

Source: the Blizzard Game Data API (World of Warcraft Forever auction houses), read about once an hour.
World of Warcraft and the auction data are (c) Blizzard Entertainment.

The files are in the release `current`:

- `index.txt`: one line per auction house with its file, region, ruleset, house, snapshot time, size and SHA-256.
- `<region>-<ruleset>-<house>.txt`: the newest snapshot of one auction house, summarized per item
  (cheapest, 25th percentile and median unit price in copper, units and lots listed, the cheapest lots).
- `<region>-<ruleset>-<house>-history.txt`: the last 30 days, per item the daily minimum, median and units.

Blizzard's API gives listings only, not sales.

## Icons

`icons/<FileDataID>.png`: 48x48 item icons decoded from the WoW Forever client's own icon files (build 1.60.1.70888),
for the plugin's bag view. World of Warcraft icons are (c) Blizzard Entertainment.
