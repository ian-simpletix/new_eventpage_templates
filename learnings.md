# Template Voting Learnings
## Based on 411 User Comparisons

---

## Executive Summary

After collecting **411 head-to-head comparisons** from real users, we identified clear patterns in what makes event page templates succeed or fail. **18 templates were archived** to the graveyard based on poor performance, while **26 templates survived** with varying success levels.

**The Core Finding:** Users overwhelmingly prefer **"professional indie"** aesthetics - templates that balance trustworthiness with personality, modern design without gimmicks, and clean layouts with warmth.

### Key Statistics
- **Total matches:** 411
- **Templates tested:** 44
- **Archived (DEAD):** 18 (40.9%)
- **Survivors:** 26 (59.1%)
- **Top performer:** greenpoint (95.5% win rate, ELO 1711)
- **Worst performer:** terminal (3.4% win rate, ELO 1223)

---

## The Winners: Common Traits

### Top 10 Templates (By ELO)

1. **greenpoint** (95.5% win, ELO 1711, 22 matches) - Premium/Luxury
2. **zine** (79.2% win, ELO 1632, 24 matches) - Creative/Arts
3. **risograph** (92.9% win, ELO 1630, 14 matches) - Creative/Arts
4. **heartland** (80% win, ELO 1625, 20 matches) - Corporate/Professional
5. **losangeles** (80% win, ELO 1616, 15 matches) - Wellness/Lifestyle
6. **nordic** (73.9% win, ELO 1612, 23 matches) - Corporate/Professional
7. **classic_publisher** (75% win, ELO 1610, 20 matches) - Education/Academic
8. **mesa** (70% win, ELO 1594, 20 matches) - Community/Family
9. **williamsburg** (100% win, ELO 1594, 7 matches) - Creative/Arts
10. **brutalist** (75% win, ELO 1585, 16 matches) - Creative/Arts

### Design Patterns That Won

