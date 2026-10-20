---
name: Arriaga's Pool & Spa Renovation
description: Pools built to last in PA, NJ & DE. Calm paper and cobalt bands over their own job photo, one brick-red thing to do.
colors:
  navy: "#1b3f78"
  deep-navy: "#0d2140"
  ink: "#0d2140"
  brick: "#ee8a5c"
  brick-hover: "#f4a27c"
  brick-light: "#f6a07a"
  brick-ink: "#a33f14"
  paper: "#f4f6fb"
  card: "#ffffff"
  field: "#e6ecf5"
  body-text: "#2a3a4c"
  soft-text: "#4a5868"
  on-dark: "#f4f7fb"
  on-dark-soft: "#c9d7ea"
  error-red: "#b3261e"
typography:
  display:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(42px, 12vw, 80px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.005em"
  headline:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 7.6vw, 48px)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.005em"
  headline-phone:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 9vw, 52px)"
    fontWeight: 400
    lineHeight: 1
  title-row:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(19px, 5.2vw, 22px)"
    fontWeight: 400
    lineHeight: 1.2
  title-step:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "21px"
    fontWeight: 400
    lineHeight: 1.2
  title-step-desktop:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "22px"
    fontWeight: 400
    lineHeight: 1.2
  numeral:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "20px"
    fontWeight: 400
    lineHeight: 1
  button:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1
  label:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.2
  phone-header:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1
  phone-header-desktop:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "20px"
    fontWeight: 400
    lineHeight: 1
  promise:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.7vw, 20px)"
    fontWeight: 400
    lineHeight: 1.5
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 19px)"
    fontWeight: 400
    lineHeight: 1.7
  who:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(18px, 5vw, 20px)"
    fontWeight: 400
    lineHeight: 1.7
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.7
  input:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.4
  caption:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.7
rounded:
  field: "10px"
  row: "18px"
  link-row: "20px"
  card: "24px"
  pill: "999px"
  circle: "50%"
spacing:
  gutter-narrow: "16px"
  gutter-phone: "20px"
  gutter-desktop: "40px"
  section-phone: "64px"
  section-desktop: "96px"
  column-gap: "64px"
  column-gap-tablet: "40px"
  label-gap: "8px"
  row-gap: "10px"
  actions-gap: "12px"
  stack: "16px"
  hero-stack: "20px"
  field-gap: "22px"
  item-gap: "24px"
  block-gap: "32px"
components:
  button-primary:
    backgroundColor: "{colors.brick}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.brick-hover}"
    textColor: "{colors.ink}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  service-row:
    backgroundColor: "{colors.card}"
    textColor: "{colors.ink}"
    typography: "{typography.title-row}"
    rounded: "{rounded.row}"
    padding: "14px 16px 14px 22px"
    height: "68px"
  feature-row:
    backgroundColor: "{colors.brick}"
    textColor: "{colors.ink}"
    typography: "{typography.title-row}"
    rounded: "{rounded.link-row}"
    padding: "14px 16px 14px 22px"
    height: "76px"
  row-arrow-hover:
    backgroundColor: "{colors.brick}"
    textColor: "{colors.ink}"
    rounded: "{rounded.circle}"
    size: "44px"
  work-photo:
    backgroundColor: "{colors.deep-navy}"
    rounded: "{rounded.card}"
    width: "520px"
  form-card:
    backgroundColor: "{colors.card}"
    textColor: "{colors.ink}"
    rounded: "{rounded.card}"
    padding: "clamp(20px, 5vw, 32px)"
    width: "600px"
  input:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    typography: "{typography.input}"
    rounded: "{rounded.field}"
    padding: "13px 14px"
    height: "52px"
  chip:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.card}"
  step-marker:
    backgroundColor: "{colors.brick}"
    textColor: "{colors.ink}"
    typography: "{typography.numeral}"
    rounded: "{rounded.circle}"
    size: "48px"
  float-text:
    backgroundColor: "{colors.brick}"
    textColor: "{colors.ink}"
    rounded: "{rounded.circle}"
    size: "60px"
  header:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    height: "64px"
---

# Design System: Arriaga's Pool & Spa Renovation

## Overview

**Creative North Star: "Cobalt Tile, Brick Coping"**

