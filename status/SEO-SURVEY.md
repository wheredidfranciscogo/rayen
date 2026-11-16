# Who ranks for plant-app searches — survey of 2026-11-13

Method: 11 web searches through Claude's search tool (US results). This shows what an
engine returns, **not** Google's exact ranking and **not** search volume. Volume needs
Keyword Planner (see the end). Treat everything here as a first read.

## What the results look like

| Search | Who fills the results |
| --- | --- |
| plant watering tracker app | App Store listings, almost exclusively (Terracotta, mizu:log, Sprig, Ginkgo, PlantLog…) |
| plant care app no account no subscription | App Store listings again; several claim "no account" (PlantLog, PlantPal, Plantasia, Plant Daddy) |
| free plant watering reminder app | App Store listings, plus one Apartment Therapy piece on Vera |
| best plant care apps 2026 / best plant watering apps | Mostly affiliate and low-quality SEO pages (sdfi.co.kr, bottegadelsarto.com, a pages.dev blog), a few real publishers (igeeksblog, Reader's Digest, androidguys, appshunter) |
| best Planta alternative free | Directories: AlternativeTo, Product Hunt, GetApp, SoftwareAdvice |
| simple plant tracker web app no download | Almost no hosted web apps: WaterMe (Product Hunt), self-host projects (Sempervivum, HortusFox), Jotform templates, GitHub repos |
| plant tracker PWA install home screen | Generic PWA guides; **no plant-tracker PWA came up at all** |
| how to keep track of when you water your plants | Small blogs and printables (bullet-journal trackers, free printable PDFs) |

## Reading it

1. **"Plant app" and "best plant care app" are not worth chasing.** App Store pages and
   Planta own the head terms, and the listicle results are a crowd of spam, so even a
   good article would have to out-trust real publishers.
2. **The no-download, no-account web app is a real gap.** For queries phrased that way,
   the engine had nothing polished to show. Rayen's pitch fits those words exactly.
3. **"No account / data stays on your device" is not unique among native apps**, so it
   should not be the only claim. "Nothing to install" is the part nobody else says.
4. **The informational query is won by small blogs**, which is the best place for an
   article plus a "or just use it here" link to the app.
5. **"Alternative to X" results are directories.** Being listed on AlternativeTo and
   Product Hunt is a smaller job than writing articles, and it targets those searches.

## Phrases worth testing for volume

- plant tracker no download · online plant watering tracker · plant watering log online
- plant app no account · plant care app no subscription · free plant tracker website
- how to keep track of when you water your plants (informational)
- Planta alternative free (via AlternativeTo / Product Hunt, not an article)

Avoid: "plant app", "best plant care app", "plant identification".

## Google Trends read, 2026-11-14

Method: worldwide, web search, read from the Explore page (skill: `keyword-trends`). Relative
numbers: 100 = peak of the biggest phrase in the batch. Two batches (5 years, then 12 months)
that share "plant tracker" and "plant care app". The 12-month batch carries the sizing; the
5-year batch is only for seasonality and for "plant app" and "planta app".

| Phrase | Size (12 months, "plant tracker" = 1×) | Notes |
| --- | --- | --- |
| plant tracker | 1× (average 39) | Measurable, but ambiguous: rising related queries are fitness trackers |
| plant care app | about 0.8× (average 31) | Measurable and clean. Rising related: "free plant care app android" |
| plant watering app | about 0.13× (average 5) | Small. Only related query: "best plant watering app" |
| plant reminder app | about 0.03× (average 1) | Barely registers |
| plant watering tracker | no data | Too small for Trends. This is the phrase the About page leads with |
| houseplant tracker | no data | Too small for Trends |
| plant app | 20 against 1–2 for the rest (5-year batch) | **Polluted.** Its 2025–26 surge came with "chatgpt app" and "ai news today" as rising queries. Not evidence |
| planta app | about 2 (5-year batch) | Brand search, small and steady |

Seasonality: every plant phrase peaks March to June and bottoms out October to November, the
same shape in each of the last five years (northern-hemisphere spring). It is November now:
"plant tracker" sits at 5 against a spring peak of 100.

Top regions for "plant app": Kenya, Nigeria, New Zealand, South Africa, India (English-speaking,
mostly non-US). For "plant tracker": Hong Kong, Kazakhstan, Algeria, Finland, Philippines.

Consequences for the site:

1. The About page leads with "plant watering tracker", which Trends cannot even measure.
   "Plant care app" and "plant tracker" are roughly ten times larger and both describe Rayen.
   Worth working one or both into the About title or description. Not changed yet.
2. Index the site before spring. Search interest is at its yearly low, so there are about four
   months to be crawled and ranked before the March–May rise.
3. Skip "plant app" as a target, as the web survey above already advised: now confirmed noisy.
4. Trends sizes phrases but gives no monthly volumes. Autocomplete, Search Console and the Ads
   website's Keyword Planner are the next layers.

## Not known yet

- Absolute search volume for any of the above. Needs Keyword Planner: through the Google Ads
  API (Basic access, blocked on the OAuth brand check) or through the Ads website. Likely broad
  ranges only, since the Ads account has no spend.
- Whether WaterMe or others still maintain a web version. Not checked.
