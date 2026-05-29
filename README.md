# Vectoy — Public Assets

World-readable host for **rendered game assets only** — UI mockups (live HTML) and concept art (PNGs). The Game Design Document and all source live in the **private** `Vectoy-Game-Dev` repo and are never published here.

## What goes here

- `ui/<screen>/` — standalone HTML/CSS mockups, served live via GitHub Pages and embedded into Notion.
- `concept/` — concept-art PNGs (Nano Banana output), referenced in Notion via raw URLs.

## Pipeline

1. Asset authored (mockup HTML, or art generated via Nano Banana on Desktop).
2. Pushed here via the GitHub MCP.
3. **UI:** served by GitHub Pages → embedded live in the 🎨 UI/UX Notion page with `/embed`.
4. **Art:** referenced in Notion as an image via `https://raw.githubusercontent.com/Jakers011/vectoy-assets/main/concept/<file>.png`.

## Live URLs (after Pages enabled)

| Screen | Path | Live URL |
|---|---|---|
| Phase 4 — Resolution | `ui/phase4-resolution/` | https://jakers011.github.io/vectoy-assets/ui/phase4-resolution/ |

## Design tokens (starter palette — ratify into Notion)

Surfaces: `#2b2438` felt · `#38304a` panel · `#423a55` card · `#574d70` edge  
Ink: `#fdf6ec` bright · `#b9add0` muted · `#8579a0` dim  
Resources: Food `#6fcf5f` · Wood `#b5793f` · Stone `#9aa6b2` · Gold `#f4c54a` · Iron `#7f8fd6`  
Accents: skull-glow `#ff5d6c` · reroll `#57d6c4` · charge `#c98bff`  
Fonts: Fredoka (display) · Nunito (body)
