---
name: daily-pack
description: Build today's posting pack for all 5 TikTok slideshow accounts — one set per slot with slide text, ChatGPT prompts, real piece links, caption.
---
1. Read CLAUDE.md, 01-app/app-brief.md, 01-app/accounts.md, 07-results/winners.md, 07-results/failure-log.md, today's 02-research/trends file (run trend-scan first if missing), and the format file for each account.
2. For each slot in accounts.md, pick the angle: a trend bridge if a natural one exists, otherwise the account's evergreen format.
3. Write 30 hooks per set, score them, keep the best one. Hooks about other people > hooks about us.
4. Write `04-sets/YYYY-MM-DD-account-slug/set.md` with:
   - Account + time
   - Hook + skeleton used
   - Slides: slide number, text to type in TikTok (<25 words), image to use
   - Locked scene description + one ChatGPT prompt per generated image (copy-paste ready, "no text in image")
   - Real piece links (plain list) / exact image URLs for celebrity slides
   - Where the app enters (real screenshot from 01-app/assets/) or end CTA
   - Caption + sound suggestion
   - Sources for every fact
5. Write `06-queue/YYYY-MM-DD.md`: posting order, times, set paths, status "awaiting approval".
6. Reply to HMEDE with a SHORT summary: one line per account. Full content lives in the files; paste a set in chat only when he asks.
