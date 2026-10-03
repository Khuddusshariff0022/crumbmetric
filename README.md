# CrumbMetric — kitchen conversion tools site

A static site (no backend, no build step) with 6 baking/kitchen calculators:
recipe scaler, oven temperature converter, butter converter, cup-to-grams
converter, yeast converter, pan size converter. Monetization plan: display
ads (Google AdSense) once the site has traffic.

## Why this model
- No content treadmill — tools work forever once built, unlike a blog.
- Pure client-side JS — nothing to host, patch, or keep alive.
- Each tool targets a specific long-tail search ("how many grams in a stick
  of butter") with low competition compared to big recipe sites.

## What's done
- [x] Homepage + 6 working, tested calculators (`index.html`, `tools/*.html`)
- [x] SEO basics: meta descriptions, canonical tags, `sitemap.xml`, `robots.txt`
- [x] Git repo initialized locally with the first commit

## What you need to do (one-time, ~15–20 min total)

I can't create accounts or enter payment info on your behalf — these are the
only manual steps:

1. **Pick and register a domain** (~$10–15/yr, fits your <$20 budget).
   Suggested names to check availability for: `crumbmetric.com` (what the
   site is already branded as), `bakeconvert.com`, `kitchenconvert.app`.
   Any registrar works (Namecheap, Porkbun, Google Domains successor, etc.)
   — if you pick a name other than crumbmetric, tell me and I'll do a
   find-and-replace across the site in two minutes.

2. **Create a free GitHub account** (if you don't have one) and a free
   **Vercel** account (sign in with GitHub, one click). Then:
   - Push this folder to a new GitHub repo (I can prep the remote-ready repo
     and give you the exact `git remote add` + `git push` commands — just
     say go).
   - Import that repo in Vercel → it deploys automatically. Point your
     domain's DNS at Vercel (Vercel's dashboard gives you the exact records).
   - From then on: every time I update files in this folder and you push,
     the live site updates automatically. No redeploying by hand.

3. **Later — once the site has some real traffic** (don't bother on day
   one; Google will reject it): apply at
   [google.com/adsense](https://www.google.com/adsense) with your domain.
   Approval takes a few days to a few weeks. Once approved, you paste one
   snippet of code into the site — I'll do that part, you just paste the
   AdSense account ID you're given.

## What I'll keep doing automatically
- Add new calculator tools over time (more long-tail keyword coverage =
  more traffic) — I can batch-generate these on a schedule if you want a
  recurring task set up for it.
- Keep `sitemap.xml` in sync as tools are added.
- Watch for broken conversions / bad math (flag anything that looks off).

## Honest expectations
This is a slow-burn, low-maintenance passive income project, not a
get-rich-quick scheme. Realistic timeline: weeks to months before Google
indexes and ranks the pages, and AdSense revenue depends entirely on
traffic volume (expect cents to a few dollars a day at modest traffic;
real money needs real traffic, which takes sustained SEO — more tools,
maybe some backlinks/Reddit/Pinterest mentions — over months).
