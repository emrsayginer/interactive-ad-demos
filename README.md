# Interactive display creatives — live demos

Running HTML5 display creatives, served as the ad server would receive them:
one HTML document each, **no external requests at runtime**, system fonts only.

Live: https://emrsayginer.github.io/interactive-ad-demos/

| Creative | Sizes | Notes |
|---|---|---|
| Neon Star Shooter — pick a planet | 970×250, 300×600, 300×250, 320×480, 728×90, 320×50 | Six game scenes WebP-embedded per build; largest build 128 KB against the IAB 150 KB initial-load limit |
| ZEPHR playable | fullscreen | Four network builds (MRAID / Meta / Google / Pangle); everything drawn in code |
| KORVAL sun path (real estate) | 970×250, 300×600, 160×600, 300×250, 728×90, 320×50 | Drag the sun around the floor plan; rooms light by the bearing of their windows. 11 KB, no images |
| TALLO hours back (B2B software) | same six sizes | Approvals-a-week slider; hours, days and yearly cost from a stated formula, one square per approval |
| ORSA colour and price | same six sizes | Tap a colour: SVG garment takes the dye, tag flips to that colour's price, sold-out colour stays listed |
| LEDGA animated HTML5 (design to banner) | same six sizes | Three-frame animated unit on a JS timeline, three loops then end frame, reduced-motion aware |
| PULSA hold the plank (home fitness) | same six sizes | Press-and-hold timer; figure shakes with time, result placed on a four-week programme |
| ORSA Black Friday phases | 970×250 | Fixed campaign timestamp, clamped at zero |
| ORSA free-shipping box | 300×600 | Threshold mechanic run inside the ad |
| ORSA size and stock | 300×250 | Sold-out sizes stay visible, struck through |

ORSA, KORVAL, TALLO, LEDGA and PULSA are fictional brands made for these demos. Neon Star Shooter is my own game
and the scenes come from it. Click-through URLs are placeholders; a live campaign
uses the ad server's clickTag.
