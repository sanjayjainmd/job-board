# Job Board

The published front end for [job-search-bot](https://github.com/sanjayjainmd/job-search-bot): a single-page board that lists the finance roles the bot finds at AI-infrastructure startups.

- Jobs are grouped and scored by the bot, then written into this page as static HTML
- Each posting can be marked **New**, **Seen**, **Applied** or **Dismissed**
- Marks are saved through a small Vercel API, so they stay in sync across a phone and laptops
- Served with GitHub Pages; no build step

The bot regenerates `index.html` and pushes it here automatically after each run.
