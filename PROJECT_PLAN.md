# Dive Feels Website — Project Plan

> Living checklist. Tick `[x]` when done. Add notes inline under a task as `> note: …` if useful.
> Companion docs in this folder:
> - `Dive Feels Website - Integrated Requirements.docx` — scope, sitemap, SEO/conversion spec, 24 discussion points
> - `Dive Feels Website.docx` — original requirement (source of truth for course copy)

## Strategic Goals

- **Primary**: Generate organic SEO traffic that converts into course enrollments (Open Water, Advanced, Nitrox, etc.)
- **Secondary**: Use Trips section for inspiration only; route inquiries to LINE OA / Facebook
- **Constraint**: Minimize ongoing content maintenance — no live trip schedules / prices on the website

## Milestones

- [ ] **M1** — Kickoff meeting complete (end of Phase 1)
- [ ] **M2** — Requirements signed off (end of Phase 2)
- [ ] **M3** — Design signed off (end of Phase 3)
- [ ] **M4** — Staging build complete + UAT passed (end of Phase 4)
- [ ] **M5** — Site live on production domain (end of Phase 5)
- [ ] **M6** — First 10 organic search clicks recorded (~4–8 weeks post-launch)

---

## Phase 1 — Draft / Pre-project (~7 days)

Goal: answer "why we're building this + who decides + where we start" before formal requirements.

- [ ] **1.1 Define business goals & KPIs** — # students/month, # leads/month, conversion target, top 3 keywords to rank for. Must be measurable in GA4.
- [ ] **1.2 Identify stakeholders & decision-makers** — who approves content / design / budget / launch. Build RACI.
- [ ] **1.3 Audit existing digital assets** — Facebook, LINE OA, Google Business Profile, IG, existing photos/videos, customer database.
- [x] **1.4 Define target audience personas** — 2–3 personas (e.g. beginner wanting OW, certified diver wanting AOW, international tourist). Affects tone, language, design.
  > note: **BUSINESS MODEL:** Theory + pool training in Bangkok. Open water checkout dives in Pattaya. No need to travel to Koh Tao. This is the #1 USP — convenience for Bangkok people.
  > note: **Primary market: Thai divers (Bangkok-based) first, foreigners secondary.**
  > note: **Persona 1 — "The Curious Starter"** Age ~28, Bangkok office worker, heard about scuba from a colleague. Never dived. Googling "เรียนดำน้ำ กรุงเทพ". Key USP: can learn without going to an island — evenings/weekends in Bangkok + one Pattaya weekend for checkout. Entry point: Open Water course.
  > note: **Persona 2 — "The Improver"** Bangkok-based, certified (OW or AOW), ~10 dives. Wants better technique — trim, buoyancy, navigation, Nitrox. Can train in Bangkok pool then do dives in Pattaya. Entry point: Specialty / technique courses.
  > note: **Persona 3 — "The Trip Seeker"** Certified diver wanting to join a curated live-aboard trip. ~15 trips/year; no booking on website — all inquiry → LINE / Facebook. May be lapsed → upsell: pool refresh session at special rate before the trip. Entry point: Trips/Destinations page → LINE OA.
  > note: **Persona 4 — "The Future Divemaster"** Passionate diver wanting DM/Instructor track. Community-driven school fits perfectly. Confirm if DM training location available.
  > note: **Persona 5 — "The Conservation Diver"** Certified diver motivated by social/environmental impact. Activities: Ocean Cleanup Projects, Marine Life Guidelines, Blue Ocean Program. Community-driven → strong organic sharing. Entry: Conservation Events page → LINE OA sign-up. Also strong SEO + brand reputation signal.
  > note: **Persona (old 5, REMOVED) — "The Koh Tao Tourist"** — not applicable. Dive Feels does NOT operate on Koh Tao.
