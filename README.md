# Competitor v1.5

**Edge to edge on every screen size (v1.5, 27 Oct 2026)** — no centred 800 px column on laptops and no 20 px gutter on phones; full-bleed cards with 10 px inner padding; platform results in columns on wide screens.

**WhatsApp preview + Share button (v1.4, 27 Oct 2026)** — `og-banner.jpg` (1200×630 JPEG under 300 KB) with `og:image:type image/jpeg`, so WhatsApp shows the picture; a **Share this app** button (`ibi-share.js`) sits beside the theme button. The old `og-banner.png` stays deployed.

**Own app identity (v1.3, 7 Oct 2026)** — the install manifest now carries `"id": "/Competitor/"`. Before, `"id": "./"` resolved to the bare origin `https://indiabusinessinternational.github.io/`, which every IBI app published under github.io shared — so Chrome treated installing a second such app as an UPDATE of the first and silently re-pointed it (an installed IBI Gold Mines icon opened Screen Recorder Studio). The new id is unique to this app. An install made before this release keeps the old shared id; uninstall it and install again from the page.

Competitor Links will be used to fix prices of ecommerce products.
