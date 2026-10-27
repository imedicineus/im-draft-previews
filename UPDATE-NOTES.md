# Oct 27 update notes (draft preview republish)

## Preview
- Public noindex: https://imedicineus.github.io/im-draft-previews/
- Index: https://imedicineus.github.io/im-draft-previews/preview/
- Homepage draft: https://imedicineus.github.io/im-draft-previews/im-homepage/index.html
- Repo: imedicineus/im-draft-previews (robots noindex)

## Constraints honored
- Restyle/edit only; no new pages (still 56)
- Cities line + Ready-to-talk CTA only at page bottom (one `.blk.cta` per page)
- No cream/gold; no live WP/Hostinger writes
- Overlap max 29.2% (<30%)

## Palettes per site (exact; source noted)
| Site | navy / deep / royal / green / btn | Source |
|---|---|---|
| integrativemedicine-us | `#0b2440` `#123a63` `#2b86d6` `#3fae87` `#4aa33d` (footer `#001249`) | live integrativemedicine.us/dry-needling/ CSS + Divi customizer |
| coralspringsacupuncture | `#003300` `#0d772e` `#2ea3f2` `#7cda24` `#008000` | live coralspringsacupuncture.com |
| bocaraton-acupuncture | `#0e2620` `#1d5b48` | redesign proof (live nearly empty) |
| acupuncturebocaratonfl | `#1c2422` `#1f5f4a` `#0090ce` / btn `#00bfe5` | live + redesign accent |
| acupuncturetamarac | `#1f6581` `#2ea3f2` `#29c4a9` | live et-cache |
| cr8health | `#111111` `#1d6186` `#046bd2` `#4cc5c8` | live Elementor/Astra |
| coconutcreek | `#083000` `#054907` `#7cda24` | live et-cache |
| parkland | `#0c9300` `#02d002` `#2ea3f2` `#7cda24` | live et-cache |

Implemented in `gen/palettes.py` → `css_vars(site)` injected after base CSS so site tokens win.

## Parkland letter / Coconut Creek five-things
**Why:** Not from `gen/sites.py` (only voice I/he, phone, cities, footer_addr). Formats were intentional writing choices in `src/parkland/*.md` and `src/coconutcreek/*.md`.
**Change:** All 14 rewritten to dry-needling clinic sections (Short Version / Where It Tends to Help / What to Expect / Safety / FAQ). Letter ("Dear…", "Warmly") and numbered Five Things removed. Backups in `/tmp/src-bak-letter-fivethings/`.

### Before → After (acupuncture H2s)
- Parkland before: Where I See Parkland Patients; What Acupuncture Is; Research; First Visit; What I Commonly Treat; How Many Visits
- Parkland after: The Short Version; Where It Tends to Help; What to Expect; How Care Is Planned; How It Works With Your Doctors; Safety
- CC before: 1. Needles Are Tiny … 5. Works Alongside Your Family Doctor; What Brings Coconut Creek Families In
- CC after: The Short Version; Where It Tends to Help; What to Expect; How Care Fits Busy Schedules; Working With Your Family Doctor; Kids and Needle Shy Adults

## Phone
- Drafts / Parkland / IM: **954.884.0099**
- Coconut Creek: **(954) 828-2620**
- Note: live IM dry-needling also shows (954) 775-3765 on some CTAs

## Mobile 390px
- IM drafts + homepage: no horizontal overflow after `.tablewrap`; no sliders/carousels on draft pages

## Open questions (unchanged)
Fonts (drafts Fraunces+Inter vs live Divi Open Sans); Gulou; Nine Celestial Cycle; flat slugs/500s; IM /acupuncture/ 301; stem-cell alt; no treating/wife photo; cr8 locations; CC area claims; Parkland no street address; "4 clinics"/telehealth/20 years.
