# Arriaga's Pool & Spa Renovation — handoff at ~60%

**Live:** https://10elizabethbell.github.io/arriagasPool/ · **Repo:** https://github.com/10elizabethbell/arriagasPool · **Built:** 2026-10-20 from Muse brief of 2026-10-20 (group ad post of 2026-10-19) · **Call Sheet:** site set

## What's built
- Single `index.html` in the calm band style, phone first. Sections: sticky paper header (wordmark, tap-to-call 215-768-5602 top right) → photo hero → What we fix (4 service rows) → Built to last (their job photo + Facebook link) → How it works (3 steps) → free-estimate form (deep navy) → close with big phone number and service area → footer.
- Palette from their own job photo, since there's no logo: paper `#f4f6fb`, glass-tile cobalt `#1b3f78`, deep navy `#0d2140`, brick-coping accent `#ee8a5c` (fill only, navy text on it; `#a33f14` when it's text on light, `#f6a07a` on navy).
- Hero: their spa/pool job photo (cropped for phone and desktop separately, boots at the bottom cropped out) under a navy overlay; white and accent text sampled against the brightest pixel behind them at 8:1+ on phone and 11:1+ on desktop. H1 "Pools built to last in PA, NJ & DE." bounces in letter by letter, then restores to the plain heading.
- Contact: header `tel:` link; hero buttons "Get a free estimate" (to the form) and "Text us" (pre-written `sms:`). Service rows pre-select their chip in the form. The form (service, name, optional town and details) composes a text; if nothing opens it shows the number. Floating text circle appears after the hero and hides over the form.
- Favicon / touch icon: an "A" in Cal Sans on cobalt with a brick bar (no logo exists). `og.jpg` 1200×630 for the Facebook preview.

## Assumptions I made
- **Name styling:** brief has "Arriaga's Pool & spa renovation"; I title-cased it to "Arriaga's Pool & Spa Renovation". Confirm spelling.
- **"We" voice:** renovation work suggests a crew; the brief only names a posting profile, "Arriaga's Solis".
- **Colours** come from the photo (cobalt tile, brick coping), not a brand. A gold accent is the obvious alternative if the owner has a truck/shirt colour.
- **Texting:** brief says "Accepts texts: unknown". The form and circle hand off by text; the phone number is always one tap away in the header. If they don't text, switch the form to show the number/call.
- **Copy** I wrote in their voice: the hero line adapts their own caption ("Small pool problems today can become expensive repairs tomorrow"); "Built to last." is their sign-off. The Built-to-last paragraph and how-it-works step 2 ("what it needs and what it costs, straight") are mine; step 2 assumes they come out to look before quoting.
- Placeholder town in the form ("e.g. Cherry Hill, NJ") is just an example town in their area.

## Placeholders and gaps
- **Facebook:** no business page found. Both Facebook links point to the group post where they advertised (it opens logged-out, but it's one post, not a page). Swap in their page/profile URL.
- **One photo only.** It appears twice (hero crop, full shot in the work section). More job photos, especially before/afters, would make the work section a real gallery.
- No email (footer has none), no hours, no reviews, no prices, no years in business, no insurance/licence. Nothing claimed on the page.
- "End-of-season specials" isn't on the page: the brief has no details, and it would date the site by spring.

## Questions for the owner
- Exact business name and how you'd like it written? Your first name, to put on the page?
- Do you take texts at 215-768-5602?
- Your Facebook page link? Email for the footer?
- More photos: finished pools, before/afters, decks.
- Which towns/counties do you cover most? Any warranty, insurance, years in business you want shown?
- Details of the end-of-season specials, if you want them on the site this fall.

## Impeccable sweep (done 2026-10-20)
Ran the finish reviewer plus every mode except live (critique, audit, polish, harden, clarify, adapt, optimize, typeset, layout, distill, quieter, bolder, colorize, animate, delight, extract; onboard/overdrive don't apply). Applied: hero overlay darkened (left-weighted on desktop) so brick seams no longer run through the headline; "Built to last" cut from 4 places to the H1 and close; work heading now "Done right the first time."; throwaway first sentence cut; Facebook button honestly says "See this job on Facebook."; form fallback now offers Open in Messages / copy message / call; radio errors announced to screen readers; quieter error state; 320px header fits; work photo re-exported sharp at 2x; tablet two-column work band; curly quotes; small type sizes consolidated; no-JS line in the form.
Not applied: dropping the phone number from the footer (house rule: footer keeps it); making the step-number circles neutral (kept the DPG reference's accent fill; easy swap: `.steps li::before{background:rgba(13,33,64,.07)}`).
Detector ignores saved in `.impeccable/config.json`: band texture (your calm style), flat-type-hierarchy (false positive; it skips the clamp() headings).

## Ideas not built (yours to pick)
- **Impeccable flags these as anti-patterns; kept because you chose them:** eyebrow pills, the H1 letter bounce (elastic easing), the floating text circle (it can cover the last ~56px of right-edge text while scrolling), Cal Sans, the diagonal band texture.
- **Signature motion (opt-in), best world:** a still water surface along the hero's bottom edge that ripples under the finger. Runners-up: glass mosaic tiles that settle into a waterline row as you scroll; brick coping laid stone by stone around the form; fresh plaster troweled smooth by a drag.
- Before/after sliders once pairs exist.
- A seasonal ribbon for the end-of-season specials (Oct–Nov only).

## Not verified
- Whether 215-768-5602 takes texts: three controls (Text us, the form, the circle) depend on it. Confirm before handing over.
- Real-device touch, and the `sms:` handoff on real iOS/Android and inside Facebook's in-app browser.
- Whether the Facebook group post stays viewable without logging in.
