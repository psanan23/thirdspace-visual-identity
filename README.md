# Third Space — Visual Identity Toolkit

The visual and editorial rulebook for [@thirdspace.her](https://instagram.com/thirdspace.her). A working toolkit for the multi-dimensional mother in Southeast Asia.

**Live site:** _(GitHub Pages URL appears here after first push)_

---

## What this is

A static HTML site that any human, designer, or AI tool can open before making content for Third Space. It defines:

- **Brand foundation** — manifesto, audience, the three jobs every post must do
- **Visual fundamentals** — colour palette, typography, wordmark direction
- **The post library** — five post types, the feed pattern, anatomy of each
- **Photography** — principles, treatment options, what we don't do
- **Voice** — three tone attributes, caption specs, community management
- **AI briefing** — ready-to-paste prompts for Claude, ChatGPT, Midjourney, Canva

The toolkit is the source of truth. If something contradicts the toolkit, the toolkit wins.

---

## File structure

```
.
├── index.html              # Overview / entry point
├── css/style.css           # Shared stylesheet — edit once, change everywhere
├── pages/
│   ├── brand.html          # Manifesto, audience, content jobs, pillars
│   ├── color.html          # Palette
│   ├── type.html           # Typography
│   ├── logo.html           # Wordmark direction (open decision)
│   ├── posts.html          # Five post types + feed grid
│   ├── photography.html    # Photography principles + treatment (open decision)
│   ├── voice.html          # Tone of voice
│   ├── ai-brief.html       # Prompts for AI tools
│   └── downloads.html      # Fonts, swatches, brand docs
├── decisions/
│   └── index.html          # Side-by-side previews for open decisions
├── assets/fonts/           # Cormorant Garamond + Inter (variable .ttf)
└── README.md
```

---

## How this is meant to be used

- **You, before posting:** open the relevant page, follow the rule.
- **A designer:** send them the link. Skip the brief.
- **An AI tool:** copy the prompt from [Brief an AI](pages/ai-brief.html), paste, generate.

---

## v2 — what's open

Three decisions are unresolved. The kit reflects whichever option is currently chosen.

1. **Wordmark direction** — Inter Masthead vs. Cormorant Stacked
2. **Photography treatment** — Editorial B&W vs. Warm muted colour
3. **Pillar signposting** — Named tag vs. Numbered pillar

See [`decisions/index.html`](decisions/index.html) for the side-by-side preview. Once chosen, the kit gets updated and the version bumps to v3.

---

## How to edit

The site is plain HTML and CSS. No build step. No frameworks.

- **To change a colour or font:** edit `css/style.css` at the top. The CSS variables propagate everywhere.
- **To change a section:** edit the relevant page in `pages/`.
- **To add a page:** copy any existing page, change the content, add it to the nav in every page header.

GitHub Pages serves the repo directly. After pushing, the live site updates within a minute.

---

## Built off

- `OUTPUTS/Third Space/VISUAL-IDENTITY-v1-2026-05-08.md` — the v1 spec
- `OUTPUTS/Third Space/SOURCE-OF-TRUTH.md` — the brand brief
- `OUTPUTS/Third Space/MANIFESTO.md` — opening prose (v3)
- Spotify's 2025+ Social Style Guide — for the toolkit framework (mandatory vs. flexible elements, tone-of-voice structure, do/don't pattern). We do not pull Spotify's visual register.

---

## License

Private. All rights reserved.
