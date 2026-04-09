# Share — VKZ Proposal

_Internal reference. Updated 2026-04-08 after concept call #2._

---

## 3D Approach — DECIDED: Real-time WebGL (Option B)

The decision was made on the Apr 2 concept call. Jose was direct: *"if we have a website that doesn't load we're cooked because it's literally what we do, it's internet."*

**Option A — Pre-rendered 3D Video (PNG sequence on scroll)** — NOT chosen.
- Cinematic 3D environment rendered as video, converted to image sequence playing frame-by-frame on scroll.
- Examples: terminal-industries.com, getnauta.com.
- Pros: Highest visual fidelity, smooth performance, faster dev cycle.
- Cons: Not interactive, less wow, **30+ MB page weight** (target is 2–3 MB), particles don't work well, breaks on slow connections.

**Option B — Real-time 3D environment (WebGL / Three.js)** — **CHOSEN.**
- Interactive 3D scene in browser (same tech VKZ uses on Lightweight).
- Examples: lightweight.info, 8bit.ai, blueyard.com, vkz.studio.
- Pros: Truly immersive/interactive, reactive elements, stronger impression on investors/partners, **loads efficiently on slow networks and mobile** — critical for Share's African audience.
- Cons: Heavier dev time, performance optimization needed, lower asset detail vs pre-rendered.
- Cost delta: ~$5–10K more than PNG sequence.

---

## Site Structure — 4 pages

Confirmed on Apr 6 after the concept call (Suppliers added by Jose in Slack):

1. **Home** — most immersive. Coordination-layer hero, scroll narrative (problem → solution → vision), credibility section, two CTAs.
2. **Suppliers / Infrastructure** — supply side of the marketplace. Pitches data centers, tower companies, subsea cable providers on monetizing underutilized capacity through Share. Less animation-heavy, reuses 3D elements from homepage for consistency.
3. **For ISPs** — demand side. Hero + 3 sections covering unlimited bandwidth on revenue share, cross-connect anywhere, integrate-with-existing-systems messaging.
4. **Users** — find a Share-connected ISP, understand what Share-network internet means.

**Optional / phaseable additions (proposed by VKZ on the Apr 2 call):**
- **Contact page with form** — currently CTAs link to external surveys; a form gives flexibility to bring leads onto the site later.
- **About / founders** — Thao noted Share's IG personalities are strong content; case for highlighting founders even though Share defaults to using "Share" as a single pseudonym for team.
- **Case studies** — testimonials and onboarding stories from existing ISP partners.
- **Blog / press releases** — only worth building if Share commits to ≥1 article per month. Otherwise it's not worth the build cost. Hourly estimate is locked, so it can be added in 6 months without re-quoting.

---

## Budget — $32–35K total (real-time rendering)

Down from VKZ's original $35–40K range — Thao adjusted because pages turned out less lengthy than originally scoped.

**Breakdown structure:**
- Project setup + shared components (buttons, text styles, things used everywhere)
- Big chunk for the homepage animation
- **~60–70% of budget is sections / pages** — modular, broken down so Share can prioritize what to ship now vs. defer
- Connections (email/newsletter integration, etc.)

**Itemized breakdown spreadsheet:** sent to Share on 2026-04-08. Link in `memory/reference_project_assets.md`.

---

## CMS & Editing

- All text and images outside the 3D homepage experience are connected to a CMS (Sanity).
- Share can edit copy, add/remove/reorder sections, and publish blog posts themselves.
- Blog posts editable in a simple inline editor — described as a *"miniaturized Google Docs."*
- Content types in the Resources section: archive page + template per type (article, press release, case study).

---

## Maintenance & Yearly Fee

- VKZ charges a yearly maintenance fee covering: tech updates, package updates, bug fixes, server management, uptime monitoring.
- New features or pages open a new scope (not bundled into the maintenance fee).
- Form builder system included in the initial scope so Share has the option to bring forms onto the website later.

---

## Tech Stack

- **Frontend:** React/Next.js
- **3D:** Three.js / WebGL (real-time)
- **CMS:** Sanity (headless, built-in image optimization)
- **Hosting:** Vercel

All confirmed by Share — their existing webapp is also React/Next.js on Vercel.

---

## Workflow

1. Moodboard & Creative Direction
2. Concept & Storytelling
3. 3D Scene Development
4. Homepage Design
5. Supplier / ISP / User pages design
6. Subpages Design + Parallel Development
7. QA & Optimization

---

## Timeline

3 months from engagement to launch, parallel design-development approach. Target window: May 2026 PR moments.
