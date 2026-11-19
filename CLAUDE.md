# Savanna Morris — Portfolio: Project Memory

Personal portfolio site for Savanna Morris (GTM, Growth & AI Systems).
Read this before editing. Keep it updated when facts change.

## How the site works
- Single page: `index.html` (inline CSS + JS, no build step). Assets sit at the repo root.
- Hosted on **GitHub Pages from `main`**: https://smore-netizen.github.io/Savanna-Morris-Tech-Portfolio/
- Merging to `main` triggers the "pages build and deployment" workflow (~1 min). The live site can
  serve a cached copy for ~10 min; tell Savanna to hard refresh (Cmd+Shift+R) or use a private window.
- Workflow: edit on a branch → PR → merge to `main`. Savanna has approved direct merges when she asks.

## Editing conventions
- Check every visual change with Playwright screenshots at **1280px and 390px** widths; no horizontal scroll.
- **Keep card grids balanced — no empty grey cells.** Grids: `.rn-grid` (3 cols; `#right-now` is 2×2),
  `#builds .samples-grid` (2 cols), `.lead-grid` (Leadership & Character, currently 6 cards).
  If adding/removing a card leaves a gap, rebalance (add a card, or change the column count).
- Copy style: plain, specific, results-first. Don't invent numbers; ask Savanna for real metrics.
- Never publish internal/confidential employer details (internal event names, compensation or bonus timing).
- This repo is public: keep this file free of anything private.
- Don't put her email or other private contact details anywhere new. Calendly link already on the site is fine.
- Images: compress to ~1200px wide JPG (`convert ... -resize 1200x -strip -quality 80`).
  iPhone HEIC files with depth data don't convert here; ask for JPG.

## Key facts (as of November 2026)

### Sparrow — RuthAI & Google AI for Social Good Hackathon (Nov 13, 2026)
- **Sparrow is the product/business. Finch is Sparrow's AI agent (a bird). Don't mix these up.**
- Google office, Playa Vista. ~50 selected from 400+ applicants; 1,000+ applied for the reception.
- **2nd place out of 11 teams (11 total, including hers).** 6 hours to build MVP + deck + pitch.
- Judges (creators; names are their Instagram handles, do NOT link): CatGPT, Zoey Unlimited, Chantel Jeffries.
- Media interviewed/photographed the team.
- **Savanna's role:** frontend, UI/UX for platform and landing page, the pitch, and all branding
  (company name, logo, font, color palette, escape button, privacy acknowledgements).
- Product: helps women going through divorce find resources and get financially organized.
  Finch = long-running Gemini case agent with private memory; "tweets" tips every 30s; cited case wiki,
  what's-missing checks, five-year projection, lawyer prep brief. Finance dashboard (finds hidden assets),
  personalized onboarding by relationship status, pdf-lib court forms, divorce checklist with progress bar,
  Google Maps lawyer locator (directions, search, call in-app). Firebase Auth/Firestore/Storage.
- Stack: React 18 + Vite, Tailwind, Lucide, React Router v7, Node/Express, TypeScript, Multer, pdf-lib,
  Google Maps API, Gemini Flash, Google AI Studio, NotebookLM, Google Flow, Antigravity IDE.
- Roadmap: language translation; financial education for women in any relationship status.
- Repo `github.com/dzymachine/ruthAI` is **private** (she's a collaborator). Add a "View the code"
  button only once it's public. Team plans to deploy soon.
- Photos: `finch-team.jpg` (on stage), `finch-reception.jpg` (reception). Professional photos coming.
- Site: first card in Builds, case study `#cs-sparrow`, top stat, marquee line.

### TapIn — her own company (NOT Vibes)
- Founder. Consumer career platform. Selected for the **inaugural cohort of the Waves Innovation
  Accelerator — one of 10 startups chosen from 100+ applicants**.
- Validating demand via customer interviews with college seniors; testing core mechanic with an
  AI-assisted workflow. Site: venture block under Vibes + Right Now card.

### Vibes — Founding Chief Growth Officer
- Real-time atmosphere map (find restaurants/bars/cafés by how a place feels). Sole growth officer.
- **Still in beta**; currently planning/strategizing the business model ahead of LA launch.

### AI & Your Career Workshop Series (Pepperdine Career Center)
- 3 sessions she designed and teaches; supported by the Career Center.
- Session 1 (Nov 4): AI fluency + building a personal AI assistant (cover letters in your voice,
  resume tailoring, networking messages, skill-gap learning projects). **5 students.**
- Session 2 (Nov 11): prompt structuring, tokenization, which LLM for which task. **5 students.**
- Session 3: Dec 2, 2:30–3:30 p.m., CCB 341. Update attendance/feedback afterward.
- Site links `AI_Career_Selected_Slides.pdf` (8 selected slides) + "Request the full curriculum" → Calendly.
  Line: "Available to bring this series to your campus or team." She wants to take it to other universities.
- Attendance is small; frame as small hands-on groups rather than headline the count.

### Service Leadership Capstone (Team Lead, 5-person team, LA community nonprofit)
Deliverables in progress: Google Sheets outreach tracker (grants, donations, fundraising events);
email/print PR packet (outreach email templates w/ body, subject lines, signatures, branding;
mailable flyers; gala materials; donor & volunteer thank-you notes); outreach calendar with weekend
volunteer events; sign-in table/ID recommendations; job postings (Executive Director, unpaid internships).
Don't name teammates on the site.

### Student Programming Board
- Harry Potter-themed late-night event (Nov 7, 2026): $15,000 budget, 390+ attendees; negotiated vendor
  pricing, coordinated logistics, delegated roles, adapted through 30 mph winds.
- Still co-managing a major annual event (13% of Campus Life budget) — ask for results when done.

### Cloudera — Acting Co-Lead, Internal Communications (Oct 2026 – Feb 2027)
- Site version condensed to 4 bullets (five launches, newsletters/templates, Cloudera Conversations,
  EVOLVE reporting + partner spotlights + impact report). Wanted: a real metric (e.g., open rates).

### Other
- Paid guest speaker (sermons) at Woodland Hills Christian Church — twice. In Leadership & Character.

## Open items / ask Savanna about
- Session 3 attendance + student quotes; Career Center testimonial.
- ruthAI repo going public → add code/live link. App screenshot to replace team photo on Builds card.
- Professional hackathon photos.
- Cloudera acting co-lead metrics; Vibes beta/business-model milestones; capstone final outcome.
- Resume: `Savanna_Morris_Resume.pdf` (1 page, Nov 2026; made from her Word file with LibreOffice,
  LinkedIn/GitHub/Portfolio links added). It calls TapIn "Stealth Startup". Linked from the Download Resume button.
