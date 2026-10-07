# Competitor v1.3

**Own app identity (v1.3, 7 Oct 2026)** — the install manifest now carries `"id": "/Competitor/"`. Before, `"id": "./"` resolved to the bare origin `https://indiabusinessinternational.github.io/`, which every IBI app published under github.io shared — so Chrome treated installing a second such app as an UPDATE of the first and silently re-pointed it (an installed IBI Gold Mines icon opened Screen Recorder Studio). The new id is unique to this app. An install made before this release keeps the old shared id; uninstall it and install again from the page.

Competitor Links will be used to fix prices of ecommerce products.