The site is built from one real job: a pool and spa mid-renovation, with new cobalt glass tile, red brick coping and the old plaster stripped back. The palette comes straight out of that photo. Glass-tile cobalt and a deep navy are the dark grounds, the brick coping becomes the one warm accent, and off-white paper carries everything in between. The page follows the calm band style (after lpmr.co.uk): full-bleed bands that alternate light and dark, soft rounded white surfaces, pill buttons, and a rounded display face at its single regular weight.

Density is low and the tone is direct. Each band carries one heading, at most one quieter line under it, and one kind of content: four service rows, the job photo, three steps, the form, the phone number. Brick is used as a fill for the thing to do (the primary button, step numerals, the floating text circle, the Facebook row) and, on dark grounds only, for an accent phrase in a heading. The client's own photo is the only image, used twice: cropped on the spa behind the hero under a dark navy overlay, and in full in the work band.

The build rejects the category default (stock pool photo, twelve-icon services grid, invented reviews) and any decoration that competes with the words: no illustrations, no divider shapes, no ambient motion beyond the hero headline's one entrance.

**Key Characteristics:**
- Grounds: paper, cobalt navy (plain), deep navy (with a faint 135° line texture), and the photo hero under a deep overlay.
- Brick as a fill with ink text on it; a light brick for text on dark, a dark brick-ink for glyphs on light.
- Cal Sans at weight 400 for every heading, button, label, row title and phone number; system sans body at 16px/1.7.
- Generous rounding: 24px for the form card and photo, 18–20px for rows, full pills for buttons and chips, 10px fields, circles for markers.
- Flat surfaces; the only shadows belong to the two things that sit above the page (sticky header once scrolled, floating text circle).
- Tap targets 44px minimum, buttons 56px, reading text and inputs 16px or larger.

## Colors

A cool, calm palette lifted from the job photo: off-white paper, two cobalt navies, and a single brick-red warmth.

