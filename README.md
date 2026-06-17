# The Portfolio Board — Marc C.

An interactive, single-page portfolio for Marc Cannon, founder of **EvolvedLotus**.

Projects are pinned to a Kanban-style board across a product lifecycle —
**Concept → Built → Live → Results** — and styled like a brand strategy war room.
Visitors pick who they are (Potential client, Brand/Agency, or Fellow creator) and the
board reshuffles and rewrites each card to speak to them.

## Features

- **Persona switcher** — re-sorts the board and rewrites every card's title, goal, and
  metric for the selected audience.
- **Draggable cards** — rearrange the board by hand; switching persona resets the layout.
- **Brand hierarchy** — each card is tagged with the brand it sits under
  (EvolvedLotus, SBC | RSS, or Personal).
- **Demo videos** — cards can open a built-in popup player (e.g. the Kingdom Siege demo).
- Self-contained: all HTML, CSS, and JS live in `index.html`. No build step.

## Projects on the board

| Brand | Projects |
|-------|----------|
| **EvolvedLotus** | EvolvedLotus, LotusReplies, EVL Discord Bot, LotusCut, ThisWeeksYT, Blog |
| **SBC \| RSS** (acquired by EvolvedLotus) | SBC \| RSS, Stack Showroom, CorePulse, MonetifyGram |
| **Personal** | Kingdom Siege (built, not public), WallpaperTask (in progress) |

## Structure

```
.
├── index.html              # the entire page (HTML + CSS + JS inline)
├── README.md
└── assets/
    ├── MCsignature.png      # logo / signature mark
    └── kingdomsiegedemo.mp4 # Kingdom Siege demo video
```

## Run locally

Open `index.html` in any browser — no server or build required.

## Deploy

Static site. Upload the whole folder (keep the `assets/` subfolder) to any static host:

- **GitHub Pages** — push to the repo, then enable Pages on the `main` branch (root).
- **Netlify / Cloudflare Pages** — drag-and-drop the folder or connect the repo.

Fonts load from Google Fonts via CDN; everything else is local.

## Notes

- The demo video is large (~44 MB). If it loads slowly once deployed, host it on
  YouTube/Vimeo (unlisted) and swap the player for an embed.
- The "Book a strategy call" and "Contact" links point to
  `https://www.evolvedlotus.com/#cusection`.
