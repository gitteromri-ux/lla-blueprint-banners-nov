# Longevity Blueprint static banners — November pricing

Live Blueprint static ads (Meta ad account 1459085242361281) with the price text updated to the November Standard offer:
**Start for $79, then $169 / mo for 4 months** ($755 total). Design, fonts, layout, colours and photos are unchanged; only the price row text changed.

Hub: https://gitteromri-ux.github.io/lla-blueprint-banners-nov/

| Meta ad id | Ad name | Campaign | Image (Meta name) | Size | Status | Updated file | Original file |
|---|---|---|---|---|---|---|---|
| 52666266371828 | Ad #2 \| Static \| Courtney \| 13.08.26 | ecomm-01 #118148 | LLA_ROUND_6A_1080X1920 (hash 698c4d0a…) | 1080×1921 | Price updated | `updated/ad2_courtney_9x16_1080x1921.png` | `original/ad2_courtney_9x16_1080x1921.png` |
| 52666266371428 | Ad#3 static \| Courtney \| 03.08.26 | ecomm-01 #118148 | c_b3_1x1.png (hash 7386d16e…) | 1080×1080 | No price in image, unchanged | `updated/ad3_courtney_1x1_1080x1080.png` | `original/ad3_courtney_1x1_1080x1080.png` |
| 52669042694228 | Ad#3 static \| Courtney \| 03.08.26 | ecomm-01 #118148 | c_b3_1x1.png (same image) | 1080×1080 | No price in image, unchanged | `updated/ad3_courtney_1x1_1080x1080.png` | `original/ad3_courtney_1x1_1080x1080.png` |
| 52660478522228 | Ad#3 static \| Courtney \| 03.08.26 | FB Leads #117186 | c_b3_1x1.png (same image) | 1080×1080 | No price in image, unchanged | `updated/ad3_courtney_1x1_1080x1080.png` | `original/ad3_courtney_1x1_1080x1080.png` |
| 52669042697828 | Ad#6- static \| Julie \| 03.08.26 | ecomm-01 #118148 | LLA_chosen_chosen_b6_1x1.png (hash 8b4da261…) | 1080×1080 | No price in image, unchanged | `updated/ad6_julie_1x1_1080x1080.png` | `original/ad6_julie_1x1_1080x1080.png` |
| 52661127580828 | Ad#9- static \| Julie \| 20.08.26 | FB Leads #117186 | LLA_BLUEPRINT_1x1_1440x1440.png (hash 2e1e3234…) | 1440×1440 | Price updated | `updated/ad9_julie_1x1_1440x1440.png` | `original/ad9_julie_1x1_1440x1440.png` |
| 52661127060228 | Ad#7 static \| Courtney \| 20.08.26 | FB Leads #117186 | c_b4_191x1.png (hash efed2dd7…) | 1200×628 | No price in image, unchanged | `updated/ad7_courtney_191x1_1200x628.png` | `original/ad7_courtney_191x1_1200x628.png` |

## Sources
- Ad #2 (9:16): `gitteromri-ux/lla-meta-ig-ad-sizes` → `source-pages/LLA-All-Banners.html`, frame 6a 9:16, same renderer as `render_rounds.py`; price text nodes replaced in-DOM, row height locked.
- Ad #9 (1440): `gitteromri-ux/lla-meta-ig-ad-sizes` → `blueprint.html` at commit `8ecd00c` (pixel-matched to the live file), `?f=1x1hi`.
- Ad #3 / #7: `gitteromri-ux/courtney-banners` → `banners/c_b3_1x1.html`, `banners/c_b4_191x1.html`.
- Ad #6: `gitteromri-ux/lla-meta-banners-gallery` → `banners/chosen/chosen_b6_1x1.html`.

`original/` = the image Meta serves today (ground truth). `updated/` = the file to upload. Meta was read-only throughout; nothing was changed in Ads Manager.
