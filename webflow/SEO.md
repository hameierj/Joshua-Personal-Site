# SEO setup (applied in Webflow)

| Page | Title | Structured data | Head extras |
|---|---|---|---|
| Home `/` | Joshua “JB” Hameier | Person + WebSite + ProfilePage (`@graph`) | canonical, og:type profile, twitter large card, robots max-image-preview |
| Writing `/writing` | Writing — Joshua “JB” Hameier | Blog (author/publisher → #person) | canonical, og:type website, twitter large card |
| Blog template `/blog/<slug>` | (set in Designer, bound to Name) | — | og:type article, twitter large card |

- Social share image: team.jpg (1800×1200) on Home and Writing.
- Alt text set on hero.jpg and team.jpg assets.
- Home and Writing included in the Webflow sitemap.