- [ ] **1.5 Draft initial sitemap** — start from Integrated Requirements doc; adjust to personas.
- [ ] **1.6 Reference site research** — analyze 5 dive school sites (Crystal Dive, Big Blue, Roctopus, Koh Tao Divers + 1 international). Structure, CTA, pricing display, blog cadence.
- [ ] **1.7 Initial budget estimate** — design, dev, content, photography, hosting, ongoing/year. Range is fine at this stage.
- [ ] **1.8 Initial timeline estimate** — launch target date, per-phase duration, known blockers.
- [ ] **1.9 Vendor / team identification** — designer, developer, copywriter, photographer, SEO. Internal vs outsource.
- [ ] **1.10 Kickoff meeting** — all stakeholders + plan Phase 2. → **M1**

---

## Phase 2 — Confirm Requirements (~10 days)

Goal: lock scope. Changes after this phase have cost.

- [ ] **2.1 Review Integrated Requirements doc** — walk through every section with requirement owner. Use [เดิม/ปรับ/ใหม่] markers.
- [ ] **2.2 Answer 24 discussion points** — section 9 of Integrated doc. Blocks everything if not done.
- [ ] **2.3 Finalize sitemap** — lock page structure, URL slugs, menu, footer. Hard to change after this.
- [ ] **2.4 Course master list with prices** — spreadsheet: name, price, duration, included, excluded, location, prereq, photo refs. Content source for Phase 4.
- [ ] **2.5 Trip strategy confirmation** — confirm: no price/schedule, experience-only, CTA → LINE/FB. Lock.
  > note: **~15 live-aboard trips/year.** No booking or schedule on the website. All inquiry → LINE OA / Facebook. Trips section = inspiration + teaser only. Route conversions to social.
- [ ] **2.6 Language strategy** — TH only / TH+EN at launch / TH first then EN. Affects dev effort 30–50%.
- [ ] **2.7 CMS selection** — WordPress / Webflow / Next.js+headless / Wix. Lock immediately after choosing.
- [ ] **2.8 Domain & hosting decision** — register/confirm domain, choose hosting plan.
- [ ] **2.9 Content audit & gap list** — what exists in Integrated doc vs what's missing (Maldives, Hin Pherng, missing Specialty pages).
- [ ] **2.10 Plan content creation** — assign writers for missing content; schedule photo/video shoot if needed. Can run parallel with Phase 3.
- [ ] **2.11 Budget finalization** — based on CMS/hosting + team + real scope.
- [ ] **2.12 Scope of Work (SOW) sign-off** — single doc with all decisions + scope + timeline + budget + signature. → **M2**

---

## Phase 3 — CI & Design (~21 days)

Goal: brand assets + wireframes + hi-fi mockups + design system. Sign-off before dev.

- [x] **3.1 Brand discovery workshop** — mood, values, tone of voice, brand personality. 1-day session with owner.
  > note: Mood — Professional & trusted + Warm & community. Tone: "We're SSI certified and genuinely excited to teach you." Keywords: Certified, Calm, Trusted, Friendly, Approachable.
- [ ] **3.2 Logo audit / refresh / new** — vector + all lockups (horizontal, vertical, mark).
  > note: Existing script logo (white on black) confirmed in use. Vector source file still needed.
- [x] **3.3 Color palette** — primary + secondary + accent + neutral. Test WCAG AA contrast.
  > note: Final palette locked — Deep Navy #1C2B3A (nav/headings), Ocean Navy #2E4A6A (hero/sections), Ocean Teal #5BA8B8 (badges/links/accents), SSI Red #E31837 (CTA only), Warm Coral #FF9B7A (warm accent), Warm White #FFF6F0 (page bg). Saved to design-tokens.css.
- [x] **3.4 Typography** — Thai-supporting fonts (Sarabun / Prompt / IBM Plex Thai). Heading + body + caption.
  > note: Heading — Prompt, Body — Sarabun, Mono — IBM Plex Mono. Defined in design-tokens.css. Final pairing to confirm once rendered on screen.
- [ ] **3.5 Photography style guide** — tone (warm/cool), aspect ratio, treatment, do/don't. Brief for photographer.
  > note: Mood board direction established — warm, sunlit, natural ocean. Full written brief still needed.
