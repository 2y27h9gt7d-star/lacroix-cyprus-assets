# LaCroix Cyprus — brand asset library

Approved product and brand assets used by the LaCroix Cyprus content pipeline
(invideo, Metricool, Canva). Images are served from this repo so production tools
can fetch them by URL.

| Folder | Contents |
|---|---|
| `cans/` | Transparent can cut-outs per flavour (`can_<flavour>.png`). Use these as the locked product layer — never let AI redraw the can. |
| `emojis/` | Flavour emoji illustrations (transparent). |
| `logo/` | Primary LaCroix logo (transparent PNG). |
| `product-tiles/` | Square product images on white (1200×1200). |
| `photography/` | NBC lifestyle and product photography, resized to max 2400 px. |
| `social-legacy/` | Earlier Cyprus social posts (reference only). |
| `web/` | Compressed WebP images used by lacroixcyprus.com (served via raw.githubusercontent.com; jsDelivr refuses this repo because it is over 50 MB). Cans 280 px tall, gallery/recipes 700 px wide, hero 1920 px plus 608×1080 mobile crops. |

Known gaps: none for cans (Pineapple Coconut added 2026-10-10). No Pineapple Coconut emoji illustration yet.

Raw URL pattern: `https://raw.githubusercontent.com/2y27h9gt7d-star/lacroix-cyprus-assets/main/<folder>/<file>`
