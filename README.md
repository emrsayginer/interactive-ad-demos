# Interactive display creatives — live demos

Running HTML5 display creatives, served as the ad server would receive them:
one HTML document each, **no external requests at runtime**, system fonts only.

Live: https://emrsayginer.github.io/interactive-ad-demos/

| Creative | Sizes | Notes |
|---|---|---|
| Neon Star Shooter — pick a planet | 970×250, 300×600, 300×250, 320×480, 728×90, 320×50 | Six game scenes WebP-embedded per build; largest build 128 KB against the IAB 150 KB initial-load limit |
| ZEPHR playable | fullscreen | Four network builds (MRAID / Meta / Google / Pangle); everything drawn in code |
| ORSA Black Friday phases | 970×250 | Fixed campaign timestamp, clamped at zero |
| ORSA free-shipping box | 300×600 | Threshold mechanic run inside the ad |
| ORSA size and stock | 300×250 | Sold-out sizes stay visible, struck through |

ORSA is a fictional brand made for these demos. Neon Star Shooter is my own game
and the scenes come from it. Click-through URLs are placeholders; a live campaign
uses the ad server's clickTag.
