# Plumb: case study (self-initiated concept)

Plumb is a fictional product invented for this portfolio piece. There is no client, no real data, and no metrics or awards are claimed.

## Problem
Pro-grade levels are heavy and fussy; phone apps are convenient but imprecise and need your hand to be steady. The brief to myself: sell a small laser level to DIYers and renters, and make a technical, trust-based purchase feel light rather than intimidating.

## Positioning
"Every line, dead level." A tool that checks its own work. The promise is confidence, not features: the beam blinks rather than lie, and the phone is a second opinion. The audience is people whose eye is better than their level.

## Design decisions
- **Light and airy, not "tool-bro".** Hardware pages default to black and orange. A cool paper ground, generous whitespace and one-pixel hairlines signal precision and calm.
- **The grid is the brand.** Faint 12-column hairlines run behind the hero, echoing graph paper and a ruler. All sections snap to the same 12 columns.
- **One hot accent, used as a graphic.** Beam orange (3.3:1 on white) is never used for text; the readable variant is a separate token at 5.7:1.
- **Hard-offset shadows** (the device, frames, card hover) are a playful, flat-geometric device that also reads as "object on a wall".
- **Honest numbers.** The accuracy chart is plain geometry (error = distance x tan angle) and labelled illustrative.
- **Mobile is a re-composition, not a shrink.** Hero stacks with full-width actions, the spec strip becomes 2x2, bento tiles become a single column, pricing cards stack with the featured kit in the middle.

## System
Tokens: ink, slate, graphite, cobalt (interaction), beam, lime, sky, paper, mist. Type scale 100/76/52/30/21 display to heading, 17 body, 12 mono labels. Radii 10/18/28/36/pill, spacing in 8px steps, 128px section rhythm. Components: primary, secondary, quiet and on-dark buttons; inputs with hover, focus, error, success, disabled; chips, tags, segmented control; step, tile and plan cards. Focus is always a 3px paper gap plus a 3px cobalt ring. All text pairs checked against 4.5:1 (see the style sheet for ratios).

## What I would test
- Whether the hero line plus a spec strip is enough, or buyers need a short demo loop above the fold.
- Whether showing the drift chart on the product page raises or lowers confidence compared with a plain spec line.
- Kit vs One as the featured plan, and whether "Our pick for DIY" beats a neutral label.
- Mobile pricing: stacked cards vs a swipeable comparison.
- Keyboard and screen-reader pass on the FAQ and segmented control.
