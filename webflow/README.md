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

## Live build (Josh's Personal Site)

- Site ID `6aee816b477be6fef8288a99`, published to https://joshs-personal-site-79260b.webflow.io
- Assets: hero.jpg `6aee81d9a7cb164e17c743ff`, team.jpg `6aee81d9a7cb164e17c74418`
- Home: Code Embed holding `home-embed.html`; SEO title "Joshua “JB” Hameier"
- CMS: "Blog Posts" collection (`/blog/<slug>`) with Summary, Published Date, Cover Image, Body
- Article template: site header embed + `.article` layout bound to the fields above
- Writing page (`/writing`): collection list of `.blog-card` links to each article
