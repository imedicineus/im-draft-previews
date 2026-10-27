# Oct 27 update notes (draft preview republish)
## Palettes per site
- **integrativemedicine-us**: navy `#0b2440` deep `#123a63` royal `#2b86d6` green `#3fae87` btn `#4aa33d` — source: live https://integrativemedicine.us/dry-needling/ embedded page CSS (style block) + Divi customizer footer #001249
- **coralspringsacupuncture**: navy `#003300` deep `#0d772e` royal `#2ea3f2` green `#7cda24` btn `#008000` — source: live coralspringsacupuncture.com HTML/CSS (#7cda24, #008000, #0d772e, #2ea3f2, #7cc68d)
- **bocaraton-acupuncture**: navy `#0e2620` deep `#1d5b48` royal `#1d5b48` green `#1d5b48` btn `#1d5b48` — source: boca-acupuncture-redesign/site/assets/style.css (live HTML had almost no theme colors; #1d5b48 only)
- **acupuncturebocaratonfl**: navy `#1c2422` deep `#1f5f4a` royal `#0090ce` green `#1f5f4a` btn `#00bfe5` — source: live acupuncturebocaratonfl.com (#e6dccf, #a68b6a, #00bfe5, #0090ce, #f6f1ea) + redesign greens as accent
- **acupuncturetamarac**: navy `#1f6581` deep `#27323a` royal `#2ea3f2` green `#29c4a9` btn `#2ea3f2` — source: live acupuncturetamarac.com et-cache/HTML (#2ea3f2, #29c4a9, #1f6581, #82c0c7)
- **cr8health**: navy `#111111` deep `#1d6186` royal `#046bd2` green `#4cc5c8` btn `#1d6186` — source: live cr8health.com Elementor/Astra globals (#1d6186, #4cc5c8, #046bd2, #334155, #f0f5fa)
- **coconutcreek**: navy `#083000` deep `#054907` royal `#7cda24` green `#7cda24` btn `#7cda24` — source: live acupuncturecoconutcreek.com et-cache (#7cda24, #083000, #054907, #27323a)
- **parkland**: navy `#0c9300` deep `#02d002` royal `#2ea3f2` green `#7cda24` btn `#0c9300` — source: live acupunctureparkland.com et-cache (#0c9300, #7cda24, #02d002, #2ea3f2)

## Parkland letter / Coconut Creek five-things
**Why:** Not forced by `gen/sites.py` (that file only sets `voice` I vs he, phone, cities, footer). The letter and five-things formats were writing choices in `src/parkland/*.md` and `src/coconutcreek/*.md` (and similar in Oct 26 cornerstones).
**Change made:** Rewrote all 14 pages to dry-needling clinic structure (The Short Version / Where It Tends to Help / What to Expect / Safety / FAQ). Letter framing (Dear neighbor, Warmly) and Five Things numbering removed. Trigram overlap vs prior versions under 30% (max pair across sites now 29.2%).

### Before (sample H2s)
- Parkland acupuncture: ## Where I See Parkland Patients, ## What Acupuncture Is, ## What the Research Tells Us, ## What Your First Visit Will Feel Like, ## What I Commonly Treat, ## How Many Visits You May Need
- Coconut Creek acupuncture: ## 1. The Needles Are Tiny, ## 2. Research Supports It for Several Common Problems, ## 3. The First Visit Is Mostly Talking, ## 4. It Fits Into Busy Family Schedules, ## 5. It Works Alongside Your Family Doctor, ## What Brings Coconut Creek Families In

### After (sample H2s)
- Parkland acupuncture: ## The Short Version, ## Where It Tends to Help, ## What to Expect, ## How Care Is Planned, ## How It Works With Your Doctors, ## Safety
- Coconut Creek acupuncture: ## The Short Version, ## Where It Tends to Help, ## What to Expect, ## How Care Fits Busy Schedules, ## Working With Your Family Doctor, ## Kids and Needle Shy Adults
