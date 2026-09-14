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
| LEDGA animated HTML5 (design to banner) | fourteen sizes: the six above plus 970×90, 468×60, 336×280, 250×250, 200×200, 120×600, 320×100, 300×50 | Three-frame animated unit on a JS timeline, three loops then end frame, reduced-motion aware |
| PULSA hold the plank (home fitness) | same six sizes | Press-and-hold timer; figure shakes with time, result placed on a four-week programme |
| VELMOR set the hour (luxury watch) | same six sizes | Drag the dial: light on the sapphire follows the hour, lume takes over after dark. Rich media with one mechanic, 14 KB |
| ARVEN move a coin (retail banking) | same six sizes | Tap coins between Spend now and Save; scale tips, five-year figure computed from a stated rate inside the ad |
| KEVRA where is it now (B2B logistics) | same six sizes | Animation-only rebuild of a storyboard: route draws itself, measures slide in, end frame holds. Same timeline engine as LEDGA |
| ALDRA hurt in a crash (legal services) | fourteen sizes, same list as LEDGA | Animation-only injury-law unit: shield draws itself, three steps light along a line, brand and CTA hold. "Attorney advertising" label in every size |
| ORSA end of season sale (e-commerce) | fourteen sizes, same list as LEDGA | Animation-only sale unit: three product tiles stay in every frame, prices strike through and restamp tile by tile, brand, deadline and CTA hold. Tiles shed detail by size |
| ORSA Black Friday phases | 970×250 | Fixed campaign timestamp, clamped at zero |
| ORSA free-shipping box | 300×600 | Threshold mechanic run inside the ad |
| ORSA size and stock | 300×250 | Sold-out sizes stay visible, struck through |
| OKTAV story reveal (consumer electronics) | 300×250 | Three-scene vertical-story format; hold to pause, tap an edge to skip |
| ROLIO swipe to match (recruiting) | 300×250 | Dating-app card stack for job listings; drag or tap to match/pass, auto-demo until first swipe |
| VINDO spin for a code (e-commerce) | 300×250 | Gamified spin wheel; spins itself once unattended, six weighted outcomes including a genuine "try again" |
| FARNO before/after slider (home renovation) | 300×250 | Drag-compare kitchen remodel; clip-path driven by pointer position, auto-demo transition on load |
| KELWEN chat your way to a plan (SaaS) | 300×250 | Sequential chat-bubble Q&A with typing indicator; branches to a plan recommendation, auto-answers if left untouched |
| DOVANE pull the lever (loyalty/rewards) | 300×250 | Gacha capsule vending machine; lever pull drops and cracks a capsule, random prize from a five-item pool |
| VELTIC test your reflexes (telecom/broadband) | 300×250 | Reaction-timer mini-game; wait-tap-arm cycle with a millisecond readout, auto-demo round on load, early taps called out |
| VAERIS unlock your free scan (cybersecurity) | 300×250 | Rotary combination-lock dial; drag through three marks to spring the shackle, auto-rotates once unattended |
| PURENZO sort it right (sustainability/recycling) | 300×250 | Drag-to-sort game across four items and two bins; wrong drops shake back for a retry, auto-sorts if left alone, score counts first-try only |
| CRATIQ stack it, we'll move it (moving/storage) | 300×250 | Tap-drop stacking game; a box drifts over the last one placed, overlap on drop decides a clean stack vs. a miss, auto-drops if left alone |
| BALANTO keep it level (personal finance/budgeting) | 300×250 | Drag dollar chips onto a Save or Spend pan; a beam tilts by the running imbalance, auto-assigns if left alone, final read is balanced or the dollar gap |
| LUMORA bring it into focus (optical/eyewear) | 300×250 | Connect five dots in strict order to progressively sharpen a blurred eye chart behind them; auto-traces one dot at a time if left alone |
| ECHONYX feel it in sync (audio/headphones) | 300×250 | Tap a glowing orb exactly on beat, five times, filling a progress ring; auto-taps in time if left alone |
| OBSIDRA feel it launch (automotive/EV) | 300×250 | Drag a throttle knob to the top and hold to launch, with a sweeping gauge and light-streak effect; auto-ramps if left alone, ends on a 0-60 time |

ORSA, KORVAL, TALLO, LEDGA, PULSA, VELMOR, ARVEN, KEVRA, ALDRA, OKTAV, ROLIO, VINDO, FARNO, KELWEN, DOVANE, VELTIC, VAERIS, PURENZO, CRATIQ, BALANTO, LUMORA, ECHONYX and OBSIDRA are fictional brands made for these demos. Neon Star Shooter is my own game
and the scenes come from it. Click-through URLs are placeholders; a live campaign
uses the ad server's clickTag.
