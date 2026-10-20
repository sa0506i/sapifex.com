# sapifex.com

Static site of Sapifex, served by GitHub Pages from `main` (root), custom domain `sapifex.com` (`CNAME`). No build step, no JavaScript, no third-party requests: the B612 fonts (SIL OFL, `assets/fonts/OFL.txt`) are self-hosted and the icons (Lucide, ISC) are inlined.

| Path | Content |
| --- | --- |
| `index.html` | Sapifex: who, what, the apps, contact |
| `pilots-seat/index.html` | Pilot’s Seat product page in the app's own skin (dark, B612, Lucide icons, the store screenshots incl. Glass and HUD) |
| `pilots-seat/privacy/index.html` | Pilot’s Seat privacy policy (English and German) and support; the URL both stores get |
| `anyvoc/index.html` | Anyvoc in short, pointing to anyvoc.eu |
| `imprint/index.html` | One imprint for the site and all Sapifex apps (§ 5 DDG, § 18 MStV) |
| `assets/site.css` | Shared styles; `html.ps` switches a page to the Pilot’s Seat skin, `html.product` widens it |

Store URLs: privacy policy `https://sapifex.com/pilots-seat/privacy/`, support `https://sapifex.com/pilots-seat/privacy/#support`, imprint `https://sapifex.com/imprint/`.

Editing rules: every content change on a legal page bumps its "Last updated" date in the same commit. Screenshots and the app icon come from the PilotsSeat repository (`docs/release/store-screenshots/`, `assets/pilotsseat-icons/store/`); copy them over when they change.
