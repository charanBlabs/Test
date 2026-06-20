# BDGS V2.0 — Weekly Daily Checklist

> **Source:** `bdgs-v2-0-redesign-and-development-2026-06-13.md` (MoM Jun 13, 2026)  
> **Aligned with:** `docs/phases/phase-1-tasks.md`  
> **Schedule start:** Mon **Jun 22, 2026**  
> **Working days:** Mon–Sat · **Sunday = off**  
> **Tick:** ☐ not started · ◐ in progress · ☑ done

---

## Priority order (UPDATED)

1. **Week 1 — Homepage first** (MoM #1–4) · owner sign-off before hub build at scale  
2. **Week 2 — Hub pages** · master `/solutions/all-solutions` + 8 category hub static pages (shells + IA)  
3. **Weeks 3–4 — Phase 1 per hub** · inventory, migrate, QC **hub by hub** using [Google Sheet](https://docs.google.com/spreadsheets/d/1p7yHVqNYuNTR9H5ztLkP89GeZ9Xatv6kofmPwWIje8A/edit?usp=sharing)  
4. **Weeks 5+** · Tools hub, rolling service pages, buy-flow plan, PMP

**Rule:** Do **not** block homepage on Phase 1 lock. Phase 1 closes **after** hub pages exist, one hub at a time.

**Note:** MoM §12 “$100 credits” → **killed**. Use **Final CTA / Zoom Clinics**.

---

## How this maps to the MoM

| MoM track | Week |
|-----------|------|
| Actions #1–4 | **W1** Homepage sprint |
| Actions #7–9, #19 | **W2** Hub pages (design + static build) |
| Phase 1 + #5, #6, #10, #11, #18 | **W3–W4** Per-hub tools work |
| Action #12 | **W5** Tools hub & spoke |
| Actions #13–14, #20, #21, #23–25 | **W5–W6+** |
| Action #22 | **W6** v2.2 tools shortlist |

---

## Already completed (carry forward ☑)

| Item | Status |
|------|--------|
| Titan knowledge graph (`brainstroming_v1.md`) | ☑ |
| Claude archive trimmed | ☑ |
| Master inventory Google Sheet (tabs + Hub column) | ☑ |
| Solution post type in BD | ☑ |
| Slug `/solutions` + `/solutions/all-solutions` coexist | ☑ |
| Static page shell `/solutions/all-solutions` | ☑ |
| Post-type listing live (49 published) | ☑ |

**During W1:** Keep Solutions/Tools homepage blocks live daily · **MoM #2** ◐

---

## Week 1 — Homepage sprint v7 (Jun 22–27) · **FIRST PRIORITY**

**Goal:** MoM #1–4. Close sections 1–15. Responsive sign-off.

**Daily rule:** 3 sections/day · copy + images + icons + layout + **mobile + tablet + desktop**.

**Also daily (5 min):** Solutions/Tools CTAs still work · **MoM #2**

### Monday Jun 22 — Sections 1–3

- [x] **§1** Header / nav *(done 2026-06-20 via antigravity)*
- [x] **§2** Hero (copy, AI strip, CTAs) *(done 2026-06-20 via antigravity)*
- [x] **§3** Service tiles / stacking intro *(done 2026-06-20 via antigravity)*

### Tuesday Jun 23 — Sections 4–6

- [x] **§4** Hire Developer card *(done 2026-06-20 via antigravity)*
- [x] **§5** Why BDGS / pain cards *(done 2026-06-20 via antigravity)*
- [ ] **§6** Trust stats (500+ · 169+ reviews · 10+ yrs · 20+ devs)

### Wednesday Jun 24 — Sections 7–9

- [ ] **§7** Reviews / social proof → `/blabs-review`
- [ ] **§8** Setup card (3-tier)
- [ ] **§9** Customizations / Solutions card

### Thursday Jun 25 — Sections 10–12 + GIF pipeline

- [ ] **§10** Tools / A-la-carte promo
- [ ] **§11** Maintenance
- [ ] **§12** Final CTA / Zoom Clinics *(not $100 credits)*
- [ ] GIF placeholder→swap pipeline · **MoM #4**

### Friday Jun 26 — Sections 13–15 + sign-off

- [ ] **§13** Signup / inquiry modal
- [ ] **§14** FAQ (+ schema ready)
- [ ] **§15** Footer
- [ ] **Full-page responsive sign-off** · **MoM #1, #3**

### Saturday Jun 27 — Buffer

- [ ] Fix failed sections from review
- [ ] Owner walkthrough → homepage **locked**

**Sunday Jun 28 — OFF**

---

## Week 2 — Hub pages (Jun 29 – Jul 4)

**Goal:** Build hub **pages** only — no full Phase 1 migration yet. MoM #7, #8, #9 prep.

**8 hubs (locked):** seo · lead-gen · member-profiles · search · page-design · content · integrations · member-management

### Monday Jun 29 — Master hub + design

- [ ] All-solutions hub: 10 layout options → pick 1 · **MoM #7**
- [ ] Lock canonical URL: **`/solutions/all-solutions`**
- [ ] Publish master hub content (8 hub cards linking to category pages)

### Tuesday Jun 30 — Hub pages batch 1

- [ ] Static page: `/solutions/seo`
- [ ] Static page: `/solutions/lead-gen`
- [ ] Static page: `/solutions/member-profiles`
- [ ] Static page: `/solutions/search`
- [ ] Each page: hero + hub intro + placeholder card grid

### Wednesday Jul 1 — Hub pages batch 2

- [ ] Static page: `/solutions/page-design`
- [ ] Static page: `/solutions/content`
- [ ] Static page: `/solutions/integrations`
- [ ] Static page: `/solutions/member-management`

### Thursday Jul 2 — Hub IA + routes

- [ ] Route map: master hub → category hub → detail URL pattern
- [ ] Wire hub cards on master page → all 8 category URLs
- [ ] 301 redirect map (legacy `?category=` → static hubs) · **MoM #9** draft

### Friday Jul 3 — Hub QC + approval

- [ ] Test all 9 hub URLs (master + 8) on mobile/tablet/desktop
- [ ] Send hub pages to Yakin + Pranitha · **MoM #19**
- [ ] Implement first batch of 301 redirects

### Saturday Jul 4 — Buffer

- [ ] Fix hub feedback
- [ ] **Light page list pass** — start MoM #5 (names only, no deep Phase 1)

**Sunday Jul 5 — OFF**

**Done when:** All hub **pages** live with correct URLs and nav — cards can be placeholders until W3.

---

## Week 3 — Phase 1 · Hubs 1–4 (Jul 6–11)

**Goal:** Phase 1 work **per hub** — map sheet rows → hub page cards → migrate/QC published items only.

### Monday Jul 6 — Hub 1: SEO & Schema

- [ ] Sheet: all SEO hub rows verified (Hub column)
- [ ] `/solutions/seo` — populate cards from sheet (published only)
- [ ] QC pricing · sidebar · hero · forms (SEO hub items)
- [ ] Link spokes → live solution detail URLs

### Tuesday Jul 7 — Hub 2: Lead Generation & Conversion

- [ ] Sheet: lead-gen hub rows verified
- [ ] `/solutions/lead-gen` — populate cards
- [ ] QC lead-gen published items

### Wednesday Jul 8 — Hub 3: Member Profile Enhancement

- [ ] Sheet: member-profiles hub rows verified
- [ ] `/solutions/member-profiles` — populate cards
- [ ] QC member-profile published items

### Thursday Jul 9 — Hub 4: Search & Discovery

- [ ] Sheet: search hub rows verified
- [ ] `/solutions/search` — populate cards
- [ ] QC search hub published items

### Friday Jul 10 — Detail template + inventory

- [ ] Solution detail page UI lock · **MoM #10**
- [ ] Apply template to 2 pilots per hub (8 max)
- [ ] **Page inventory research pass** · **MoM #5**

### Saturday Jul 11 — Buffer

- [ ] Catch up open hub 1–4 items
- [ ] Recheck pilot copy · **MoM #11**

**Sunday Jul 12 — OFF**

---

## Week 4 — Phase 1 · Hubs 5–8 + lock (Jul 13–18)

**Goal:** Finish remaining hubs. Close Phase 1. Rolling service pages start.

### Monday Jul 13 — Hub 5: Page Design & Development

- [ ] `/solutions/page-design` — populate + QC published items

### Tuesday Jul 14 — Hub 6: Content & Engagement

- [ ] `/solutions/content` — populate + QC published items

### Wednesday Jul 15 — Hub 7: Integrations

- [ ] `/solutions/integrations` — populate + QC published items

### Thursday Jul 16 — Hub 8: Member Management & Automation

- [ ] `/solutions/member-management` — populate + QC published items
- [ ] Remaining 301 redirects live · **MoM #9**
- [ ] `ALL All Posts` tab = 123 rows · reconcile 7 gaps
- [ ] Delete list → owner decision

### Friday Jul 17 — Phase 1 exit

- [ ] Draft/pending publish pass (capture URLs, re-draft bad quality later)
- [ ] Charan + Yefim: lock master static-page list · **MoM #6, #18**
- [ ] Owner sign-off → **Phase 1 locked**
- [ ] **Rolling page 1:** `/setup`

### Saturday Jul 18 — Buffer + pages

- [ ] **Rolling pages 2–3:** `/hire-developer` · `/about`
- [ ] Performance pass on `/solutions` (slow load)

**Sunday Jul 19 — OFF**

---

## Week 5 — Tools hub + rolling pages (Jul 20–25)

**Goal:** MoM #12, #21, #13, #20.

### Monday Jul 20 — Tools IA

- [ ] Tools hub static page (mirror Solutions pattern)
- [ ] 301 map for legacy `/tools?` URLs

### Tuesday Jul 21 — Tools build

- [ ] Tools hub + category pages live
- [ ] 301 redirects batch 1

### Wednesday Jul 22 — Rolling pages

- [ ] `/contact` · `/zoom-clinics` · `/consultation` · `/maintenance`

### Thursday Jul 23 — Buy flow document

- [ ] End-to-end flow doc · **MoM #13**
- [ ] Dashboard V1 spec outline · **MoM #14**

### Friday Jul 24 — Buy flow + schedule

- [ ] Submit buy flow to Yakin + Pranitha · **MoM #20**
- [ ] Lock next 3–4 pages for W6 · **MoM #21**

### Saturday Jul 25 — Buffer

- [ ] Tool detail template aligned with Solutions

**Sunday Jul 26 — OFF**

---

## Week 6 — PMP + dashboard + v2.2 (Jul 27 – Aug 1)

**Goal:** MoM #16, #22, #23, #25 prep.

### Monday Jul 27 — PMP API plan · **MoM #23**

### Tuesday Jul 28 — Dashboard V1 start *(if buy flow approved)* · **MoM #16**

### Wednesday Jul 29 — Dashboard + 2 rolling pages

### Thursday Jul 30 — Dashboard V2 plan · **MoM #24**

### Friday Jul 31 — v2.2 tools shortlist (10 tools, lock first 2) · **MoM #22**

### Saturday Aug 1 — PMP rollout prep · Themes brief for Vikash · **MoM #17**

**Sunday Aug 2 — OFF**

---

## Hub → week map (Phase 1 per hub)

| Hub | Slug | Week | Sheet tab filter |
|-----|------|------|------------------|
| SEO & Schema | `/solutions/seo` | W3 Mon | Hub 1 |
| Lead Gen & Conversion | `/solutions/lead-gen` | W3 Tue | Hub 2 |
| Member Profiles | `/solutions/member-profiles` | W3 Wed | Hub 3 |
| Search & Discovery | `/solutions/search` | W3 Thu | Hub 4 |
| Page Design | `/solutions/page-design` | W4 Mon | Hub 5 |
| Content & Engagement | `/solutions/content` | W4 Tue | Hub 6 |
| Integrations | `/solutions/integrations` | W4 Wed | Hub 7 |
| Member Management | `/solutions/member-management` | W4 Thu | Hub 8 |

---

## Approval gates (updated order)

| Gate | Owner | When |
|------|-------|------|
| Homepage sign-off | Yakin | End **W1** |
| Hub pages (master + 8) | Yakin + Pranitha · **#19** | End **W2** |
| Phase 1 lock (all hubs populated) | Yakin | End **W4** |
| Buy-flow plan | Yakin + Pranitha · **#20** | **W5** |
| PMP rollout | Yakin | July · **#25** |

---

## MoM Action Board — master tick list

| # | Action | Week | ☐ |
|---|--------|------|---|
| 1 | Home sections 1–15 | **W1** | ☐ |
| 2 | Solutions & Tools blocks live | W1 daily | ◐ |
| 3 | Full-page responsive sign-off | W1 Fri | ☐ |
| 4 | GIF asset pipeline | W1 Thu | ☐ |
| 5 | Complete page list | W3 Fri | ☐ |
| 6 | Lock static-page list | W4 Fri | ☐ |
| 7 | Solutions hub & spoke design | **W2** | ◐ |
| 8 | Canonical Solutions URL | W2 Mon | ◐ |
| 9 | 301 Solutions category URLs | W2–W4 | ☐ |
| 10 | Solution detail page design | W3 Fri | ☐ |
| 11 | Recheck solution detail content | W3–W4 | ☐ |
| 12 | Tools hub & spoke + 301s | W5 | ☐ |
| 13 | Plan buy flow | W5 Thu | ☐ |
| 14 | Plan member dashboard | W5 Thu | ☐ |
| 15 | Themes E2E | Aug | ☐ |
| 16 | Unified dashboard V1 | W6 | ☐ |
| 17 | Vikash Themes support | W6 | ☐ |
| 18 | Master page inventory w/ Yefim | W4 Fri | ☐ |
| 19 | Approve Solutions hubs | W2 Fri | ☐ |
| 20 | Approve buy flow | W5 | ☐ |
| 21 | 3–4 pages/week rolling | W4+ | ☐ |
| 22 | v2.2 tools shortlist | W6 Fri | ☐ |
| 23 | PMP API plan | W6 | ☐ |
| 24 | Dashboard V2 plan → build | W6+ | ☐ |
| 25 | PMP rollout July | End Jul | ☐ |

---

## Quick daily standup (2 min)

1. What did I ☑ yesterday?
2. Homepage section **or** hub name today?
3. Owner approval block?
4. Solutions/Tools links still live?

---

*Sunday always off. Homepage W1 → Hub pages W2 → Phase 1 per hub W3–W4.*
