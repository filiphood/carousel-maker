# Filip's Brand & Carousel Style Guide

This is the design system for **@filiphood** on Instagram — the visual + editorial rules that keep my carousels feeling like mine. Captured from the carousel-maker tool and the "Time to Build" content pillars.

**Use it as:**
- A cheat sheet when starting a new carousel
- A brief for future Claude sessions (see [§ For an AI assistant](#for-an-ai-assistant) at the bottom)
- A reminder when I'm tempted to chase a trendy style that doesn't fit

Rules here are defaults, not prison bars. 80 % fidelity = strong brand. 100 % fidelity = brittle and boring. Break any rule if the post is better for it.

---

## 1. Who it's for

- **Primary audience:** solo builders, indie devs, AI-curious creators in their 30s thinking about escaping 9-to-5
- **Secondary audience:** photographers and videographers rediscovering themselves as builders (my own past)
- **Tertiary:** anyone who likes a grounded take on AI, carrying something too heavy, or the creative kid inside them

## 2. Voice & tone

- **Honest over polished.** Share the middle, not just the summit.
- **Specific over generic.** "Six continents" beats "traveled a lot". "$2,024" beats "some revenue".
- **Short sentences.** One idea per sentence. Let line breaks do the lifting.
- **Emotional payoffs.** Every carousel earns the last slide by being vulnerable before it.
- **No guru speak.** No "10× your X". No "rise and grind". No "let me show you the secret".
- **"AI is not the goal — shipping is"** energy. Grounded, not hyped.
- **Repeat motifs.** The "something too heavy" image, the "fifteen-year-old kid building HTML sites", the "creative kid never went anywhere" callbacks. These are mine — use them when true.

## 3. Color palette

Always reference by hex. Not by name. Themes in the carousel-maker hold these.

| Role | Hex | Notes |
|---|---|---|
| **Paper** (default cream) | `#f2ede3` | Warmer than white, softer than beige. The home base. |
| **Ink** (default text) | `#111111` | Near-black. Real black (`#000`) feels too digital. |
| **Warm accent** (dots / grid) | `#5c4820` | A deep warm brown. Used at ~12–22 % opacity for patterns. |
| **Light ink** (on photo / dark bg) | `#f6f3ec` | Slightly warm off-white. Use with Black minimal or Dark green themes. |
| **Black background** | `#0e0e0e` | Black minimal theme. For photo-heavy or cinematic slides. |
| **Dark green** | `#0d2a22` | Deep forest. Used for nature/build-log carousels. |
| **Light ink on green** | `#f1ead6` | Warm cream text on dark green. |

**Do not:** introduce new colors per carousel. Pick from this palette or extend the theme library intentionally.

## 4. Typography

Two voices, always paired:

### 4.1 Display voice — Inter Black (900)
- **Google Fonts:** `family=Inter:wght@900`
- Used for: headlines, punch lines, tool names, emotional anchors (`stay.`)
- Always weight 900 (Black). Never regular Inter.
- Tracking: `letter-spacing: -0.045em` (tight).
- Line-height: `0.98` for multi-line headlines, `0.9` for hero CTAs like "stay."
- Sizes: 92px (info title) → 108px (text headline) → 132px (cover) → 280px (CTA hero). Scale fluidly with Instagram 1080 × 1350.

### 4.2 Soft voice — Apple Garamond italic
- **Font stack:** `'Apple Garamond', 'ITC Garamond Std', 'Garamond', 'Hoefler Text', 'Times New Roman', serif`
- Used for: subtitles, lead-ins, quotes, the "why" line on CTAs
- Always italic. Apple Garamond regular is only for long-form info body text.
- Tracking: `letter-spacing: -0.005em`
- Line-height: `1.18`
- Size: 44–54px next to a 108px Inter Black headline.

### 4.3 Editorial body — Apple Garamond regular
- Same font stack, `font-style: normal`, `font-weight: 400`
- Used for: the **Info** slide template body (multi-paragraph tool reviews, explainers)
- Size 36–40px, line-height `1.42`, paragraphs separated by one blank line
- Never use for display — reads as weak.

### 4.4 UI voice — Inter Black small-caps
- Footer handle + page number (`@filiphood 01 / 08`)
- Size 18px, letter-spacing `0.18em`, uppercase, `color: rgba(ink, 0.5)` or similar
- Tiny and confident. Not loud.

## 5. Patterns

The **bullet-journal dot grid** is the signature texture. It reads as "notebook / builder / in progress" — which is the whole brand.

Defaults (`Cream + Dots` theme):
- Dot color: `#5c4820` at 22 % opacity
- Dot size: `1.6px`
- Dot spacing: `28px`

### Pattern variants (pick one per theme, not one per slide)

| Variant | Use for |
|---|---|
| **Dots** (plain) | Default narrative carousels |
| **Dots + layered (size accent)** | When you want rhythm — accent dot every 3rd cell, 2.6× larger |
| **Dots + intensity accent** | Same rhythm but via brightness instead of size. Subtler. |
| **Radial hotspot** | Draws focus to a center point. Use sparingly (1 slide per carousel) |
| **Linear band** | Diagonal or vertical band of emphasis — signals transition or tension |
| **Graph grid** | Info / editorial slides (`Cream + Grid` theme), 44px cells, 14% opacity |
| **Plain** | When content is already busy (photo + texture) — no pattern |

**Rule of thumb:** dots on narrative slides, grid on info slides, plain on photo slides.

## 6. Slide templates

Eight types in the carousel-maker. Use the right one.

### Cover (photo cover)
- **When:** slide 1 of most carousels
- **Structure:** full-bleed photo, short 1–3-line headline at bottom, circle mark top-left, page number + handle at the bottom
- **Tip:** use a moody photo with grayscale filter and 15–25 % dim for text legibility

### Text
- **When:** narrative, quote, or emotional beat — most slides in a Shift-style carousel
- **Structure:** one Inter Black headline + one Apple Garamond italic line (order: italic above OR below the headline)
- **Max:** 2 sentences total per slide. If more, split into two slides.

### CTA (3-line)
- **When:** the emotional climax — the last slide (or occasionally second-to-last)
- **Structure:** small italic lead-in → huge centered Inter Black word or phrase → small italic "why" below
- **Example:** *"If you're still carrying something too heavy —"* / **stay.** / *"I'll show you what putting it down actually looks like."*

### Info (editorial)
- **When:** explanatory posts, tool reviews, tutorials — anything with 3+ short paragraphs
- **Structure:** Inter Black title (often ALL CAPS) → optional italic subtitle → Apple Garamond regular body in 3–5 short paragraphs
- **Alignment:** always left
- **Tip:** pair with `Cream + Grid` theme for a "field notes" feel

### Screenshot
- **When:** showing a file, a UI, a tool, anything captured as an image
- **Structure:** **tag** (STEP 1, WHAT I BUILT, etc. — small caps, warm accent) → Inter Black headline → uploaded image (rounded, soft shadow) → italic caption
- **All fields editable from the sidebar** — the image is uploaded once, the rest is text
- **Tip:** pair with `Cream + Dots` theme; leave caption under ~10 words

### Prompt
- **When:** quoting a prompt, showing config, showing a few lines of "input"
- **Structure:** tag → Inter Black headline → monospace prompt box (SF Mono / Menlo, pre-wrap) → italic caption
- **Prompt is a plain text field** — type any prompt, any length; line breaks and indentation preserved
- **Tip:** aim for 6–10 lines of prompt copy; longer gets cramped at 1080×1350

### Comparison
- **When:** before/after, two tools, two approaches side-by-side
- **Structure:** tag → Inter Black headline → 2-column image grid (each with an optional label underneath) → italic caption
- **Two separate file uploads** (Image A / Image B); labels default to BEFORE / AFTER but are editable

### List
- **When:** "5 things I learned", "7 rules I follow", short numbered lessons
- **Structure:** tag (optional) → Inter Black headline → numbered items (Inter Black number + Apple Garamond italic text) → italic caption
- **Items field:** one item per line in the textarea — numbers are generated automatically
- **Tip:** 3–6 items max; each under 60 characters so lines don't wrap

## 7. Photo treatment

Any slide can have a full-bleed photo. Photos replace the dot/grid pattern.

### 7.1 Textures (overlay on photo)

| Texture | Character | Best on |
|---|---|---|
| **Grain** | Fine film noise | Moody/dark photos, vintage mood |
| **Paper** | Horizontal fibers, linen look | Faded/grayscale photos, editorial feel |
| **Canvas** | Cross-hatched weave | Painterly, heavier textured look |

Default texture opacity: **50–70 %**. Above 80 % starts fighting the photo.

### 7.2 Filters (on the photo itself)

| Filter | Effect |
|---|---|
| Grayscale | Strips color. Defaults to this for mood carousels. |
| Sepia | Warm vintage. Use sparingly. |
| Faded | Lower contrast, slight desaturation. "Memory" feel. |
| Dim | Brightness × 0.6. For extra text legibility. |

### 7.3 Localized blur

A region of the photo blurred while the rest stays sharp. Subtle but distinctive.

- **Radial hotspot:** circular blur around a chosen point
- **Linear band:** blurred strip at any angle

Typical settings: blur amount 20–35px, falloff 40–60 %. Don't over-blur — it should feel like motion or focus, not damage.

### 7.4 Photo sourcing

- Shoot your own whenever possible (the photographer in me approves)
- If licensed: Unsplash / Pexels only, never paid stock that looks like stock
- Prefer: landscapes, textures, hands, desks, architectural
- Avoid: faces that aren't mine, obvious stock setups, AI-generated people

## 8. Composition rules

- **Mark circle** (top-left, 28px, 3px stroke, same color as ink) — always present
- **Footer** (bottom) — `@filiphood` left-aligned, `XX / YY` page number right-aligned, all caps, 18px Inter Black with 0.18em tracking
- **Swipe hint** (`swipe →` top-right) — slides 1 through N-1, hidden on the last
- **Left-aligned** for narrative, context, info
- **Centered** for CTAs and covers
- **Breathing room:** at least 120–140px padding around content
- **Paragraphs on info slides:** one blank line between paragraphs (parsed as `\n\s*\n`)

## 9. Content pillars → visual conventions

My three pillars (from the Notion Brand Hub) have soft visual identities:

### Build Logs (green)
- Feels: in-progress, documented, honest
- Themes: `Cream + Dots`, `Cream + Layered dots`, occasional `Black minimal` for launch reveals
- Templates: mostly Text + occasional Cover (photo of what I'm shipping) + CTA

### AI Toolkit (purple)
- Feels: explanatory, calm, field notes
- Themes: `Cream + Grid` (dominant), `Cream (plain)` for very content-heavy
- Templates: Info (dominant), CTA to close, optional Cover

### Takes & POV (orange)
- Feels: voice-forward, opinionated, book-quote-ish
- Themes: `Cream + Intensity dots`, `Cream + Radial hotspot`, occasional `Dark green`
- Templates: Text (dominant), CTA for the mic-drop, photo covers for quote reveals

## 10. Writing rules per template

**Text slide — max 30 words total across headline + soft.** If longer, split.

**Info slide — max 80 words per slide.** Three paragraphs ideal. Four is maximum.

**CTA slide — 3 lines, each under 8 words.** Hero word is ideally 1–2 syllables.

**Cover slide — headline under 10 words.** Should read as a hook you'd stop scrolling for.

## 11. Do / Don't cheat sheet

### Do
- Break text across 2–3 lines in headlines to control rhythm
- Use em-dashes ( — ) freely in italic lines. They're the signature beat.
- Let the cream paper breathe. Empty space is a design element.
- Repeat motifs across carousels (the "kid building HTML sites", the "too heavy", "AI is not the goal")
- Shift between Shift-style (emotional) and Info-style (explanatory) carousels
- Reuse icons: the circle mark is non-negotiable

### Don't
- Use gradient fills for text. Never.
- Use more than 2 type weights on one slide (Inter 900 + Garamond italic/regular)
- Add drop shadows to text. If you need one, your contrast is wrong — fix the bg.
- Use pure `#000` or pure `#fff` — stick to the warm ink / light ink above
- Bold random words in body copy. If it matters, it's the headline.
- Use emoji unless the post is specifically meme / cultural commentary
- Copy Canva-template aesthetics — they read as generic

## 12. Quick-start recipes

### Shift-style narrative (7–9 slides)
1. **Cover** with moody photo + grayscale + dim → short punch headline
2. **Text** slides 2–5 with italic lead-in above or below a punchy Inter Black line — build the arc
3. **Text** slide with the realization / turn
4. **Text** slide with the COVID / turning-point hook
5. **Text** callback to childhood / origin story
6. **CTA** with small lead → hero word → italic "why"
- Theme: `Cream + Dots` or `Cream + Layered dots`
- Tone: vulnerable, specific, em-dashes

### Tool review (4–6 slides)
1. **Cover** with title like "Tools I use to [X] in [YEAR]"
2–4. **Info** slides, one per tool — ALL CAPS title + italic subtitle + 3-paragraph body
5. **CTA** with ask like "reply." / "Drop a tool name in the comments"
- Theme: `Cream + Grid`
- Tone: calm, concrete, no hype

### Book-quote / Takes & POV (4–6 slides)
1. **Cover** with moody photo of book, hands, or reading setup
2. **Text** slide with the quote itself — Garamond italic only, larger size
3. **Text** slide with one-line reaction
4. **Text** slide with a concrete application (builder lens — what it means for shipping / identity / work)
5. **CTA** with invitation ("who said it first?" / "what's yours?")
- Theme: `Cream + Intensity dots` or `Cream + Radial hotspot`
- Tone: reflective, not preachy

### Dune-style AI-news commentary (3–4 slides)
1. **Cover** — striking photo + hook ("X is set 20,000 years in the future. There's not a single computer.")
2. **Info** — context in 2–3 paragraphs
3. **Text** — the punchline quote (Garamond italic for the Herbert line)
4. **CTA** — tie-back to the present day

---

## For an AI assistant

If you're Claude (or any model) helping me make a carousel in a future session, here's what you need to know:

1. **My tool is `carousel-maker`** — a single-file HTML editor at https://filiphood.github.io/carousel-maker/, repo at https://github.com/filiphood/carousel-maker. It uses localStorage so my saved themes + carousels are already in my browser.
2. **My handle is `@filiphood`.** Always include it in the footer.
3. **My voice is honest, vulnerable, specific.** Err on the side of "real" over "polished". Em-dashes are a trademark.
4. **My typography is Inter Black + Apple Garamond italic** — paired on every slide. Never use other fonts.
5. **My palette is the cream + warm ink system above** — `#f2ede3` / `#111111` / `#5c4820`. Don't introduce new colors without asking.
6. **Four slide templates:** Cover (photo), Text (narrative), CTA (3-line climax), Info (editorial). Pick based on the request's shape.
7. **My three content pillars** are Build Logs, AI Toolkit, Takes & POV. Each maps loosely to a template + theme pairing (see § 9).
8. **Short copy wins.** Cap at 2 sentences per Text slide, 4 paragraphs per Info slide.
9. **If the user gives you a story,** break it into 7–9 slides with an emotional arc: hook → context → turn → vulnerable middle → callback → announcement → CTA.
10. **If the user gives you a tool to review,** use the Info template, ALL CAPS title, 3-paragraph body, close with a CTA.
11. **Always end with a payoff slide** (CTA) — never leave the viewer hanging on the penultimate beat.
12. **Default to the recipes in § 12** unless the request is clearly different.
13. **When asked for "a different style"** — reach for the pattern variants (radial, band, grid) or the photo+texture system before inventing anything new. Every option you need is already in the system.

The goal: I should be able to send you a story or topic and get back slide-by-slide copy + recommended theme + template, all within this system, in under 2 minutes.

---

*Last updated: carousel-maker v2 (after radial hotspots, linear bands, photo textures, localized blur). Bump this file when the system changes meaningfully.*