- [ ] **3.6 Icon set** — line or filled family aligned to brand. Open-source is OK (Phosphor / Lucide).
- [x] **3.7 Wireframes (low fidelity)** — Home, Course landing, Destination, Trip (simplified), Contact, Blog list, Blog post, FAQ, About. Mobile + desktop.
  > note: Home page wireframe complete — wireframe-home.html. Desktop + mobile. 12 sections: nav, hero, how-it-works, trust strip, courses (4 cards), LINE CTA, destinations, instructors, reviews, blog teaser, final CTA, footer. Pending: Course landing, Destination, Trip, Contact, Blog, FAQ, About pages.
- [ ] **3.8 Wireframe review** — walk through with Owner + PM + Dev. Get feedback before hi-fi.
- [ ] **3.9 Hi-fi mockup: Home** — mobile + desktop, all states (hover, sticky CTA, etc.).
- [ ] **3.10 Hi-fi mockup: Course landing template** — single template reused for every course. Critical for conversion.
- [ ] **3.11 Hi-fi mockup: Destination + Trip** — Destination = inspiration heavy; Trip = simplified spec.
- [ ] **3.12 Hi-fi mockup: Contact + About + Instructor bio** — map embed + LINE QR + form + team grid + bio detail.
- [ ] **3.13 Hi-fi mockup: Blog list + Blog post + FAQ** — Blog UX readable; FAQ accordion compatible with FAQPage schema.
- [ ] **3.14 Design system / component library** — tokens (color/type/spacing), components (button, card, form, modal), states. Speeds up dev a lot.
  > note: Color + typography + spacing tokens done (design-tokens.css). Components (button, card, form, modal) still to be built.
- [ ] **3.15 Mobile responsive review** — check every mockup at 360 / 768 / 1280 / 1920px. Mobile-first.
- [ ] **3.16 Design review iteration** — 1–2 rounds of feedback + fix.
- [ ] **3.17 Design sign-off** — Owner signs final design package. → **M3**

---

## Phase 4 — Development + Testing (~45 days)

Goal: working site on staging, all functional + non-functional tests pass.

### 4A. Environment & CMS Setup

- [ ] **4.1 Dev environment setup** — local dev + Git repo + basic CI.
- [ ] **4.2 Staging environment setup** — staging subdomain + SSL + basic auth. **Block indexing from Google.**
- [ ] **4.3 CMS install & configure** — install, blank theme, roles (admin/editor), backup plugin.

### 4B. Frontend Templates

- [ ] **4.4 Global layout** — sticky header, responsive menu, footer with NAP + social + sitemap link.
- [ ] **4.5 Template: Home page** — from hi-fi mockup. Dynamic sections: Featured Courses, Reviews, Trust strip.
- [ ] **4.6 Template: Course landing page** — reusable template + course meta fields (price, duration, inclusions). SEO-heavy.
- [ ] **4.7 Template: Destination page** — destination template + photo gallery component.
- [ ] **4.8 Template: Trip page (simplified)** — hero + story + gallery + CTA only.
- [ ] **4.9 Template: Contact + About + Instructor bio** — contact form, Google Maps, LINE QR, team grid, bio detail.
- [ ] **4.10 Template: Blog list + Blog post** — pagination, category filter, related posts, social share.
- [ ] **4.11 Template: FAQ + Legal pages** — FAQ accordion (FAQPage schema), Privacy, Terms, Cancellation, Cookie banner.

### 4C. SEO Implementation

- [ ] **4.12 SEO module install + config** — Yoast/RankMath (WP). Meta titles, descriptions, OG tags, breadcrumbs.
- [ ] **4.13 Schema markup** — Course, Product, Offer, FAQPage, LocalBusiness, Review, VideoObject. Validate with Rich Results Test.
- [ ] **4.14 Sitemap.xml + robots.txt + canonical** — auto-generated, canonical on every page.
- [ ] **4.15 Multi-language setup (if applicable)** — subfolder `/en/` + hreflang + language switcher. Skip if TH-only.

### 4D. Integrations

