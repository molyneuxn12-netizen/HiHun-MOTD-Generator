# Hideaway Hunters — Fleet MOTD Generator

A simple web tool for generating EVE Online fleet channel MOTDs (Message of the Day) for the Hideaway Hunters standing fleet.

## What it does

Fill in the form fields and the MOTD preview updates in real time. When you're happy with it, hit **Copy MOTD to Clipboard** and paste it directly into your EVE Online fleet channel MOTD box.

### Customisable fields

- Fleet name
- Orca / Porpoise pilot name
- Mining boost, shield boost, and compressor ranges (km)
- Current activity — Homefronts, Moon Mining, Belt Mining
- Fleet rules (editable, one per line)
- Moon mining etiquette toggles
  - Type A crystals / no residue on Glistening pulls
  - One rock per ship reminder
  - Non-corp buyback requirement
- Moon systems, corp tags, and buyback contract name

## Repo structure

```
/
├── index.html        # The entire app — single self-contained file
├── netlify.toml      # Netlify deployment config
└── README.md         # This file
```

## Deployment

This site is hosted on [Netlify](https://netlify.com) and deploys automatically whenever changes are pushed to the `main` branch.

To update the MOTD tool:
1. Edit `index.html` on GitHub
2. Commit the change to `main`
3. Netlify redeploys automatically (usually within 30 seconds)

## Running locally

No build step required. Just open `index.html` in any browser.

---

*Hideaway Hunters — HIHUN/WHBOO*
