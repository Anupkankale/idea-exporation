 # IMET Worldwide  CRO Audit & 4-Step Plan (Home, DBA, MBA)

Oct 16, 2026 · @DevXpert

## Read this first

All three pages lose leads to trust contradictions, not to button colours. A senior IT buyer comparing a USD 8,500 doctorate will find four of them in under two minutes.

1. **Three different prices.** Cost block on Home and DBA: USD $8500. Home FAQ: USD 8,000. DBA FAQ: USD 7,000 to 10,000. The MBA page shows the *DBA* price under the heading "Doctorate (DBA) Program Cost".
2. **"We don't award any degrees"** appears on all three pages, which sell a degree, and none names the awarding university.
3. **Counters show zero.** DBA and MBA pages display "0+" enrolled, "0+" countries and "0%" completion — a lazy-load counter that never ran, read by visitors as "nobody".
4. **The MBA page is a copy of the DBA page.** DBA testimonials, DBA price, DBA certificate image and a "Talk to a Doctoral Advisor" button on a master's page.

No traffic or conversion numbers were supplied. So this plan says *what* changes and *what you can measure* after each step; it does not promise a % lift. Anyone who quotes you a lift before seeing your baseline is guessing.

| Item | Value |
| --- | --- |
| Pages | [Home](https://imetworldwide.com/), [Online DBA](https://imetworldwide.com/online-doctorate-business-administration-dba-programs/), [Online MBA](https://imetworldwide.com/online-masters-mba-degree-programs/) |
| Conversion goal | Advisor / mentoring form submit (assumed — the most prominent action on each page) |
| Read on | 16 Oct 2026, page text only (no screenshots, no analytics) |
| Evidence | Every finding below is quoted from the live pages unless marked Assumed |

## Site-wide issues (fix once, fixes all three pages)

These come from shared Elementor templates — header, footer, popups, forms — so one fix lands everywhere.

| # | Issue | Where seen | Why it costs leads | Team |
| --- | --- | --- | --- | --- |
| S1 | Price differs: $8,500 / $8,000 / $7,000–10,000 | Home, DBA, MBA | Buyer can't tell the real fee; inconsistency reads as untrustworthy | Content |
| S2 | "We don't award any degrees" in footer; no awarding university named | All three | The core question ("who signs my certificate?") is unanswered | Content + leadership |
| S3 | Refer & Earn image banner above the logo, no text | All three | First thing seen is an offer for existing customers, not the program | UI/UX |
| S4 | 4 different forms (5-field, 5-field, 3-field, 3-field) with different names: "Speak with a Program Advisor", "Book Your Free 1:1 Mentorship", "Book Free Mentorship Session" | All three | Visitor can't tell if these are one action or four | UI/UX + Dev |
| S5 | WhatsApp promotional opt-in checkbox on the long forms | All three | If pre-ticked, it's a consent problem, not a test (default state not visible — check) | Dev |
| S6 | Navigation repeated 3×, footer menus 2×, 14 country links 2× | All three | Page weight and screen-reader noise; SEO sees thin duplicate link blocks | Dev + SEO |
| S7 | Footer links wrong: "MBA in Supply Chain" → Data Analytics page; "Online MBA Programs" → Cybersecurity MBA; `/#accreditaion` typo | All three | Dead ends at the moment of intent | Dev |
| S8 | Three Google Tag Manager containers | Home (likely all) | Form submit may count 2–3×; any test result would be wrong | Analytics |
| S9 | Contact: one Dubai phone; other offices are area names only; no email | All three | High-ticket buyers look for a real address before paying | Content |
| S10 | Accreditation logos as images only ("Ministry of Education" — of which country?) | All three | Unverifiable logos are discounted, or read as borrowed authority | Content + UI/UX |

## Homepage, section by section

The homepage tries to be a brochure, a program catalogue and a lead form at once; it needs to do one job — get a qualified IT leader to book an advisor call.

### Hero section

| What's there | Issue | Fix | Team |
| --- | --- | --- | --- |
| H1 "Best Online Doctorate (DBA) & Master's (MBA) Programs"; eyebrow "Your No.1 Platform for Leadership Growth" | "Best" and "No.1" with no source; serves DBA and MBA at once, so speaks to neither | One audience in the hero (DBA — it's what the page is built around); move MBA to a card below; remove or source "No.1" | Content |
| 50-word subheadline | Too long to scan; the outcome ("Dr." title, board credibility) is buried | Cut to one line on the outcome + one proof line (price, duration, awarding body) | Content |
| One CTA "Talk to a Doctoral Advisor" → `#form` | Good: single CTA. But the form it lands on is titled "Book a Free 1:1 Mentoring Session" — different promise | Same name on button and form | UI/UX + Content |
| Faculty/alumni photo strip (6 "Dr." names) | No link, no role context; "Medical Aesthetician" on an IT program confuses | Link each to LinkedIn, or replace with 3 testimonials from the IT audience | UI/UX |
| Refer & Earn banner above it all | Pushes hero down, competes for first click | Move to footer or a logged-in area | UI/UX |

### Trust & social proof

| What's there | Issue | Fix | Team |
| --- | --- | --- | --- |
| 5 accreditation logos + "Verify Accreditations" link | Logos without country or body name; awarding university never named | Text label under each logo (body + country); name the awarding university beside price | Content + UI/UX |
| 7 embassy logos "Internationally Validated… With Embassy Affiliations" | Embassies don't accredit programs; a sceptical buyer reads this as overclaiming | Keep only what you can document; link each to the evidence on the accreditation page | Content / leadership |
| 23 employer logos (IBM, Deloitte, Ericsson…) | Reads like partnerships; they are alumni employers | Label clearly: "Where our alumni work"; keep 8–10 strongest | Content + UI/UX |
| 14 testimonials with LinkedIn links | Strong — the best asset on the page. But Meheriar Patel and Dr. Lenish Kannan share the identical quote | Replace one quote; move 3 best next to the form | Content + UI/UX |
| 4 case studies | 3 of 4 "Read More" go to `#` | Link the PDFs or remove buttons | Dev |
| Alumni videos (3 titles) | Video assets exist but sit mid-page | Test one 60-sec video beside the form (after Step 3) | UI/UX |

### Features & content

| What's there | Issue | Fix | Team |
| --- | --- | --- | --- |
| "Why Choose" 7 one-line tiles | Mixed list of features and claims; no order of importance | Lead with what a buyer decides on: awarding body, price after scholarship, time per week, outcome | Content |
| Price block: USD $8500, "Up to 45%" scholarship | Good that price is shown. Conflicts with FAQ (8,000); "up to" without criteria; EMI with no terms | One price; show example after scholarship; EMI: number of instalments | Content |
| Program tabs: DBA / MBA / Diploma | Diploma "Learn More" goes to a blog post; MBA Supply Chain goes to a 2025 blog post | Link to program pages or remove until pages exist | Dev + SEO |
| "Top Featured Programs" | Repeats the tab section; MBA Cybersecurity and DBA AI/ML each listed twice | Remove the duplicate section | UI/UX |
| 24 FAQs | Two identical questions (1 and 2); "Can I get a PhD without a Master's?" answered "Yes… a Master's is required" | Fix answers; move price/awarding/time FAQs to the top | Content |

### Navigation & UX

| What's there | Issue | Fix | Team |
| --- | --- | --- | --- |
| Mega-menu: DBA, MBA, Discover, Resources + "Contact Us" | No CTA in nav; "Contact Us" goes to a separate page, not the form | Add a nav button with the same name as the hero CTA | UI/UX |
| Six named actions on one page | "Talk to a Doctoral Advisor", "Talk to a Career Advisor", "Talk to Advisor", "Book a Free 1:1 Mentoring Session", "Check Your Eligibility" (popup), "Start Leadership Journey" (popup) | One name, one form; scholarship check becomes a field in that form | UI/UX + Dev |
| Sticky nav | Not seen on Home (exists on DBA/MBA) | Sticky header with CTA on mobile (after Step 3, as a test) | UI/UX |

### Form

Two forms on one page: 5 fields + WhatsApp checkbox (mid-page), and 3 fields (footer). LinkedIn URL and Message are friction for a first touch. Fix: one form, 3 required fields (Name, Email, Phone with country code), LinkedIn optional; collect the rest on the advisor call.

## Online DBA page, section by section

The DBA page has the strongest offer on the site — price, duration, no GMAT, 1-on-1 mentoring all in the hero — but broken counters and duplicated blocks undo it further down.

### Hero section

| What's there | Issue | Fix | Team |
| --- | --- | --- | --- |
| H1 "Online Doctorate Education Programs" | Title tag and H1 say "Education Programs"; the slug and searchers say "DBA" | H1 and title: "Online DBA" wording that matches the slug | SEO + Content |
| Stats: 12–24 months, 100% online, "45% Scholarships & Feed" | Typo "Feed" in the hero | Fix to "Fees" | Content |
| Bullets: "Approvals: MHRD, MCA, WES++" | "WES++" is unexplained; the FAQ itself says WES evaluates credentials, it doesn't accredit | State exactly what each body confirms, link proof | Content / leadership |
| CTA "Talk to a Doctoral Advisor" → form "Speak with a Program Advisor" | Two names again | Same name on both | Content |

### Trust & social proof

| What's there | Issue | Fix | Team |
| --- | --- | --- | --- |
| Achievement counters | All four show **0** ("0+ Doctorates Enrolled", "0% Completion Rate") | Fix the counter script, or hard-code real numbers. Ship this first | Dev |
| "Consulting Rate Increase: $150/hr" | Presented as an outcome with no source | Source it (named alumnus) or remove | Content |
| 6 testimonials with LinkedIn | Good. Image alt "Nirvate" vs name "Nivate"; Patel shown without "Dr." | Fix names | Content |
| Industry and country charts | Percentages add to 88% and 77%; text names countries the chart lacks | Correct the data or remove the charts | Content |
| Faculty strip incl. "Medical Aesthetician" | Off-audience on an IT DBA | Replace with IT faculty | Content |

### Features & content

| What's there | Issue | Fix | Team |
| --- | --- | --- | --- |
| Price block USD $8500 | FAQ says USD 7,000–10,000; unclear if before or after scholarship | One figure + "after scholarship from $X" example | Content |
| Industry Analytics, career outcomes table, salaries | Each appears **twice**; "Enroll Now" 6× | Delete duplicates; page is a 16-minute read | UI/UX + Dev |
| "Program Highlights" mentions cybersecurity research | Copied from the Cybersecurity DBA page | Make generic, or link to the specialisation | Content |
| DBA vs PhD bullets + table | Same comparison twice | Keep the table only | Content |
| 15 FAQs | Strong coverage; cost and recognition answers sit at #10–12 | Move cost, recognition, admission to the top | Content + SEO |

### Navigation & UX

| What's there | Issue | Fix | Team |
| --- | --- | --- | --- |
| Sticky in-page nav (7 anchors) | Good pattern; targets unverified | Check each anchor scrolls to its section | Dev |
| "Read More" / "Close" on career table | Link to `#` | Wire up or remove | Dev |
| 4 forms on one page (5, 3, 5, 3 fields) | Same as homepage | One form, repeated by anchor | UI/UX + Dev |
| Scholarship check = popup 2872 | Separate path from the advisor form | Merge into the form as an optional question | UI/UX + Dev |

## Online MBA page, section by section

The MBA page is the DBA page with a new H1; an MBA visitor meets doctorate price, doctorate testimonials and a "Doctoral Advisor" button. It needs its own content before any optimisation.

### Hero section

| What's there | Issue | Fix | Team |
| --- | --- | --- | --- |
| H1 "Online Master's  (MBA) Degree Programs" | Double space in source; fine otherwise | Fix spacing | Dev |
| CTA "Talk to a Doctoral Advisor" (popup) | Wrong program on an MBA page | "Talk to an MBA Advisor" or one neutral name used site-wide | Content |
| "45% Scholarships & Feed" | Same typo as DBA | Fix | Content |
| "Approvals: MHRD, WES++" | Same unexplained claim | As DBA | Content |

### Trust & social proof

| What's there | Issue | Fix | Team |
| --- | --- | --- | --- |
| 6 testimonials | All six talk about the **DBA** | Collect 3–6 MBA alumni quotes; until then show none rather than DBA ones | Content |
| Counters | All four show 0 ("0 + MBA Enrollments") | Fix script or real numbers | Dev |
| "DBA Certificate" image | Wrong certificate | MBA certificate sample | Content + UI/UX |
| Embassy logos, alt text "Doctorate Program" | Wrong program in alt text | Fix alt text | SEO |

### Features & content

| What's there | Issue | Fix | Team |
| --- | --- | --- | --- |
| Price block titled "Doctorate (DBA) Program Cost — USD $8500" | No MBA price anywhere; page calls the MBA "a low cost program" | Show the MBA fee | Content |
| Duration: hero 12–24 months; FAQ "24 months" / "2 years" | Contradiction | One figure | Content |
| "100% Online" vs "Flexible Hybrid Options" | Contradiction | Pick the true one | Content |
| Eligibility: FAQ needs 5 years' experience; "Who Can Join" says nothing | Buyer can't self-qualify | State experience requirement near the form | Content |
| Specialisations: nav lists 3, body lists 4; URLs differ between nav and body | Supply Chain has no real page | Align list and URLs; redirect duplicates | SEO + Dev |
| "Build Authority with #1 Online Doctorate Program (DBA)" pre-footer block | DBA promo inside the MBA page | Replace with MBA close, or a soft "Considering a doctorate later?" link | Content + UI/UX |
| 8 FAQs | Generic MBA questions; nothing on price, awarding body, recognition | Add those three first | Content + SEO |

### Navigation & UX

Same 4-form, popup-heavy pattern as DBA. "Read More"/"Close" link to `#`. Program Highlights opens as an overlay with an X — content hidden behind a click. Fix with the same shared-template work as the DBA page.

## Who fixes what

Each team gets a checklist it can own. Leadership must answer two things first — the one true fee and the awarding university — because content, design and SEO all depend on them.

### Leadership / admissions (blocks everyone)

- [ ] Confirm one fee per program (DBA, MBA), and the scholarship rule in one sentence
- [ ] Name the awarding university and what each accreditation logo actually confirms
- [ ] Approve or drop "No.1", "#1", embassy-affiliation claims

### UI/UX & Figma

- [ ] One CTA component, one name, used site-wide (header button, hero, mid-page, footer)
- [ ] One form component: 3 required fields, LinkedIn optional, scholarship question optional; replaces all 4 forms
- [ ] Hero layout per page: outcome line, 3 proof chips (price · duration · awarding body), CTA, 3 testimonials beside the form
- [ ] "Decision block" near the form: fee after scholarship, EMI instalments, awarding university, verify link
- [ ] Logo walls with text labels; employer wall labelled "Where our alumni work"
- [ ] Remove duplicate sections; target DBA page length roughly half of today
- [ ] Move Refer & Earn banner to footer
- [ ] Mobile frames at 360 px: CTA visible on first screen, sticky header CTA

### SEO & content

- [ ] Rewrite price, awarding body and duration so all three pages agree (S1, S2)
- [ ] DBA: H1 and title tag use "Online DBA" to match slug; fix "Feed", "Tranformation"
- [ ] MBA: write MBA-only content — price, testimonials, certificate, FAQs; remove DBA blocks
- [ ] Replace duplicated homepage testimonial; source or drop "$150/hr" and chart percentages
- [ ] FAQ order: cost, recognition, admission first; fix contradictory answers; add FAQPage schema
- [ ] Fix alt text ("Doctorate Program" on MBA, "Nirvate")
- [ ] Align MBA specialisation URLs; 301 duplicates; real page or removal for Supply Chain
- [ ] Program-tab links to program pages, not blog posts

### Development (WordPress / Elementor)

- [ ] Fix zero counters on DBA and MBA
- [ ] Fix every `#` link and wrong footer link (S7); fix `#accreditaion`
- [ ] Build the single form + CTA as global Elementor widgets
- [ ] Make WhatsApp opt-in unticked by default (if it isn't)
- [ ] Remove the 2 extra nav copies and duplicate footer lists from the DOM
- [ ] Core Web Vitals check on mobile after the cleanup

### Analytics

- [ ] Audit the 3 GTM containers; one form-submit event, fired once
- [ ] Match GA4 submits to CRM leads for one month
- [ ] Report weekly: visitors, submits, submit rate, qualified leads — per page and device

## The 4-step roadmap

Each step has a gate; don't start the next until it's met. Step 2 is where most of the lost leads are, and it needs leadership, not designers.

| Step | Work | Teams | Gate before next step | What you get |
| --- | --- | --- | --- | --- |
| 1. Measure | Merge 3 GTM containers into one submit event; match GA4 submits to CRM leads; record 4 weeks by page × device | Analytics, Dev | One submit event that matches CRM | Real baseline submit rate per page; weekly traffic (tells you which tests can run); numbers you can trust |
| 2. Fix trust | One fee; name the awarding university; fix 0 counters, `#` and footer links; MBA page gets MBA price, quotes, FAQs | Leadership, Content, Dev | Leadership signs off fee and awarding body | No contradictions a buyer can find; every link and number works; each page sells its own program |
| 3. Rebuild the path | One CTA name, one 3-field form; fee + awarding body beside the form; cut duplicates; fix DBA H1 and title | UI/UX & Figma, SEO, Dev | 4 weeks of stable data after launch | One clear path to an advisor call; before/after submit rate vs Step 1; shorter, cleaner pages |
| 4. Test and learn | Run X1–X6 one at a time, DBA first; only tests that finish within 8 weeks; guardrail: qualified-lead share | Analytics, UI/UX | — | Proven wins shipped site-wide; a learning log; more submits with lead quality held |

Read top to bottom: what each team does at each step (middle) and what the business can measure once it's done (right). Steps 1 and 2 can start in parallel; Step 3 waits on the Step 2 sign-off; Step 4 waits on clean data.

## A/B experiments (Step 4 only)

Run these only after Steps 1–3, one at a time, on the DBA page first (it has the clearest single offer). Each is from your experiment list and tied to something seen on the pages.

| # | Test (from your list) | Page | Control → Variant | Primary metric | Guardrail |
| --- | --- | --- | --- | --- | --- |
| X1 | Testimonials near form | DBA | Testimonials mid-page → 3 named quotes beside the form | Form submit rate | Qualified-lead share |
| X2 | Field count | DBA | 5 fields → 3 fields, LinkedIn optional | Form submit rate | Qualified-lead share |
| X3 | Benefits above form / "What you'll get" | DBA | Form alone → form + decision block (fee, awarding body, time) | Form submit rate | Call show-up rate |
| X4 | Video testimonial | Home | Photo strip → one 60-sec alumni video in hero | Hero CTA clicks | Page load (LCP) |
| X5 | Sticky nav CTA | Home, mobile | No sticky CTA → sticky header CTA | Form submit rate | Bounce rate |
| X6 | Multi-step form | DBA | One step → step 1 contact, step 2 scholarship question | Step-1 submits | Completed both steps |

**Can each test finish?** Visitors needed per variant, 80% power, 5% significance. Baselines are examples; replace with your real rate from Step 1.

| Baseline submit rate | Per variant, 20% relative lift | Per variant, 30% relative lift |
| --- | --- | --- |
| 1% | 42,693 | 19,827 |
| 2% | 21,109 | 9,798 |
| 3% | 13,914 | 6,455 |

Weeks = (2 × visitors per variant) ÷ weekly visitors to that page. Up to 4 weeks: run. 5–8 weeks: run only a bolder change. Over 8 weeks: don't A/B test — ship the change and watch the trend.

**Not worth testing here:** button colour, button text variants and exit-intent popups. The first two need samples far above these pages' likely traffic; the third adds a seventh interruption to pages already heavy with popups.

## Not checked, questions, sources

**Not checked** — needs input:

- Mobile first screen, tap targets, contrast → phone screenshots of each page at 360 px
- Speed → Core Web Vitals field data (Search Console)
- Popups on arrival, chat widgets → screenshots after 10 seconds on page
- Real conversion rates → GA4 export (Step 1)

**Questions**

- [ ] Which fee is correct for DBA and for MBA?
- [ ] Which university awards the degrees?
- [ ] Weekly visitors and form submits per page for the last 8 weeks?
- [ ] Is the WhatsApp opt-in pre-ticked?

**Sources** (fetched 16 Oct 2026)

- [Homepage](https://imetworldwide.com/)
- [Online DBA programs](https://imetworldwide.com/online-doctorate-business-administration-dba-programs/)
- [Online MBA programs](https://imetworldwide.com/online-masters-mba-degree-programs/)