#### **Color Philosophy**
- **Backgrounds:** Warm/neutral tones - cream (#fef9f3), light gray (#e5e7eb), warm white (#fdfdfc), beige
- **Accent colors:** 1-2 maximum - used strategically for CTAs
- **Total palette:** 2-4 colors (not 5+)
- **Temperature:** Warm or neutral (never pure black or neon)

**Examples:**
- greenpoint: `#f8f8f8` background, `#166534` green CTA
- zine: `#e2e8f0` background, `#fef08a` yellow CTA
- risograph: `#fef9f3` cream background, `#0078bf` blue + `#ff6c47` orange accents

#### **Typography**
- **Font count:** 1-2 families maximum
- **Body text:** 16-18px, line-height 1.6-1.8
- **Titles:** 48-72px (not extreme)
- **Letter-spacing:** Default or 1-2px max
- **Choices:** Professional sans-serifs (Inter, Roboto) or strategic serif accents (Playfair Display for titles only)

**Examples:**
- greenpoint: Inter + Playfair Display (titles)
- zine: Courier Prime + Permanent Marker
- losangeles: Inter throughout (weight variations)

#### **Spacing & Layout**
- **Section padding:** 40-60px on desktop, 20-30px mobile
- **Between sections:** 32-40px (`mt-8` to `mt-10`)
- **Line height:** 1.6-1.8 for readability
- **Breathing room:** Generous whitespace, not cramped

**Layout patterns:**
- Asymmetric 2-column (sticky sidebar + scrolling content)
- Single column centered (max-width 1200px)
- Sticky CTAs that appear intelligently

#### **Visual Complexity**
- **3-4 elements** visible on first screen
- Clear hierarchy: Title > Event Details > Description > CTA
- **Minimal decorative** elements (borders used sparingly)
- 1-2 images maximum on initial view

#### **CTA Buttons**
- **Style:** Solid color fills (no gradients)
- **Contrast:** 3:1+ ratio minimum
- **Padding:** Generous (`px-8 py-4`)
- **Effects:** Simple shadows or borders, no glows/animations

**Examples:**
- greenpoint: `bg-green-800`, white text, rounded-lg, shadow-lg
- zine: `#fef08a` yellow, dashed border, marker font
- risograph: `#ff6c47` orange, 4px black border, 6px shadow offset

#### **Overall Feel**
Winners feel: **Professional, Calm, Trustworthy, Easy-to-Scan, Warm, Contemporary**

---

## The Losers: Common Traits

### Bottom 10 Templates (By ELO)

35. **editorial** (28.6% win, ELO 1423) - Typography/Minimalist [DEAD]
36. **ice_rink** (33.3% win, ELO 1422) - Special Occasions [DEAD]
37. **glitch** (20% win, ELO 1405) - Creative/Arts [DEAD]
38. **deco** (27.8% win, ELO 1401) - Premium/Luxury [DEAD]
39. **maximalist** (34.8% win, ELO 1393) - Creative/Arts [DEAD]
40. **hologram** (21.7% win, ELO 1363) - Corporate/Professional [DEAD]
41. **web1** (7.1% win, ELO 1346) - Creative/Arts [DEAD]
42. **academic_poster** (19.2% win, ELO 1325) - Creative/Arts [DEAD]
43. **algorithm** (16.9% win, ELO 1246, **59 matches**) - Corporate/Professional [DEAD]
44. **terminal** (3.4% win, ELO 1223, 29 matches) - Corporate/Professional [DEAD]

### Design Anti-Patterns That Failed

#### **Color Philosophy**
- **Backgrounds:** Pure black (#000), dark blue-black (#0a0e27, #0d0d1a)
- **Accent colors:** Neon/fluorescent (#00ff00, #ff00ff, #00ff41)
- **Total palette:** 5-8+ colors OR extreme monochromatic
- **Temperature:** Cold extremes (tech aesthetic)

**Examples:**
- terminal: `#000000` background, `#00ff00` bright green text (Matrix)
- algorithm: `#0a0e27` dark blue, `#00ff41` neon green, `#00d4ff` cyan
- web1: 6+ garish colors (`#000099`, `#ff00ff`, `#00ff00`, `#ffff00`)

#### **Typography**
- **Monospace for body text** (Source Code Pro, JetBrains Mono)
- **Novelty display fonts** (Orbitron sci-fi, Comic Sans)
- **Extreme letter-spacing:** 4-8px (feels forced)
- **Oversized titles:** 84px+ or 48px with extreme spacing
- **Font overload:** Double monospace or double serif

**Examples:**
- terminal: Source Code Pro everywhere, 48px + 4px letter-spacing
- algorithm: JetBrains Mono + Space Mono (double monospace)
- deco: Playfair Display + Libre Baskerville, 84px titles + 8px letter-spacing

#### **Spacing & Layout**
- Heavy borders everywhere (5-10px double/ridge/outset)
- Inconsistent spacing (some tight, some loose)
- Decorative elements competing for attention
- Over-styled containers (ASCII borders, geometric patterns)

**Examples:**
- deco: 6px double borders, corner ornaments, chevron patterns
- web1: 5-10px ridge/outset 3D borders
- terminal: 2px borders + glowing box-shadows + CRT scanlines

#### **Visual Complexity**
- **6-10+ elements** on first screen
- Multiple competing effects (scanlines + glows + borders + animations)
- Thematic consistency over usability
- Text effects (glows, shadows, rainbow animations)

#### **CTA Buttons**
- Gradient fills (linear/radial)
- Animations (blinking, shimmer, loading bars)
- Decorative symbols (`>`, `◆`, `//`)
- Glow effects or extreme shadows
- Low contrast with heavy styling

**Examples:**
- terminal: Black bg + green border + glow + "> TEXT <"
- web1: Red-to-yellow gradient, 5px outset border, blinking, 5px shadow
- deco: Gold gradient with shimmer, ornate borders

#### **Overall Feel**
Losers feel: **Gimmicky, Try-Hard, Hard-to-Read, Themed-Over-Functional, Cold, Dated**

---

## Key Differentiators: Winners vs Losers

### Color Temperature
- ✅ **WINNERS:** Warm/neutral (beige, cream, light gray, stone)
- ❌ **LOSERS:** Cold extremes (pure black, dark blue, neon green/cyan)

### Contrast Philosophy
- ✅ **WINNERS:** Moderate contrast (80-90% vs 10-20%), easy on eyes
- ❌ **LOSERS:** Extreme contrast (100% black vs 100% fluorescent)

### Color Count
- ✅ **WINNERS:** 2-4 colors total
- ❌ **LOSERS:** 5-8+ colors OR monochromatic extremes

### Font Philosophy
- ✅ **WINNERS:** "Pick a good font and use it well" (1-2 fonts)
- ❌ **LOSERS:** "Express theme through typography" (novelty fonts)

### Body Text
- ✅ **WINNERS:** 16-18px sans-serif, readable
- ❌ **LOSERS:** 14-16px monospace, harder to scan

### Title Treatment
- ✅ **WINNERS:** 48-72px, minimal letter-spacing
- ❌ **LOSERS:** 48px + extreme spacing OR 84px+ overwhelming

### Letter Spacing
- ✅ **WINNERS:** Default or 1-2px on uppercase
- ❌ **LOSERS:** 4-8px (feels forced/designed)

### Borders
- ✅ **WINNERS:** None or simple 1-3px solid, used sparingly
- ❌ **LOSERS:** 5-10px double/ridge/outset, decorative patterns

### Animations
- ✅ **WINNERS:** Simple hover states, subtle transitions
- ❌ **LOSERS:** Scanlines, glows, rainbow, blinking, shimmer

### CTA Buttons
- ✅ **WINNERS:** Solid fill, simple text, subtle shadow
- ❌ **LOSERS:** Gradients, glows, symbols, animations

### Visual Density
- ✅ **WINNERS:** 3-4 elements on first screen
- ❌ **LOSERS:** 6-10+ competing elements

### Background Treatment
- ✅ **WINNERS:** Solid color or very subtle texture
- ❌ **LOSERS:** Patterns (stripes, geometric, CRT scanlines)

### Content Hierarchy
- ✅ **WINNERS:** Clear (Title 60px > Body 18px > Labels 14px)
- ❌ **LOSERS:** Flat (everything styled thematically at similar weight)

---

## Category-Specific Insights

### Corporate_Professional (7 templates: 2 survived, 5 dead)

**SURVIVORS:**
- heartland (#4, 80%) - "Warm conference" style
- nordic (#6, 73.9%) - Scandinavian minimalism

**DEAD:**
- algorithm (16.9%, 59 matches) - Tech corporate
- keynote (42.4%) - Generic presentation style
- terminal (3.4%, 29 matches) - Command-line gimmick
- hologram (21.7%) - Futuristic tech

**Learning:** Traditional "corporate professional" is dead. Only "warm conference" and "Scandinavian lifestyle" aesthetics work. Users reject cold, tech-focused, generic presentation styles.

### Creative_Arts (13 templates: 6 survived, 7 dead)

**TOP PERFORMERS:**
- zine (#2, 79.2%)
- risograph (#3, 92.9%)
- williamsburg (#9, 100% but small sample)
- brutalist (#10, 75%)

**MID-TIER:**
- archival (54.5%)
- critical (69.6%)
- mycelium (55.6%)
- punk (66.7%)
- collage (51.9%)

**DEAD:**
- web1 (7.1%) - GeoCities nostalgia
- glitch (20%) - Matrix/tech glitch
- academic_poster (19.2%) - Academic formality
- maximalist (34.8%) - Too much visual noise
- memphis (48.6%) - 80s patterns

**Learning:** Highly polarizing category. Quality craft aesthetics (zine, risograph) dominate. Gimmicks (web1, glitch) and visual chaos (maximalist) fail badly. Execution matters MORE than concept.

### Premium_Luxury (4 templates: 2 survived, 2 dead)

**WINNER:**
- greenpoint (#1, 95.5%) - Understated modern luxury

**MID-TIER:**
- couture (38.9%) - Haute couture styling

**DEAD:**
- deco (27.8%) - Art Deco ornamental
- asheville (43.8%) - Goth luxury with decoration

**Learning:** Only understated modern luxury works. Ornamental luxury (deco, asheville) fails. Modern luxury = restraint + quality materials, NOT decoration. Greenpoint proves "less is more" in premium space.

### Typography_Minimalist (5 templates: 3 survived, 2 dead)

**SURVIVORS:**
- swiss (#11, 71.4%)
- bauhaus (#13, 71.4%)
- zen (#20, 63.6%)

**DEAD:**
- editorial (28.6%) - Too stark
- type_brutalist (41.7%) - Brutalism without warmth

**Learning:** Typography minimalism is safe but not elite. All survivors are mid-tier (none in top 10). Pattern: Clean typography works when paired with warmth. Brutalist typography without warmth fails.

### Community_Family (2 templates: 2 survived)

**BOTH STRONG:**
- mesa (#8, 70%)
- community (#15, 64.7%)

**Learning:** Underexplored category with consistent performance. Warm, approachable, family-friendly aesthetics work well. Opportunity to create more templates in this space.

### Wellness_Lifestyle (1 template: 1 survivor)

**WINNER:**
- losangeles (#5, 80%)

**Learning:** Strong performer but only 1 template in category! Airy, optimistic, wellness aesthetic resonating. Major opportunity for expansion - "wellness" vibe is underrepresented but highly successful.

### Music_Entertainment (4 templates: 2 survived, 2 dead)

**SURVIVOR:**
- immersive (#12, 59.1%) - Theatrical concert vibe

**MID-TIER:**
- neon_tokyo (30%) - Neon aesthetic

**DEAD:**
- vaporwave (33.3%) - 80s/90s nostalgia
- manuscript (37.5%) - Classical formal

**Learning:** Entertainment needs energy without kitsch. Immersive works (theatrical but readable), while themed nostalgia (vaporwave) and formality (manuscript) fail.

### Education_Academic (3 templates: 2 survived, 1 dead)

**SURVIVORS:**
- classic_publisher (#7, 75%) - Editorial/refined
- cambridge (#16, 72.7%) - Academic but warm

**DEAD:**
- lab_notes (46.2%) - Scientific/clinical

**Learning:** "Academic" works when it means "refined editorial", not "stuffy lecture hall". Classic publisher succeeds by being sophisticated without being cold.

### Special_Occasions (4 templates: 1 survived, 3 dead)

**SURVIVOR:**
- halloween (#19, 66.7%) - Seasonal fun

**DEAD:**
- basketball (80% but marked DEAD - possibly error?)
- ice_rink (33.3%)
- winter_holiday (37.5%)

**Learning:** Seasonal templates are hit-or-miss. Halloween works (recognizable holiday), but niche events (ice skating, winter generic) struggle. Question: Is "occasion-specific" too narrow?

---

## Strategic Recommendations

### Immediate Actions

#### **Kill These Categories (Poor Performers):**
1. **Tech Corporate** - algorithm, terminal, hologram all failed (<22% win rates)
2. **Novelty Web Design** - web1 (7%), glitch (20%), neon_tokyo (30%)
3. **Ornamental Luxury** - deco (27.8%), asheville (43.8%)
4. **Academic Formal** - academic_poster (19.2%)
5. **Maximalism** - maximalist (34.8%)

#### **Double Down On (Proven Winners):**
1. **Quality DIY/Craft** - zine (79.2%), risograph (92.9%)
2. **Warm Professional** - heartland (80%), classic_publisher (75%)
3. **Understated Luxury** - greenpoint (95.5%)
4. **Community/Family** - mesa (70%), community (64.7%)
5. **Wellness/Lifestyle** - losangeles (80%)

### Template Creation Priorities

#### **HIGH PRIORITY (Create 3-5 new templates):**

1. **More "Wellness/Lifestyle"** (only 1 currently!)
   - Target: Yoga retreats, meditation workshops, wellness festivals
   - Style: Airy, optimistic, clean + warm
   - Colors: Warm whites, stone tones, soft greens/blues
   - Example: Expand on losangeles success

2. **More "Warm Conference"** (only heartland in top 10)
   - Target: Professional conferences, business events
   - Style: Professional without corporate, warm color palette
   - Colors: Light grays, warm blues, earth tones
   - Example: Heartland variations with different color schemes

3. **More "Quality DIY/Craft"** (zine + risograph dominating)
   - Target: Indie events, art shows, markets
   - Style: Handmade aesthetic + tight execution
   - Colors: Limited 3-color palettes, print-inspired
   - Example: Letterpress, screen-print, risograph variants

4. **More "Community/Family"** (only 2 templates, both performing well)
   - Target: Local events, family gatherings, community festivals
   - Style: Approachable, warm, friendly without childish
   - Colors: Warm earth tones, friendly accent colors
   - Example: Neighborhood block party, farmers market

5. **"Modern Luxury" Variations** (greenpoint dominates but only 1 template)
   - Target: Premium events, galas, upscale experiences
   - Style: Understated elegance, quality over decoration
   - Colors: Neutrals with sophisticated accents
   - Example: Japanese minimalist luxury, Scandinavian luxury

#### **MEDIUM PRIORITY:**

6. **"Swiss Typography + Color"** (swiss performing well but only 8 matches)
   - Test: Swiss grid with bold color accents
   - Test: Swiss with subtle illustration

7. **"Refined Punk"** (punk 66.7% - DIY + polish)
   - Test: Music venue, indie film, art show variants
   - Balance: Attitude without chaos

#### **AVOID (Based on data):**

❌ More typography minimalism (saturated, mid-tier)
❌ Any tech/corporate aesthetics (all failed)
❌ Novelty/gimmick designs (consistently bombed)
❌ Ornamental luxury (only understated works)
❌ Maximalist approaches (visual noise fails)
❌ Seasonal/niche occasion-specific (too narrow)

---

## Design Principles: The Winner Formula

### **DO THIS:**

1. **Colors:** Use warm/neutral backgrounds (cream, light gray, warm white)
2. **Colors:** Pick ONE accent color for CTAs (solid blue, green, orange - not neon)
3. **Colors:** Limit to 2-4 colors total in entire palette
4. **Typography:** Use 1-2 professional fonts (Inter, Roboto, system sans)
5. **Typography:** Keep body text 16-18px, line-height 1.6-1.8
6. **Typography:** Make titles 48-60px, minimal letter-spacing
7. **Spacing:** Give content breathing room (40px+ between sections)
8. **CTAs:** Use solid color buttons with high contrast (no gradients)
9. **Layout:** Keep it simple: Title > Details > Description > CTA
10. **Simplicity:** Show 3-4 elements max on first screen

### **AVOID THIS:**

1. ❌ Pure black (#000) or dark blue (#0a0e27) backgrounds
2. ❌ Neon/fluorescent colors (#00ff00, #ff00ff, #00d4ff)
3. ❌ Monospace fonts for body text
4. ❌ Novelty/display fonts for everything
5. ❌ Letter-spacing over 3px
6. ❌ Multiple borders, glows, shadows per element
7. ❌ Animations beyond simple hover states
8. ❌ Gradient CTA buttons
9. ❌ Thematic styling that sacrifices usability
10. ❌ 5+ colors or overly complex palettes
11. ❌ Decorative elements competing with content
12. ❌ Background patterns (stripes, geometric shapes, scanlines)

### **The Core Pattern:**

**Winners are "professionally understated."**
**Losers are "thematically overdesigned."**

Users voted for **"I can easily find information and trust this event"** over **"This looks like a cool theme experiment."**

---

## Specific Design Values That Won

### Color Codes (Hex Values)

**WINNING BACKGROUNDS:**
- `#f8f8f8` (very light gray) - greenpoint
- `#fef9f3` (warm cream) - risograph
- `#e2e8f0` (light gray-blue) - zine
- `#e5e7eb` (gray-200) - heartland
- `#fdfdfc` (warm white) - losangeles

**WINNING ACCENTS:**
- `#166534` (green-800) - greenpoint CTA
- `#fef08a` (warm yellow) - zine CTA
- `#ff6c47` (warm orange) - risograph CTA
- Blue-700 variants - heartland, nordic

**LOSING BACKGROUNDS:**
- `#000000` (pure black) - terminal, deco
- `#0a0e27` (dark blue-black) - algorithm
- `#0d0d1a` (near black) - glitch
- `#0a0a0a` (black) - deco

**LOSING ACCENTS:**
- `#00ff00` (neon green) - terminal, algorithm
- `#ff00ff` (magenta) - web1
- `#00d4ff` (cyan) - algorithm
- `#d4af37` (metallic gold) - deco

### Fonts That Won
- Inter (body + titles) - greenpoint, losangeles
- Roboto (body) - heartland, various
- Playfair Display (titles only, paired with sans) - greenpoint
- Courier Prime (with character, not everywhere) - zine, risograph
- Permanent Marker / Special Elite (headlines only) - zine, risograph
- Oswald (titles) - heartland

### Fonts That Lost
- Source Code Pro (body text) - terminal
- JetBrains Mono + Space Mono (double monospace) - algorithm
- Orbitron (sci-fi display) - glitch
- Comic Sans MS - web1
- Playfair + Libre Baskerville (double serif) - deco

### Spacing Values That Won
- Section padding: `px-6 md:px-12` (24-48px)
- Between sections: `mt-8` to `mt-12` (32-48px)
- Line height: `leading-relaxed` (1.625) to `leading-loose` (2)
- Button padding: `px-8 py-3` to `px-8 py-4`
- Max width: `max-w-4xl` to `max-w-6xl` (1024-1280px)

### Border Styles That Won
- None (most common)
- `border` (1px solid) - used sparingly
- `border-2` or `border-3` (2-3px solid) - zine, risograph used deliberately
- Dashed borders for character (zine button)

### Border Styles That Lost
- `5px double` - deco
- `6px ridge` - web1
- `10px outset` - web1
- Multiple nested borders - deco

---

## Market Insights

### What Event Organizers Want:

✅ **Personality** without chaos (zine, not maximalist)
✅ **Professional** without corporate (heartland, not algorithm)
✅ **Modern** without trendy (greenpoint, not neon_tokyo)
✅ **Quality** without pretension (risograph, not couture)
✅ **Warm** without childish (mesa, losangeles)
✅ **Distinctive** without gimmicky (punk, not glitch)
✅ **Clean** without sterile (swiss, not type_brutalist)

### What They Explicitly Reject:

❌ Corporate tech templates (terminal 3.4%, algorithm 16.9%)
❌ Web design novelty (web1 7.1%, glitch 20%)
❌ Academic formality (academic_poster 19.2%)
❌ Ornamental decoration (deco 27.8%, asheville 43.8%)
❌ Maximalist chaos (maximalist 34.8%)
❌ Cold minimalism (type_brutalist 41.7%, editorial 28.6%)

### The Market Position:

Event organizers are rejecting **both extremes:**
- Generic corporate templates ← REJECTED
- Overwrought creative chaos ← REJECTED

They want: **"Professional indie"** - Sophisticated enough to trust, creative enough to remember.

---

## The Greenpoint Lesson

**Why greenpoint dominates (95.5% win rate, ELO 1711, 22 matches):**

1. **Understated modern luxury** - looks expensive without trying
2. **Professional but not corporate** - trustworthy without being cold
3. **Distinctive but not weird** - memorable without gimmicks
4. **Warm color palette** - `#f8f8f8` background, natural tones
5. **Quality typography** - Inter + Playfair Display (restrained serif)
6. **Clear hierarchy** - sticky sidebar, easy to scan
7. **Generous spacing** - content breathes, not cramped
8. **Simple CTA** - solid `#green-800`, white text, simple shadow

**The takeaway:** Users want templates that feel like **"A professional designer made this for my specific event"** not **"I downloaded a theme and customized it."**

---

## Archived Templates (Moved to Graveyard)

The following 18 templates were archived based on poor performance:

### Corporate_Professional (4 dead)
- algorithm.html (16.9% win, 59 matches - most tested failure)
- hologram.html (21.7% win, 23 matches)
- keynote.html (42.4% win, 33 matches)
- terminal.html (3.4% win, 29 matches - worst overall)

### Creative_Arts (5 dead)
- academic_poster.html (19.2% win, 26 matches)
- glitch.html (20% win, 15 matches)
- maximalist.html (34.8% win, 23 matches)
- memphis.html (48.6% win, 35 matches)
- web1.html (7.1% win, 14 matches - only 1 win)

### Premium_Luxury (2 dead)
- asheville.html (43.8% win, 16 matches)
- deco.html (27.8% win, 18 matches)

### Education_Academic (1 dead)
- lab_notes.html (46.2% win, 13 matches)

### Music_Entertainment (2 dead)
- manuscript.html (37.5% win, 8 matches)
- vaporwave.html (33.3% win, 6 matches)

### Typography_Minimalist (2 dead)
- editorial.html (28.6% win, 14 matches)
- type_brutalist.html (41.7% win, 12 matches)

### Special_Occasions (3 dead)
- basketball.html (80% win, 10 matches - marked dead, possibly user choice)
- ice_rink.html (33.3% win, 18 matches)
- winter_holiday.html (37.5% win, 8 matches)

These templates are preserved in `/graveyard/` folder (untracked) for reference.

---

## Next Steps

1. **Create 3-5 new templates** in high-priority categories:
   - 2x Wellness/Lifestyle (expand on losangeles)
   - 1x Warm Conference (expand on heartland)
   - 1x Quality DIY/Craft (expand on zine/risograph)
   - 1x Modern Luxury (expand on greenpoint concept)

2. **Test new templates** with same voting system
   - Get 15-20 matches minimum per template for confidence
   - Compare against existing winners

3. **Iterate based on data**
   - If new templates fail (<40% win rate), archive them
   - If new templates succeed (>65% win rate), create variations

4. **Build final top 10** for production
   - Focus resources on templates with 70%+ win rates
   - Consider building 2-3 variations of top performers

---

## Conclusion

After 411 user comparisons, the data is clear: **Users want event pages that are professional without being corporate, creative without being gimmicky, and modern without being trendy.**

The winning formula is **"professionally understated"** - templates that balance trustworthiness with personality, clean design with warmth, and sophistication with approachability.

Templates that tried to be thematically interesting (terminal, web1, glitch, deco, maximalist) failed badly. Templates that focused on clarity, warmth, and quality (greenpoint, zine, risograph, heartland, losangeles) dominated.

**The market has spoken: Event organizers want "professional indie" aesthetics.**

---

*Document generated from 411 head-to-head template comparisons collected via voting app.*
*Analysis based on ELO rankings calculated from user preferences.*
*Last updated: November 17, 2025*
