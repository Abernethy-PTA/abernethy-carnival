# Abernethy Carnival Website — LIVE SOURCE

This directory IS the deployed source. Push to `main` → GitHub Pages auto-deploys.

## Deployment
- **Live URL**: https://carnival.supportabernethy.org
- **GitHub repo**: Abernethy-PTA/abernethy-carnival (public)
- **Hosting**: GitHub Pages, branch `main`, root `/`
- **Deploy**: `git push origin main`

## Design language (current site)
- Modern editorial layout, "chapter" sections with eyebrow + title + subtitle
- Fonts: Fraunces (headings/display), Nunito (body), Caveat (accents)
- Palette: cream (#fdf4dd) → sky (#d8ecf3) gradient background, navy (#1d3a5f) ink, coral (#ec7d72), orange (#e89a3a), teal (#5b9a92)
- Nav: sticky cream bar with backdrop blur
- Map is `carnival-map.jpg` (illustrated overhead) with absolutely-positioned `.map-hot` clickable overlays linking to relevant sections
- Buttons: `.btn .btn-primary` (navy), `.btn .btn-secondary` (cream/coral border), add `.big` for hero CTAs
- Sections use shared `.chapter` wrapper with `.chapter-head` containing `.chapter-eyebrow`, `.chapter-title`, `.chapter-sub`

## Single directory (consolidated 2026-06-05)
- This is the ONE and only working directory. The old stale `abernethy-carnival-live/` split was consolidated away — there is no sibling dir anymore.
- New raw assets (PNGs, generated maps, photos): drop them in, compress to JPG, and commit. No separate scratch dir.

## Content
- Event: Friday May 15 2026, 5:30–8:30 PM
- Location: Abernethy Elementary, 2421 SE Orange Ave, Portland, OR 97214
- Wristbands: $25 advance / $30 at event / $10 pre-elementary / $5 donate-a-bracelet
- Wristband purchase: Konstella (https://www.konstella.com/open/sales/69adb9845b1aa98cd7a03ade) or gazebo May 12–15
- T-shirt sales: https://bashors.chipply.com/abernethycarnival/ (Bashors / Chipply)
- Wristband includes: unlimited games + 1 cotton candy + 1 popcorn + 1 donut
- Does NOT cover: food trucks, Fairy Sparkle hair
- Financial assistance: Jenny Morgan, jmorgan1@pps.net
- Volunteer signup: Konstella, questions → carnival@supportabernethy.org (carnivalhelp@ is retired — never used, no members)
- Cake-a-Palooza: store-bought donations only (PPS allergen rules), drop in auditorium day-of, cake@supportabernethy.org
- General questions: carnival@supportabernethy.org

## Map editing notes
- The map JPG is a flat illustration generated externally (ChatGPT/Gemini). Cannot be edited in code.
- The porta potty has NO clickable hotspot — it's purely decorative on the map.
- To swap the map: replace `carnival-map.jpg` only. No HTML changes needed unless hotspot positions move (none of the hotspot targets coincide with porta potty).
