# QA-NOTES.md — Gurukul Management Studies Hotel & Hospitality Management Landing Page

Generated: 2026-05-27 | Conversion from SBIHM BHM landing page

---

## 1. PLACEHOLDERS INSERTED (FLAGS) — Client Action Required

| # | Section | Flag | Client Must Supply |
|---|---------|------|--------------------|
| 1 | HEAD / canonical | `[[FLAG: canonical URL]]` (line ~21) | Final Gurukul landing-page domain. Placeholder: `https://gurukulmanagementstudies.in/hotel-hospitality-management/` |
| 2 | HEAD / og:image | `[[FLAG: og:image URL]]` | Gurukul OG image file URL |
| 3 | HEAD / og:url | `[[FLAG: og:url]]` | Final Gurukul landing-page URL |
| ~~4~~ | ~~Utility Bar / Hero / Apply / Footer~~ | ~~WhatsApp links removed~~ | **RESOLVED 2026-05-28** — WhatsApp number confirmed as +91-9830390636. Buttons reinstated in utility bar, FAB, apply section, thank-you state, and footer. |
| ~~5~~ | ~~Hero form (hero)~~ | ~~`[[FLAG: Form webhook]]`~~ | **RESOLVED 2026-05-28** — Unified Gurukul webhook deployed and wired to all forms via `submitGurukulForm`. |
| 6 | Programme — Eligibility | `[[FLAG: Eligibility — client to confirm]]` | Eligibility criteria for admission (Gurukul has not published these; do NOT copy SBIHM's "10+2 50%") |
| 7 | Awards — Card 4 | `[[FLAG: Award title required from client]]` | Title/name of the award corresponding to `Award4.png` |
| 8 | Campus — Map links | `[[FLAG: Google Maps URLs]]` (×2) | Correct Google Maps pins for Main Campus (Kankinara) and City Office (Bidhannagar) |
| 9 | Testimonials | `[[FLAG: Student testimonial pending — client to provide]]` (×6) | 6 real Gurukul student testimonials: name, batch year, placement/role, quote |
| 10 | Admission Step 5 | `[[FLAG: Orientation/class-start dates]]` | Confirmed 2026–27 orientation and class-start dates |
| 11 | FAQ — Eligibility | `[[FLAG: Eligibility criteria to be confirmed]]` | Same as item 6 — eligibility for FAQ answer |
| 12 | Apply form (footer) | `[[FLAG: Form webhook]]` | Same Gurukul webhook/Sheet endpoint (applies to footer form too) |
| 13 | Footer — Social media | `[[FLAG: Social media URLs]]` (×4) | Gurukul Facebook, Instagram, LinkedIn, YouTube profile URLs; icons currently link to `#` |
| 14 | Footer banner | `[[FLAG: Footer banner image is SBIHM-branded]]` | Gurukul-branded footer banner image to replace `sbihm_FooterBanner_all.jpg.jpeg` |
| 15 | JSON-LD / og URL | Placeholder domain used | Final domain to replace `https://gurukulmanagementstudies.in/` |
| 16 | GTM Tag | `GTM-5KFQNGBB` left in place | Client to replace with Gurukul's own GTM container ID before go-live |

---

## 2. REMOVED CONTENT (No Gurukul-verified equivalent)

| Item Removed | Original Location | Reason |
|---|---|---|
| ~~Recruiter logo wall (Taj, ITC, JW Marriott, Hyatt, Oberoi, Radisson, Leela, Hilton, Pride, Crown Plaza, Carnival, Apollo, Fortis, IndiGo, Akasa, Ginger, Vivanta, HRC, WW, The Park)~~ | Section 10 — Partners | **RESTORED 2026-05-27** — Client approved all 20 as verified recruiting partners. Scrolling marquee wall reinstated. |
| Placement salary stats (₹16.4 LPA top, ₹3.2–16.4 LPA average, Median ₹4.8 LPA) | Section 9 — Careers aside | Gurukul has not published placement figures |
| Celebrity attributions (Sanjeev Kapoor, Ranveer Brar, Kapil Dev, Sunil Gavaskar, Brett Lee, Times of India, ABP News, Zee 24 Ghanta) | Section 7 — Awards | None of these apply to Gurukul |
| 5 excess award cards (SBIHM had 9; Gurukul has 4 Award*.png files) | Section 7 — Awards | Only 4 Award PNG files exist; 3 known Gurukul award titles + 1 flagged |
| WB Student Credit Card funding card | Section 13 — Fees | Not mentioned by Gurukul; remove unless client confirms eligibility |
| NCHMCT JEE FAQ | Section 15 — FAQ | Not applicable to Gurukul |
| International internship specifics (Thailand/Pathum Thani, USA/American Hotel Academy, Mauritius, Dubai, Europe) | FAQ + Programme | These are SBIHM's specific partners; not published by Gurukul |
| Named hotel internship brands (Taj, ITC, Hyatt, Oberoi, JW Marriott) | Programme Section 8 | Not published by Gurukul |
| Named hotel employers in career cards (Taj, ITC, Hyatt, Marriott, Hilton, Radisson, IndiGo, Emirates, Apollo, Fortis) | Section 9 — Career cards | Not published by Gurukul |
| WhatsApp links (wa.me/917003872527) | Utility bar, Apply section, Footer, Thank-you state | Gurukul has not provided a WhatsApp number |
| UGC and NCHMCT affiliations | Hero badges, Programme quick info, Footer affiliations | Gurukul does not hold these; replaced with IIC and Ministry of Education |

---

## 3. INDICATIVE / UNVERIFIED CONTENT

| Item | Location | Status |
|---|---|---|
| Year-wise curriculum (Year 1–4 breakdown) | Section 8 — Programme | Marked "Indicative learning journey" — client must confirm or supply MAKAUT-approved syllabus |
| Eligibility criteria | Programme quick info + FAQ | Flagged — not published by Gurukul |
| Internship description ("industry exposure and internships with hospitality establishments") | Programme Year 2 block | Generic phrasing used; no named hotels or institutions |
| Stats counter: 4 / 8 / 70 / 100% | Stats strip | 4-year duration, 8 semesters, 70 seats, 100% placement assistance sourced from Gurukul's own site |
| Award titles (Award1–Award3) | Section 7 — Awards | CSR Award, Education Excellence Award, Royal National Leadership Award — sourced from Gurukul site |
| Hostel fees (₹3,600/month + ₹3,000 admission) | Fees section + FAQ | Sourced from Gurukul's published fee schedule |
| Full fee structure (₹40,000 admission + ₹25,000 × 8 semesters = ₹2,40,000) | Fees section | Sourced from Gurukul's published Hotel & Hospitality Management (4 Years Honors) fee structure |
| Merit discounts (15%/10%/5%), one-time payment discount (7%), Army/Police eligibility | Fees section | Sourced from Gurukul's published information |

---

## 4. IMAGES CLIENT MUST SUPPLY

| File | Purpose | Current State |
|---|---|---|
| `gurukul_logo.png` | Header + footer logo | **PRESENT** in `assets/images/` — already in use |
| `Award1.png` | Award card 1 (CSR Award Winner) | **PRESENT** — mapped |
| `Award2.png` | Award card 2 (Education Excellence Award Winner) | **PRESENT** — mapped |
| `Award3.png` | Award card 3 (Royal National Leadership Award Winner) | **PRESENT** — mapped |
| `Award4.png` | Award card 4 (title unknown — flagged) | **PRESENT** — mapped; title needed |
| `makaut.png` | Affiliation logo — MAKAUT | **PRESENT** in `assets/images/` |
| `aicte.webp` | Affiliation logo — AICTE | **PRESENT** in `assets/images/` (note: `.webp` not `.png`) |
| `IIC.png` | Affiliation logo — IIC | **PRESENT** in `assets/images/` |
| `mhrd.png` | Affiliation logo — Ministry of Education | **PRESENT** in `assets/images/` (confirm this is the correct MoE logo) |
| `photo1.png` – `photo5.png` | Campus/lab facility photos | **SBIHM IMAGES** — client must supply genuine Gurukul campus and lab photos |
| Footer banner | Footer banner image | **SBIHM-BRANDED** (`sbihm_FooterBanner_all.jpg.jpeg`) — client must supply Gurukul version |
| Hero student photo | Hero background | Not present (hero is CSS background) — flag for client review |

---

## 5. OPEN CLIENT CONFIRMATIONS REQUIRED BEFORE GO-LIVE

| # | Item | Detail |
|---|------|--------|
| 1 | **Final domain** | Replace placeholder `https://gurukulmanagementstudies.in/` in canonical, og:url, og:image, JSON-LD |
| ~~2~~ | ~~**Form webhook endpoint**~~ | **RESOLVED 2026-05-28** — All three forms (hero, contact, brochure) wired to unified Gurukul Apps Script webhook via `submitGurukulForm`. |
| ~~3~~ | ~~**WhatsApp number**~~ | **RESOLVED 2026-05-28** — WhatsApp: +91-9830390636. Links added to utility bar, FAB (replaced phone FAB), apply section, thank-you state, and footer. |
| 4 | **GTM container ID** | Replace `GTM-5KFQNGBB` (SBIHM's) with Gurukul's own GTM ID |
| 5 | **Social media URLs** | Supply Facebook, Instagram, LinkedIn, YouTube URLs for footer social icons (currently `href="#"`) |
| 6 | **Orientation / class-start dates** | Step 5 of admission process currently flagged — supply 2026–27 dates |
| 7 | **Eligibility criteria** | Confirm admission eligibility for the Hotel & Hospitality Management programme |
| 8 | **Award 4 title** | Supply the award name/title for `Award4.png` |
| 9 | **Awards verifiability** | If the 3 named Gurukul awards are publicly verifiable, the section heading can be strengthened back to SBIHM's original stronger phrasing |
| ~~10~~ | ~~**Recruiter partnerships**~~ | **RESOLVED 2026-05-27** — Client approved all 20 partners. Marquee grid restored in Section 10. |
| 11 | **Student testimonials** | Supply 6 real Gurukul student names, batch years, placements, and quotes |
| 12 | **Gurukul campus/lab photos** | Supply 5 genuine Gurukul campus/lab photos to replace `photo1.png`–`photo5.png` |
| 13 | **Footer banner image** | Supply a Gurukul-branded banner to replace the SBIHM footer banner |
| 14 | **WB Student Credit Card** | Confirm if Gurukul is eligible; if yes, reinstate the credit card funding card |

---

## 6. NOTES ON PROTECTED STRINGS REMAINING IN FILE

The following SBIHM-named strings **intentionally remain** because they are CSS variable names or class names that cannot be changed per the brief (touching CSS or class attributes is prohibited):

- CSS variables: `--sbihm-red`, `--sbihm-red-dark`, `--sbihm-red-soft`, `--sbihm-black`, `--sbihm-charcoal`, `--sbihm-gold`, etc. (in `<style>` block)
- Form class: `sbihm-lead-form` (on both hero and footer forms)
- Google Tag Manager: `GTM-5KFQNGBB` — SBIHM's GTM container (see item 4 in Section 5 above)

These do not appear in user-visible rendered content and do not need to be changed for the page to function correctly. The GTM container ID should be replaced before go-live.
