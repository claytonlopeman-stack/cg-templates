# C&G Scaling — Service Business Template Library

## Project
Building 5 distinct, non-generic website templates for the most common
service businesses in Oklahoma. These become reusable, sellable starting
points for C&G Scaling client sites — not one-off throwaway pages.

## The 5 templates (one folder each)
1. plumbing/
2. hvac/
3. roofing/ — storm damage / restoration angle (big category in OK)
4. pest-control/
5. powerwashing/ — use cngsolutions.org content/tone as a starting
   reference for real copy and photos, but do not copy it verbatim;
   adapt and improve it as a template, not a clone of the live site.

## Hard rule: no two templates may share a layout skeleton
The generic AI-site tell is: centered hero, 3 icon cards, testimonial
carousel, footer, repeated regardless of industry. Never reuse the same
section order, hero style, or component structure across these 5
templates. Each one needs its own structural logic:
- plumbing — clean, trust-forward, strong emergency-call CTA near the top
- hvac — seasonal urgency (heat/cold), before/after comfort framing
- roofing — bold, high-contrast, storm-damage narrative front and center
- pest-control — lighter, friendlier, more "in your home" tone
- powerwashing — transformation-forward, before/after imagery as the hero

Each template also gets its own type pairing and color palette. Do not
share a theme/style file across templates.

## Copy tone
Avoid generic AI marketing language ("revolutionize," "cutting-edge,"
"unparalleled service"). Write like a real local Oklahoma business
talking to a neighbor, not an ad agency.

## MANDATORY: self-check before presenting any finished work
Before reporting a template as done, run through this checklist and fix
anything that fails yourself, don't just report the failure back and stop:
- Does this share a layout/section order with a template already built
  in this repo? If yes, restructure it.
- Does the color palette or font pairing match another template already
  built in this repo? If yes, change it.
- Any leftover Lorem Ipsum, placeholder text, or broken links/images?
- Does the copy sound like generic AI marketing language? If yes, rewrite it.
- Does it actually render correctly, including at mobile width? Preview
  with npx serve and look, don't assume it works.
- Any errors in the browser console?

Only say a template is finished after every item above is checked and
fixed. If something fails, fix it silently before responding, don't
present broken or unfinished work and ask whether to fix it.

## Workflow
- One template at a time, fully finished (including the self-check
  above) before starting the next.
- After a template passes self-check: git add, git commit, git push
  before moving to the next template.
