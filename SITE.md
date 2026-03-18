# My Website

> A personal site with retro terminal vibes

## Brand Identity

- **Personality**: Fun, nostalgic, techy but approachable
- **Vibe**: Old-school text editor meets personal blog — like coding in the 90s

### Colors
- Background: Deep navy (`#1a1a2e`)
- Surface/cards: Darker blue (`#16213e`)
- Main text: Off-white (`#edf2f4`)
- Accent (cyan glow): `#64ffda`
- Secondary accent (pink): `#f72585`
- Headings: Amber/gold (`#ffd700`)

### Fonts
- **Space Mono** — A fun, characterful monospace font for everything (headings and body)
- Loaded from Google Fonts

### Style Details
- Subtle scanline overlay for CRT monitor effect
- Blinking cursor next to the logo
- Code-style prefixes (like `#`, `//`, `→`)
- Bracket decorations around nav links `[Home]`
- Left border accents instead of cards
- Glowy hover effects on buttons

## Pages

- **Homepage** (`index.html`) — Welcome section with intro text and three feature highlights
- **About** (`about.html`) — About page with story section

## Recent Changes

- March 2026: Redesigned with retro terminal aesthetic using Space Mono font, dark color scheme, and code-editor styling

## How to Customize

- **To change colors**: Edit the CSS variables at the top of `styles.css` (look for `:root`)
- **To change the font**: Update the Google Fonts link in each HTML file and the `--font-mono` variable in CSS
- **To turn off scanlines**: In `styles.css`, find `body::before` and change `opacity: 0.3` to `opacity: 0`
- **To add a new page**: Copy `about.html`, rename it, and update the content