- [ ] **4.16 Google Analytics 4** — install + conversion events (form submit, LINE click, phone click).
- [ ] **4.17 Google Tag Manager** — container + custom events.
- [ ] **4.18 Google Search Console** — verify (submit sitemap in Phase 5).
- [ ] **4.19 LINE chat widget + Messenger button** — sticky on every page. Conversion critical.
- [ ] **4.20 Google Maps embed** — Contact page pin.
- [ ] **4.21 Google Reviews widget** — auto-pull from GBP. Show on Home + Course pages. **Real reviews only.**
- [ ] **4.22 Lead capture form** — name, phone, course interest → email + LINE Notify. PDPA-compliant.

### 4E. Content Loading

- [ ] **4.23 Content loading: courses** — load every course (text + images + meta) per master sheet 2.4.
- [ ] **4.24 Content loading: destinations + trips** — destination text + photos; simplified trip pages.
- [ ] **4.25 Content loading: About, FAQ, Legal** — team bios, FAQ Q&A, Privacy/Terms (PDPA-adjusted template).
- [ ] **4.26 Image optimization pipeline** — auto WebP/AVIF + responsive srcset + lazy load. Page-speed factor.

### 4F. Functional Testing

- [ ] **4.27 F-Test: Navigation + links** — every menu, internal link, footer link, breadcrumb. No 404s.
- [ ] **4.28 F-Test: Forms** — lead form, contact form, newsletter (if any). Submit, validate, error handling.
- [ ] **4.29 F-Test: CTAs (LINE/FB/phone)** — every button hits the right destination and fires its tracking event.
- [ ] **4.30 F-Test: CMS edit reflects on frontend** — owner edits 3 pages → verify changes appear. Doubles as owner training.
- [ ] **4.31 F-Test: Schema markup validation** — run every page through Rich Results Test + Schema.org validator.
- [ ] **4.32 F-Test: Multi-language switch (if applicable)** — switcher + hreflang + content matching. Skip if TH-only.

### 4G. Non-Functional Testing

- [ ] **4.33 NF-Test: Performance (Lighthouse)** — ≥90 mobile + desktop on Performance, SEO, Accessibility, Best Practices.
- [ ] **4.34 NF-Test: Core Web Vitals** — LCP <2.5s, INP <200ms, CLS <0.1 on real pages (PageSpeed Insights). Google ranking factor.
- [ ] **4.35 NF-Test: Accessibility (WCAG AA basics)** — alt text, contrast, keyboard nav, ARIA labels, focus states.
- [ ] **4.36 NF-Test: Security** — HTTPS, security headers (CSP, HSTS, X-Frame), no exposed secrets, XSS/CSRF basics.
- [ ] **4.37 NF-Test: SEO audit** — meta tags every page, internal linking, image alt, broken links. Screaming Frog scan.
- [ ] **4.38 NF-Test: Cross-browser** — Chrome, Safari, Edge, Firefox. Visual + functional.
- [ ] **4.39 NF-Test: Mobile devices** — actual iOS Safari + Android Chrome, not just emulator.
- [ ] **4.40 NF-Test: PDPA compliance** — cookie banner works, privacy policy complete, form consent present.

### 4H. UAT

- [ ] **4.41 UAT round 1** — Owner + team use the site for 3–5 days. Collect bug list.
- [ ] **4.42 Bug fix iteration** — dev fixes UAT bugs.
- [ ] **4.43 UAT round 2 + final sign-off** — Owner signs everything is launch-ready. → **M4**

---

## Phase 5 — Deployment (~7 days)

Goal: live on production, submitted to search engines, owner trained.