### Primary
- **Glass-Tile Cobalt** (`navy`): ground of the work band (plain, no texture). Also the focus and hover colour for controls on light grounds (the build's `--focus` role, same hex), the caret in fields, and the hover colour of links in the form's fallback line.
- **Deep Navy** (`deep-navy`): ground of the hero behind its photo, the form band and the footer. The form band and footer carry the line texture (`repeating-linear-gradient(135deg, transparent 0 22px, rgba(255,255,255,.035) 22px 23px)`). Same hex as Ink; the two names mark the ground role and the text role.

### Secondary
- **Brick Coping** (`brick`): fill of the primary button, the step numerals, the floating text circle, the Facebook row, the service-row arrow on hover, and `::selection`. Text and glyphs on it are always ink (6.4:1). Also the focus ring colour on dark grounds.
- **Brick Hover** (`brick-hover`): primary button hover fill and border only.
- **Light Brick** (`brick-light`): brick as text on dark grounds: the accent phrase in a heading on the hero, navy or deep bands (5.0:1 on cobalt), and footer link hover.
- **Brick Ink** (`brick-ink`): brick as a glyph or text on light (5.9:1 on paper): the header and closing phone glyphs, and their hover colour.

### Neutral
- **Paper** (`paper`): page ground, header ground, the services, how-it-works and closing bands, and the `theme-color`.
- **Card** (`card`): white service rows on paper, the form card on deep navy, selected-chip text.
- **Field** (`field`): fill of text fields and chips inside the white form card. It sits only 1.19:1 off white, so a field's edge is carried by its label and its navy hover/focus border, not by the fill.
- **Ink** (`ink`): headings, labels, row titles and step titles on light; text on brick; the selected chip fill.
- **Body Text** (`body-text`): running text on light.
- **Soft Text** (`soft-text`): ledes on light, the closing "Built to last." line, placeholders, the "(optional)" marker, the note under the submit button, the wordmark subline.
- **On-Dark** (`on-dark`): headings, the hero promise, ghost-button label and footer links on dark grounds. The hero H1 itself is pure white.
- **On-Dark Soft** (`on-dark-soft`): running text and ledes on navy and deep.
- **Error Red** (`error-red`): field error border and the 16px error sentence, on the white form card (6.5:1).

Translucent tints are derived, not tokens: the service-row arrow well at rest is ink at 7%, the arrow well on the brick Facebook row is ink at 12%, the ghost border is on-dark at 75%, the ghost hover wash is white at 10%, hairlines are ink at 12%. The hero overlay is a deep navy (`rgba(9,24,48,…)`) at 74–84% top to bottom on phones; from 760px a second, left-weighted layer (62% fading to 0 by 85% width) darkens the side the text sits on so the brick seams never run through the headline.

### Named Rules
**The Brick Is A Fill Rule.** Brick (`#ee8a5c`) is a filled shape with ink on it. It is never text on paper or white (2.5:1); use brick-ink there, and light brick for text on navy or deep.

**The Accent On Dark Rule.** An accent phrase inside a heading is light brick, and only on the hero, navy or deep grounds. Headings on paper stay all ink.

**The Navy Focus Rule.** On light grounds and inside the white form card, hover and focus use cobalt: a 3px ring at a 3px offset (chips 2px offset; the submit button a 2px outline at 2px offset), and text fields switch their 2px border to cobalt instead of taking a ring. On dark grounds the ring turns brick. A brick-filled control never takes a brick ring.

## Typography

**Display Font:** Cal Sans (Google Fonts), falling back to Avenir Next, Segoe UI, system-ui
**Body Font:** system sans stack (-apple-system, BlinkMacSystemFont, "Segoe UI", "Helvetica Neue", Arial, sans-serif)
**Label/Mono Font:** none distinct

**Character:** A rounded, geometric display face at its one regular weight, in sentence case with a hair of negative tracking, beside a plain native body face set loose and readable. Sturdy and friendly, not shouty.

### Hierarchy
- **Display** (`display`): the hero headline only, white, max 11ch on phones and 13ch from 760px; its accent phrase is light brick.
- **Headline** (`headline`): section headings, balanced wrap. The closing phone number runs at `headline-phone`.
- **Title**: service-row and Facebook-row labels (`title-row`), step titles (`title-step`, `title-step-desktop` from 1024px).
- **Button / Label / Phone**: Cal Sans at 18px for buttons, 17px for form labels and legends, 17px (20px from 760px) for the header phone number, 20px for step numerals.
- **Promise / Lede / Who** (system face): the hero promise (max 30ch, 34ch from 760px), the line under a heading (max 38ch), the closing "Built to last." line.
- **Body** (`body`): everything else, including chip labels and error sentences; `input` sets field text at 16px/1.4.
- **Caption** (`caption`, 14px): the "(optional)" marker and the note under the submit button. Never the main message.

### Named Rules
**The One Weight Rule.** Cal Sans is only ever weight 400 and sentence case. Hierarchy comes from size, colour and ground, never from bolding or uppercase. The only bold is 600 in the system face, for the form's fallback status line.

**Eyebrow pills (owner's choice).** Two small labels sit above headings ("Free estimates" in the hero, "Our work" on the cobalt band): 14px/500 system text, a faint tint pill (rgba(13,33,64,.06) on light, rgba(255,255,255,.14) on dark) and a 7px brick dot, no hover, arrow or shadow. Impeccable's craft floor bans eyebrows; Ellie chose them for the calm band style (2026-10-19), so they stay. Use them on the hero and at most a couple of key headings, never on every section.

**The Sixteen Floor Rule.** Reading text, error messages and form inputs are 16px or larger (no iOS zoom). The 14px caption is the only smaller size.

## Layout

A single centred column (max 1160px) with 20px gutters on phones, 16px below 360px and 40px from 760px. Bands are padded 64px top and bottom on phones and 96px from 760px. The hero sets its own padding: 64px top and 76px bottom on phones, 120px / 136px from 760px, with 20px between its lines; it is sized to its content, not to the screen.

Band order: sticky paper header, photo hero under deep navy, paper services, plain cobalt work band, paper how-it-works, textured deep form band, paper close, textured deep footer. Bands meet on straight edges with no dividers.

Breakpoints and what they do:
- **Below 380px:** chip padding tightens from 18px to 14px so chips pack on a line. Below 360px the gutter drops to 16px and the header wordmark and phone shrink so both fit at 320px.
- **From 760px:** hero buttons sit in a row at 240px minimum each (stacked full width with a 12px gap on phones); service rows go to two columns; the work band becomes two columns (heading and Facebook row left, photo right spanning both rows) with a 40px column gap.
- **From 1024px:** the work band's column gap opens to 64px; the form band becomes 1fr / 1.2fr with a 64px gap and the heading block sticking 120px from the top (clearing the header); the steps become three columns with a 40px gap; the closing band sets its text against the big phone number, bottom-aligned with a 48px gap.

Rhythm inside bands: 16px between heading and lede; 32px down to the service rows or the work content, 36px to the steps, 28px to the form; 10px between service rows; 24px between steps; 22px between form fields, 8px from label to field, 12px under a legend. The footer is padded 48px top and 96px plus the bottom safe area below, clearing the float circle.

### Named Rules
**The Number Top-Right Rule.** On the first screen the phone number appears once, as a tap-to-call link in the header's top-right corner. The hero holds at most two buttons (estimate and text) and neither is a Call button. The number returns in the closing band and the footer only.

**The One Circle Rule.** The only fixed element is one 60px brick text circle, bottom-right at 16px plus the safe-area insets. It appears after the hero leaves view and hides while the form is on screen (and is then unfocusable and `aria-hidden`). Never a sticky bottom bar, never a call button.

**The Their Photo Only Rule.** Imagery is the client's own job photo and nothing else. Behind the hero it sits under the deep overlay at whatever darkness keeps white text legible; elsewhere it is a 4:5 card with no caption. Never stock imagery, illustration or a stretched crop (`object-fit: cover` only).

## Elevation & Depth

The page is flat. Rows and the form card lift off their grounds by tone (white on paper, white on deep navy), fields sit into the card by tone, and the deep grounds get a whisper of texture from the 135° lines. Shadows exist only on the two elements that sit above the page while scrolling.

### Shadow Vocabulary
- **Header lift** (`box-shadow: 0 6px 20px rgba(13,33,64,.1)`): the sticky header, added once the hero has scrolled away, faded in over 0.25s.
- **Float** (`box-shadow: 0 10px 28px rgba(8,24,46,.3)`): the floating text circle, because it crosses every ground.

### Named Rules
**The Above-The-Page Only Rule.** A shadow belongs to something that floats over scrolling content (the stuck header, the text circle). Rows, cards, buttons, fields and the photo get tone, never shadow, including on hover.

## Shapes

Soft and generous. The form card and the work photo take 24px corners. Rows are a step tighter: 18px for the white service rows and 20px for the larger brick Facebook row. Buttons and chips are full pills. Text fields use 10px corners. Circles mark three roles: step numerals (48px), the row arrow well (44px) and the floating text circle (60px). Borders are 2px where they appear (button outlines, field and chip borders), transparent at rest so hover and focus never shift layout.

Off-system by design: the 6px corner on focus rings, a softening of the browser outline rather than a surface radius.

## Components

### Buttons
Big, round and thumb-sized.
- **Shape:** pill, 56px minimum height, 26px side padding, 2px border, Cal Sans 18px label, optional 20px line icon with a 10px gap.
- **Primary:** brick fill and border, ink label. Full width inside the form.
- **Hover / Focus:** hover (pointer devices only) lightens to brick-hover over 0.2s. Press scales to 0.98 over 0.12s. Focus is the brick ring on the hero; inside the form card the submit button takes a 2px cobalt outline on hover and focus.
- **Ghost:** transparent with a 2px on-dark border at 75% and an on-dark label. Hover turns the border white and adds a 10% white wash. Used for the hero's second action (Text us), never filled.

### Service Rows
A list of white rows on paper, each one a link to the form that pre-selects the matching chip. Cal Sans label left, a 44px circular arrow well right (ink at 7%, ink arrow).
- **Hover:** only the arrow well changes, filling brick. The row never gets an outline, tint or shadow.
- **Focus:** the row's own ring is suppressed; the arrow well fills brick and takes a 3px cobalt ring at a 3px offset.
- One column on phones, two from 760px. No icons, no descriptions, no carousel.

### Work Photo and Facebook Row
On the cobalt band: the job photo as a 4:5 card (24px corners, max 520px, deep-navy placeholder while loading), then a brick Facebook row (20px corners, 76px minimum height, 28px ink Facebook glyph, Cal Sans label, arrow well at ink 12%). Hover inverts only the arrow well to ink with a brick arrow; focus does the same and adds a 3px white ring.

### Steps
A numbered list on paper. Each item has a 48px brick circle holding a Cal Sans 20px ink numeral (CSS counter), then an ink Cal Sans title and a body-text detail line. Static; no cards, no connectors.

### Inputs / Fields
Inside a white form card (24px corners, 20–32px padding, max 600px) on the textured deep band.
- **Style:** tinted fields: field fill, ink 16px text, 2px transparent border, 10px corners, 13px/14px padding, 52px minimum height (textarea 110px, vertical resize). Labels sit above in Cal Sans 17px; "(optional)" is a 14px soft caption.
- **Hover / Focus:** the border turns cobalt (0.15s). No ring on text fields; the border is the focus.
- **Error:** border turns error red (kept red while focused) and a plain 16px red sentence appears below. Errors clear as soon as the visitor types or picks.

### Chips (form choices)
Radio choices as 48px pills on field fill, 18px padding, 16px ink system text, 2px transparent border.
- **Selected:** ink fill, white label.
- **Hover:** cobalt border. **Focus:** a 3px cobalt outline at a 2px offset (visible on the ink fill too).
- Chips exist only as real form controls.

### Navigation (Header)
A sticky paper bar, 64px tall (76px from 760px), respecting the top safe area, taking the header-lift shadow once the hero is gone. Left: the wordmark lockup (Cal Sans "Arriaga's" over a small uppercase soft-text "Pool & Spa Renovation"). The lockup's sizes (22px, 25px from 760px; 12px/600 subline) are drawing values for the wordmark, kept off the type ramp; the uppercase subline is not a label style to reuse. Right: the phone number as a tap-to-call link in Cal Sans with an 18px brick-ink phone glyph; hover turns it brick-ink. No menu. The footer repeats name, area, number and a Facebook link (44px targets, light brick on hover) on textured deep navy.

### Floating Text Circle
A 60px brick circle with a 26px ink chat glyph, opening a prefilled SMS. It slides up from 120px below the viewport (0.35s, `cubic-bezier(.2,.8,.2,1)`) once the hero is out of view and slides away while the form is visible. Cobalt focus ring, circular.

### Fade-Up
The single scroll motion: elements that start below the first screen rise 12px and fade in over 400ms ease-out as they enter. Everything above the fold is visible at rest; no JS or reduced motion shows everything at once. Smooth scroll is on, off under reduced motion.

### Hero Headline Bounce-In
The hero H1 only: on load, JS splits it into letters inside nowrap word wrappers (keeping the accent span). Each letter slides in from 50px right and fades from 0 over 1s on `cubic-bezier(.34,1.56,.64,1)`, 20ms apart. The H1 carries an `aria-label` with the full text and the letter wrappers are `aria-hidden`; when the last letter lands the plain heading is restored. No JS or reduced motion: the plain heading shows at once. Never on other headings.

## Do's and Don'ts

### Do:
- **Do** alternate paper with cobalt or deep-navy bands and let them meet on a straight edge; the deep form band and footer carry the faint line texture, the cobalt band stays plain.
- **Do** use brick as a fill with ink on it (primary action, step numerals, float circle, Facebook row), light brick for accent text on dark grounds, and brick-ink when brick must be a glyph on light.
- **Do** set every heading, button, label, row title and phone number in Cal Sans at weight 400, sentence case.
- **Do** put the client's own job photo behind the hero under a deep overlay dark enough for white text, and show it again in full as a 24px-cornered card.
- **Do** keep the form in a white 24px card, buttons and chips as full pills, and fields on the field fill with a 10px corner.
- **Do** show hover and focus in cobalt on light grounds and inside the form card, and in brick on dark grounds.
- **Do** put hover styles inside `@media (hover:hover)` so taps don't leave them stuck.
- **Do** keep tap targets at 44px minimum and buttons at 56px, with reading text, errors and inputs at 16px or larger.
- **Do** keep motion to the hero H1 bounce-in, the below-the-fold fade-up, the header lift and the float circle, all off under reduced motion.

### Don't:
- **Don't** set brick (`#ee8a5c`) as text on paper or white, or use it as a focus ring on the white form card.
- **Don't** put an accent phrase in a heading on a paper band.
- **Don't** bold or uppercase Cal Sans.
- **Don't** add a box-shadow to rows, cards, buttons, fields or the photo; shadows are for the stuck header and the float circle only.
- **Don't** show the phone number twice on the first screen, put a Call button in the hero, or add a sticky bottom bar.
- **Don't** use any image other than the client's own photos, or stretch one to fill a shape.
- **Don't** join bands with divider shapes or curves, or let any texture other than the faint deep-navy lines run behind text.
- **Don't** add decorative motion (ambient animation, sheens, parallax, letter reveals on other headings); the hero H1 bounce-in is the one entrance.
