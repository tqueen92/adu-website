# Amsterdam Data Union — website

A trusted network of data people in the Netherlands.

**Live:** https://tqueen92.github.io/adu-website/

## Values

- **Share openly** — panels and talks where companies share how they solve real problems.
- **No sales pitch** — no product pitches, no sponsors steering the conversation.
- **Small room, face to face** — we meet in person and keep the group small.

## What's in this repo

- `index.html` — the whole site (HTML, CSS and JS in one file)
- `images/logos/` — company logos (PNG)
- `images/photos/` — event photos

## Common updates

- **Values:** the "Not another meetup" section (`ul.gets` in `index.html`)
- **Stats:** `ul.stats` — events, speakers and moderators, companies on stage, LinkedIn followers
- **Logos:** add the PNG to `images/logos/`, then add a `<li class="logo">` line to `ul.logos`. Update "companies on stage" to match.
- **Contact form:** sends to a Google Form (`GOOGLE_FORM` in the script at the bottom of `index.html`)

Keep values, tagline and stats in sync with the one-page pitch: https://github.com/tqueen92/adu-pitch

## Publishing

GitHub Pages publishes from `main`. Changes go live 1–2 minutes after a commit. Use a hard refresh (Cmd + Shift + R) to see them.
