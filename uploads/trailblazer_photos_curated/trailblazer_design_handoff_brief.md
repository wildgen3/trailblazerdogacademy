# Trailblazer Dog Academy — Design Handoff Brief
*For: first-draft single-page static layout in Claude Design*

---

## 0. Resolved — locked facts going forward

- **Phone:** `281-387-5693` is correct. Discard the `830` number.
- **Availability messaging:** lead with **"Calls welcome any time."** List operational hours alongside it as reference, not as a restriction: M–F 8AM–6:30PM, Sat 10AM–6:30PM, Sun closed. Outside those windows, calls still go through; texts and the contact form are explicitly fine as backup/async options any time. Contact section copy should carry all three: call anytime, hours for reference, text/form as async fallback.
- **Service structure — confirmed, use as default:** three distinct offerings, sold and listed as separate packages:
  1. **4-Week On-Leash Board & Train**
  2. **6-Week Off-Leash Board & Train**
  3. **Boarding & Daycare**
  Competitive obedience/French Ring stays in Ryan's personal credibility story (About section), not as a fourth sold package.
- **Detail level default:** going forward, the richer About/Philosophy doc content (Ryan's origin story, specific program descriptions, contact form field spec) supersedes the earlier shorthand business-facts summary wherever they differ.
- **Contact form fields**, per that doc: Name (required), Phone (required), Email (optional), issue description (required), best contact time (required).

---

## 1. Photo package

19 images, corrected (crop + light color grade toward the ink/paper/ochre palette) and organized by intended section. Delivered as `trailblazer_photos_curated.zip`, folder structure below. Full-res originals remain untouched in case any crop needs revisiting.

### `/hero` — lead with connection, not work
- `hero_01_main.jpg` — top pick. Sharpest, full resolution, best exposure of the set.
- `hero_02_alt.jpg` — same session as main, alternate framing.
- `hero_03_nuzzle.jpg`, `hero_04_nuzzle_alt.jpg` — warmer, tighter alternate mood.

### `/about` — Ryan portrait candidates
- `about_01_portrait.jpg`, `about_02_portrait_alt.jpg` — genuine smile, dog close, credibility-friendly without gear.
- `about_03_smile_alt.jpg` — note: background setting (park/waterfall) doesn't match the 33-acre property; fine as a portrait, just don't caption it as the property.

### `/programs` — mapped to the confirmed 3 offerings

**1. 4-Week On-Leash Board & Train**
- Primary: `boardtrain_01_paw.jpg` — hand/paw moment, everyday companion-skill energy, matches "life skills to be the best companion" language from the About doc.
- Secondary: `boardtrain_02_paw_alt.jpg`

**2. 6-Week Off-Leash Board & Train**
- Primary: `obedience_03_distance_sit.jpg` — distance and control read clearly, fits "proofing behaviors off leash" positioning.
- Secondary: `obedience_01_alert_sit.jpg`

**3. Boarding & Daycare**
- Primary: `daycare_01_fetch.jpg` — playful energy, matches "pup cups, frozen kongs, playtime" language.
- Secondary: `daycare_03_relaxed_deck.jpg` — calmer, good for the overnight-comfort side of boarding specifically.
- Tertiary/alt: `daycare_02_fetch_alt.jpg`

**Unassigned / flexible spare:** `obedience_02_portrait.jpg` — attentive close portrait, works as a Programs section header/intro image if one is needed, or as a tertiary alt on the off-leash card.

### `/working` — hold for later in the page, per plan
- `protection_01/02/03` — decoy/bite-work documentation. Real, earned, but this is the "lead up into it" material, not front-door material.
- `protection_04_bridge_bond` — handler embracing a dog just off a working session. Useful as the transition image between the working section and the calmer material around it.

---

## 2. Brand reference (for Design's onboarding)

- **Palette:** ink `#1B1A16`, paper `#E9E3D4`, blaze ochre `#A8672E`, pine `#4B5A42`, rust `#9C3B2B`, grass `#D8CBA0`
- **Type:** Big Shoulders Display (headlines), Source Serif 4 (body), IBM Plex Mono (tags/labels)
- **Motif:** trail-blaze mark (axe-slash trail marker) — logo + waypoint markers along a dashed line through the page
- **Voice:** see `trailblazer_brand_voice_framework.md` — earned not performed, direct not decorated, respectful of the difficulty, precise not jargon-heavy, grounded in place, quietly confident not salesy
- **Page order logic:** Hero (connection) → About (Ryan's story) → Programs → Working/credibility → Contact. Protection-work imagery escalates gradually rather than opening the page.

---

## 3. Handoff sequence — ready to execute now, all decisions locked

1. **Start a new Claude Design project** (web or desktop — Design isn't available in this chat surface, so this step happens outside this conversation).
2. **Upload as onboarding context, in this order:**
   - `trailblazer_photos_curated.zip` (or the individual `/hero`, `/about`, `/programs`, `/working` folders — whichever Design's uploader handles better; try the folders first since a zip may not auto-expand there)
   - `trailblazer_brand_voice_framework.md`
   - This brief (`trailblazer_design_handoff_brief.md`) — it now contains the confirmed phone, hours, service structure, and photo-to-card mapping, so Design has the resolved facts, not the open questions.
3. **First prompt to Design should state explicitly:**
   - Page order: Hero → About → Programs (3 cards, in the order listed in Section 1 above) → Working/Credibility → Contact
   - Contact section content: phone `281-387-5693`, "calls welcome any time" as the lead line, hours listed as reference, text/contact form as async fallback, and the 5-field form spec (Name, Phone, Email-optional, description, best time to contact)
   - Instruction to hold protection/decoy imagery for the Working section, not the hero
4. **Point it at the existing `trailblazer_landing.html`** so Design treats the current mockup as a structural starting point rather than improvising the layout from scratch.
5. **First draft review:** treat the output as a structural/layout pass. Drop in the existing locked copy (hero headline, About blurb, program descriptions) verbatim where it fits. FAQ, tagline, and meta description are still open — draft those here first, or placeholder them in Design and swap in once finished.
6. **Nothing is blocking a live draft now** — all three Section 0 items are resolved. The only remaining dependency is the copy still marked open in Section 4 below.

---

## 4. Still open from earlier in this project
- FAQ copy
- Testimonial placeholder language
- Tagline / one-liner
- SEO meta description
- Full copy stress-test against the voice framework (now informed by Ryan's actual origin-story language, which is warmer and more narrative than the framework alone assumed)
