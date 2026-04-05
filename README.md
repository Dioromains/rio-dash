# RIO//DASH

A personal World of Warcraft character dashboard built on top of the [Raider.IO public API](https://raider.io/api).

Search any character by region, realm and name to instantly view their M+ score, best runs, raid progression and gear — without ads or clutter.

## Features

- M+ score with tier color coding and season selector
- Score progress bar across all tiers
- Score delta badge (tracks improvement between visits)
- Best and recent Mythic+ runs
- Raid progression with M / H / N kill counts
- Full gear list with item icons, enchant stats and gem names (via Wowhead)
- Pin and save multiple characters locally
- Export a summary card as a PNG image

## Usage

Open `index.html` in any modern browser. No server or installation required.

1. Select your region (EU / US / KR / TW)
2. Enter your realm name (e.g. `Ragnaros`)
3. Enter your character name
4. Press **Search** or hit Enter

## Live Demo

[https://Dioromains.github.io/rio-dash](https://Dioromains.github.io/rio-dash)

## Data Sources

Character data is fetched in real time from the **Raider.IO public API** (`raider.io/api/v1`).  
Item icons and enchant/gem tooltips are fetched from the **Wowhead tooltip API** (`nether.wowhead.com`).

This project is not affiliated with or endorsed by Raider.IO, Wowhead, or Blizzard Entertainment.

## License

See [LICENSE](LICENSE) for details.
