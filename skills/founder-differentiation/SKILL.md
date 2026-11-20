---
name: founder-differentiation
description: >-
  Your differentiation strategist. Applies the Purple Cow doctrine and Eugene
  Schwartz's Breakthrough Advertising (market sophistication stages, the unique
  mechanism, concentration contrast, and concept-judo redefinition) to turn a
  business from one of a hundred brown cows into an unmistakable purple cow that
  competitors cannot copy and buyers cannot ignore. Use when the user says
  "how do I stand out", "how to be different from competitors", "purple cow",
  "differentiation", "unique mechanism", "breakthrough advertising", or
  "why choose me over competitors".
argument-hint: "[competitor or angle]"
---

# founder-differentiation

If you drive down a country road past a pasture with a hundred cows, you stop
looking after thirty seconds. They are all brown, all identical, all invisible.
The other hundred cows are your competitors. If you try to be just a "slightly
better brown cow" (a cleaner shop, friendlier smiles, five percent cheaper), you
are still invisible.

You must be the Purple Cow: something so strikingly different, built into the
core of the product itself, that passers-by stop the car, point, and talk.

This skill combines Seth Godin's *Purple Cow* with Eugene M. Schwartz's classic
*Breakthrough Advertising* to engineer an unfair, durable difference.

## The doctrine

Framework summaries live in `${CLAUDE_SKILL_DIR}/breakthrough.md`:
- The Purple Cow Doctrine (Godin): the brown cow trap, built-in remarkability, sneezers.
- Breakthrough Advertising (Schwartz): 5 stages of market sophistication, the unique mechanism, concentration contrast, and concept-judo redefinition.

## Step 1: survey the pasture

Read `founder/idea.md` and `founder/competitors.md` (and `founder/competitors.csv`).
If competitors have not been mapped yet, run `/founder-competitors` first or list
the 3 to 5 main alternatives the buyer uses today.

Extract:
1. What the category leaders promise (their slogans, claims, and headlines).
2. The common denominator: what do all 100 brown cows have in common?
3. What buyers complain about in competitor reviews (`founder/competitors.md`).

## Step 2: diagnose market sophistication (Stages 1 to 5)

Using Schwartz's 5 stages from `breakthrough.md`, diagnose where this market sits:
- **Stage 1 (Fresh market)**: Direct claim works ("A walk-in matcha cafe").
- **Stage 2 (Early competition)**: Bigger claim needed ("Over 30 matcha varieties").
- **Stage 3 (Crowded pasture)**: Claims are exhausted; buyers are skeptical. You
  MUST introduce a **Unique Mechanism** (HOW it works, not just WHAT it does).
- **Stage 4 (Mechanism arms-race)**: Competitors have mechanisms; you must
  tighten, simplify, or eliminate the flaws of their mechanisms.
- **Stage 5 (Cynical / exhausted market)**: Claims and mechanisms bounce off.
  Direct selling fails. You must win on **Radical Identification and Redefinition**
  (the product defines who the buyer is).

Most new businesses launch into Stage 3, 4, or 5 markets while acting like they
are in Stage 1. Name the exact stage and prove it from competitor ads.

## Step 3: find the "Brown Cow Compromise"

Every mature category has an unwritten dirty secret: a compromise, hidden tax,
or point of friction that all competitors force the buyer to accept as normal.
Examples:
- Standard coffee shops force you to wait in 15-minute lines for a bitter drink.
- Traditional gyms force 12-month lock-in contracts you cannot cancel.
- Mass matcha brands use low-grade culinary powder cut with sugar to mask bitterness.

Identify the single biggest compromise the 100 competitors force on this buyer.
The Purple Cow will be built by refusing this compromise entirely.

## Step 4: engineer the Unique Mechanism

A claim without a mechanism is just noise. The mechanism is the concrete operational,
physical, or procedural reason *why* the business delivers what competitors cannot.

Apply the three-stage rule:
1. **Name the mechanism**: Give it a tangible, memorable name (e.g., "Single-Estate Stone-Ground Chasen Whip", "Zero-Wait Tap Dispense", "No-Contract Flash Pass").
2. **Describe the mechanism**: Explain the actual process in 3 to 4 vivid, plain sentences. How does it physically work? Why does it guarantee results?
3. **Feature the mechanism**: Show how it becomes the centerpiece of the pitch and headline.

## Step 5: concept-judo (Redefinition)

Identify any apparent limitation, high cost, or oddity in the business and flip
it into an asset (like Lifebuoy turning harsh medicinal smell into proof of
antiseptic strength, or Volkswagen turning a small car into an honest virtue).
Examples:
- Only 3 items on the menu? Redefine as "obsessive perfection, zero waste."
- Takes 4 minutes to hand-whisk? Redefine as "ceremonial micro-batch freshness."
- Higher price? Redefine as "first-harvest ceremonial leaves, never filler."

## Step 6: the 1-vs-100 Concentration Table

Build the direct-contrast Concentration matrix (Schwartz Chapter 12):

| Dimension | The 100 Brown Cows (Competitors) | The Purple Cow (Your Business) | Why It Matters to the Buyer |
| --- | --- | --- | --- |
| Core product | ... | ... | ... |
| The hidden compromise | What they make you tolerate | How you eliminate it | ... |
| The mechanism | How they do it (or hide it) | Your named mechanism | ... |
| The experience | Safe, average, invisible | Remarkable, photo-worthy | ... |
| Identity / Role | What buying them says | What choosing you says | ... |

## Step 7: the "Sneezer" test

Who are the sneezers (the obsessed 5% of buyers who will talk about this to
everyone they know)?
1. Name the sneezer persona.
2. The Remarkability Sentence: Write the exact 10-word sentence one customer
   says to another when describing the business at dinner ("Have you seen that
   place that..."). If it sounds like a corporate marketing brochure, rewrite it
   until it sounds like a human being.

## Rules

- Never settle for "we have better customer service" or "we care more." Those
  are brown cow claims; every competitor claims them.
- The difference must be verifiable by the customer within 30 seconds of
  contact.
- Ground claims in facts from `founder/competitors.md`.
- No em-dashes anywhere in the text (use double hyphens -- or colons).

## Output

Write `founder/differentiation.md` containing:
1. Market Sophistication diagnosis (with evidence from competitors).
2. The Brown Cow Compromise.
3. The Unique Mechanism (Name, Description, and Proof).
4. The Concept-Judo Flip.
5. The 1-vs-100 Concentration Table.
6. The Sneezer Profile and 10-word Remarkability Sentence.

Next in the pack:
- `/founder-consumer`: inject the Purple Cow pitch into `founder/pitch.md` to see
  if the 100 simulated buyers stop and buy or call it a gimmick.
- `/founder-marketing`: turn the Unique Mechanism and Concentration Table into the
  first ten launch hooks.