- [ ] **5.1 Pre-launch checklist review** — go/no-go meeting. Review tests + content + integrations.
- [ ] **5.2 Final content QA** — proofread every page. Typos, broken images, missing alt.
- [ ] **5.3 Production environment setup** — production hosting + CDN.
- [ ] **5.4 DNS configuration** — update A/CNAME at registrar → production. Propagation 24–48h.
- [ ] **5.5 SSL certificate** — Let's Encrypt or paid cert. Force HTTPS, redirect www↔non-www.
- [ ] **5.6 Production deployment** — staging → production + smoke test.
- [ ] **5.7 Verify production site** — every page, form, CTA, tracking event works on production.
- [ ] **5.8 Submit XML sitemap to Google Search Console** — and monitor coverage report.
- [ ] **5.9 Submit to Bing Webmaster Tools** — verify + submit sitemap.
- [ ] **5.10 Update Google Business Profile** — link new site + update services + post update.
- [ ] **5.11 Update social channels** — Facebook, IG, LINE OA bio + new link.
- [ ] **5.12 Backup + disaster recovery setup** — auto-backup daily + test restore once.
- [ ] **5.13 Documentation handover** — CMS guide for owner (edit course, add blog, update FAQ). Doc + video.
- [ ] **5.14 Owner training** — 1-on-1, 1–2 hours.
- [ ] **5.15 Launch announcement** — soft launch (LINE OA broadcast, FB post) → monitor 48h → hard launch. → **M5**
- [ ] **5.16 Post-launch monitoring (48h)** — errors, GA4 traffic, form submissions, GBP/SC indexing. Hot-fix ready.
- [ ] **5.17 Launch retrospective** — what went well / what to improve / lessons for ongoing.

---

## Phase 6 — Post-Launch / Ongoing

Goal: ongoing SEO, content, maintenance. This is not a one-shot.

- [ ] **6.1 Weekly: GA4 + Search Console review** — traffic, top pages, top queries, CTR, errors. ~1h/week.
- [ ] **6.2 Bi-weekly: LINE/FB lead quality review** — real leads vs spam, conversion ratio to actual enrollments.
- [ ] **6.3 Monthly: Blog content (2–4 posts)** — per cluster strategy. Feeds SEO + internal links to courses.
- [ ] **6.4 Monthly: Google Business Profile update** — post update, answer Q&A, respond to reviews, update photos.
- [ ] **6.5 Monthly: Course content refresh** — verify prices/schedule current; refresh photos.
- [ ] **6.6 Quarterly: SEO audit** — rank tracking, broken links, schema check, content gap.
- [ ] **6.7 Quarterly: Backup restore test** — actually restore from backup to verify.
- [ ] **6.8 Quarterly: Reviews collection campaign** — ask new students for Google reviews + photo shares. Target +10/quarter.
- [ ] **6.9 Annually: CMS + security updates** — core + plugins + theme + security patches.
- [ ] **6.10 Annually: Photo/video refresh** — keep content fresh, brand alive.
- [ ] **6.11 Annually: KPI review vs goals** — compare to KPIs in 1.1. Adjust next year's strategy. → **M6**

---

## Risks & Dependencies

Review weekly during build.

### Risks

- [ ] **R1** Content (prices, real photos) not ready by Phase 4 — *Mitigation:* start collecting in Phase 2 (2.4, 2.9); use placeholders if needed.
- [ ] **R2** Photo assets missing / no rights — *Mitigation:* asset audit in 1.3; budget for photoshoot in 1.7.
- [ ] **R3** Scope creep — trip schedule/price requested later — *Mitigation:* lock spec in 2.5; sign-off scope in 2.12; change-request process.
- [ ] **R4** Wrong CMS choice → migration cost — *Mitigation:* detailed trade-off in 2.7; consult dev.
- [ ] **R5** PDPA compliance gaps — *Mitigation:* PDPA-compliant template + 4.40 + legal consult.
- [ ] **R6** SEO results slow (Google indexing 3–6 months) — *Mitigation:* set expectation in 1.1; consider short-term Google Ads as bridge.
- [ ] **R7** Stakeholder decisions slow → block Phase 2 — *Mitigation:* schedule decision meetings early; decision log in 2.2; SLA 5 days/decision.
- [ ] **R8** Designer/dev capacity short — *Mitigation:* identify in 1.9; have backup vendor list.

### Dependencies

- [ ] **D1** Domain registration (handle in 2.8 — can do immediately after decision).
- [ ] **D2** Google Business Profile verified (start in Phase 1 — verification may take 1–2 weeks).
- [ ] **D3** LINE OA + Facebook page active (must be ready before Phase 5).
- [ ] **D4** Course pricing decisions (blocks Phase 3 + 4 — push in 2.4).
- [ ] **D5** Photo/video assets (blocks 4.23–4.26 — schedule shoot in 2.10).
- [ ] **D6** Owner availability for UAT + training (blocks 4.41 + 5.14 — schedule 2 weeks ahead).
