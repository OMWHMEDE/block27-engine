# BLOCK27 Content Engine

This folder is the brain for BLOCK27's content. Read this file first, every time.

This engine is for **TikTok slideshows** only — everything below + folders 01–07.

**Always write new decisions, rules and results into these files and push** — this is the memory.

## What BLOCK27 is
An AI stylist for the clothes you already own. You show it your closet, it builds the outfits. iOS app, pre-launch (Apple enrolment Nov 6, 2026). Waitlist: block27.app.

## The operator
HMEDE, solo founder. English only. **Keep every reply short** — he will not read long text. Plain lists, no tables when he needs to tap/copy links. Do only what he asked. After any change to a script or set, resend the complete version.

## How the engine works (the loop)
1. **Trend scan** → `02-research/trends/YYYY-MM-DD.md` (skill: trend-scan)
2. **Daily pack** → one set per account per slot in `04-sets/YYYY-MM-DD-slug/set.md` (skill: daily-pack)
3. HMEDE generates images in **ChatGPT (Pro, no API)**, types slide text **inside TikTok**, posts.
4. **Every 3 days** HMEDE reports by set ID (first: Oct 26, 2026). See 07-results/report-agreement.md. Posts under 48h = early read only. → log + new rules (skill: log-results)
5. Before writing anything new: read `07-results/winners.md` and `07-results/failure-log.md`.

## Folder map
- `01-app/` app-brief.md (magic moment, pains, objections, **pain bank**), personas.md, accounts.md, assets/ (real Expo Go screenshots)
- `02-research/` swipe/ (outlier slideshows found), formats/ (one file per proven structure), trends/ (one file per day)
- `03-ideas/backlog.md` scored ideas
- `04-sets/` one folder per set: `YYYY-MM-DD-slug/set.md`
- `05-templates/` ChatGPT prompt templates
- `06-queue/` approved + posting manifest per day
- `07-results/` performance.csv, winners.md, failure-log.md
- `.claude/skills/` one skill per step

## Standing rules
- **CTA position (all accounts):** ALWAYS slide 3 — 2 slides after the hook. Content continues after it.
- **Locked formats:** TRUTH = 02-research/formats/truth-breakdown.md. media = media-masked-27.md. PEAK = peak-mirror-fits.md. SMOKE = smoke-fits.md. NOBS = nobs-colour-trios.md. Never change a locked format without HMEDE.
- **Platform:** slideshows go to **TikTok only** (5 accounts).
- **Views first.** Judge conversion weekly, never per post.
- **Facts must be real.** Real dates, names, brands, quotes. If unsure, leave it out. Never invent pieces, quotes or prices.
- **Real pieces only** for outfit/fit content — give real product links (Google Shopping links are fine), menswear only, famous recognisable brands.
- **Images:** HMEDE makes them in ChatGPT from our prompts. Every set gets ONE locked scene description reused in every prompt (setting, light, camera, colour) so it looks shot on one iPhone. **Never** let ChatGPT render the app UI — app slides use real screenshots from `01-app/assets/`. ChatGPT changes logos on real products, so fit boards use real product photos, not regenerated ones.
- **Text lives in TikTok, not in the image.** Every prompt says "no text in image". Slide text is typed natively in TikTok.
- **5–10 slides. One idea per slide. Under 25 words per slide.** Every slide gives a reason to swipe.
- **Hooks about other people beat hooks about us.** Write 30 hooks, score them, keep the best.
- **Voice:** talks like a real person posting from their phone. Short, confident. Lowercase allowed on casual accounts.
- **App entry:** test the app entering on slide 3–4 in first person ("i asked this app to build it from my closet") with a real screenshot, vs the final-slide CTA. Log which wins.
- **Trends:** post within 24–48h or drop it. The bridge must feel natural — if forced, drop it. **Never** tragedies, deaths, politics.
- **Celebrities:** only clean, wearable, consistent style (a real signature across many looks). No costume/"weird" dressers (no Tyler, the Creator / A$AP Rocky / Playboi Carti types). Not one-good-outfit people.
- **Nothing gets posted without HMEDE's approval.**

## CTA (pre-launch, end of set)
BLOCK27 — an AI stylist for the clothes you already own. Join the waitlist — block27.app. You'll know the second it drops.
Caption ends: "👇 Waitlist in bio."

## Naming
Every set gets an ID: account letter + running number, never reused. block27.media = M (#M1, #M2…). BLOCK27SMOKE = S (#S1…). BLOCK27PEAK = P (#P1…). BLOCK27TRUTH = T (#T1…). BLOCK27NOBS = N (#N1…). Other accounts get their own letter when set.
SEASONS (HMEDE, 2026-10-27): work runs in seasons. Season 1 = Oct 24–27 (ends with HMEDE's report). Each report closes a season; next season starts when HMEDE says. Written 'SZN 1', 'SZN 2' (not 'S', which is SMOKE). Set IDs restart at #1 each season; log as SZN2-N1 etc.
Numbering restarted Oct 24, 2026: every account starts at #1. Pre-restart sets in 04-sets/_archive-pre-restart/.
SZN 2+ sets live in 04-sets/SZN2/<ID>/.
Folder: `04-sets/<ID>/` e.g. `04-sets/M1/`. First line of set.md: `# #<ID>` — the set is called by its ID only. HMEDE reports results by ID; log by ID in performance.csv.
