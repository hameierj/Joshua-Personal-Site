# Webflow build bundle

Rebuild of the personal site artifact for Webflow.

| File | Where it goes in Webflow |
|---|---|
| `site-head.html` | Site settings → Custom code → Head (CSS + Google Fonts, plus blog styles) |
| `home-embed.html` | Code Embed on the Home page (swap `hero.jpg` / `team.jpg` for the Webflow asset URLs) |
| `site-footer.html` | Site settings → Custom code → Footer (page script, guarded so it no-ops on blog pages) |
| `assets/` | Upload as Webflow assets |
| `source-artifact.html` | The original artifact, for reference |

Home page title: Joshua “JB” Hameier
