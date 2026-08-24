# Arcanum — Fifth-Edition DM Toolkit

A free, **unofficial** browser toolkit for running fifth-edition tabletop RPG sessions. It's a single self-contained HTML file — no install, no server, no account. Everything you create is saved in your own browser.

## Features

- **DM Screen** — conditions, DCs, cover, death saves, actions, vision & light, travel pace
- **Adventure runner** — build, import, store, and switch between multiple adventures; smart-parse your own notes into chapters & scenes; mark scenes done; drop a scene's monsters into initiative
- **Initiative tracker** — HP/AC/status, round tracking, auto-sort
- **Encounter builder** — 2024 XP budgets by party size/level/difficulty and environment, with full statblocks
- **Roll tables** — d100 / any-die tables that auto-roll the quantity dice in each result
- **Generators** — shopkeepers, NPCs, treasure hoards
- **Compendium** — searchable reference for the bundled SRD monsters, magic items, and spells
- **Content library** — add your own monsters/items (paste a statblock and it auto-fills), or import open-license data (e.g. via the Open5e API)
- **Dice roller**, **notes**, **resource links**, and **JSON backup/restore**

## Run it locally

Download `index.html` and double-click it — it opens in any modern browser. Your data lives in that browser; use the **Backup** button (top bar) to export a JSON file you can restore on another device.

## Host it on the web (free)

It's a static file, so any static host works:

- **Netlify Drop** — go to <https://app.netlify.com/drop> and drag the folder in. Instant public URL.
- **GitHub Pages** — put `index.html` in a repo, then Settings → Pages → deploy from the main branch. Free, custom-domain capable.
- **Cloudflare Pages / Vercel / itch.io** — all work the same way.

Note: state is per-browser localStorage, so every visitor gets their own private copy. There are no shared accounts or cross-device sync.

## Content & licensing

- The **application code** is released under the MIT License (see `LICENSE`).
- The bundled **game content** (monsters, magic items, spells) is from the **System Reference Document 5.1**, © Wizards of the Coast LLC, provided under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/legalcode). Some entries were reformatted for this app. Data sourced via [Open5e](https://open5e.com).
- Any adventure or campaign content **you** import is your own responsibility.

## Disclaimer

This tool is **not affiliated with, endorsed, sponsored, or approved by Wizards of the Coast**. It is an independent, unofficial utility compatible with fifth-edition rules.
