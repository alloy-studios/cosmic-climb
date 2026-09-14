# cosmic-climb

## Cosmic Climb — v2.0

A complete rebuild. Same 3,000m climb, almost nothing else is the same.

### New art direction
- Rebuilt the whole look as a **risograph screenprint**: flat spot inks, visible
  plate misregistration, halftone dot screens, paper grain and corner trim marks.
  Replaces the old pastel gradients and frosted-glass UI.
- Each of the 8 altitude bands is now its own "print run" with a distinct two-ink
  palette. The Void inverts entirely — black stock, cream ink.
- New parallax backdrop: ringed gas giants, halftone nebula tints, a black hole,
  drifting registration marks and cirrus streaks.
- Redesigned player with a tapered motion trail, squash-and-stretch, and lean.

### New gameplay
- **Air dash** — directional, refills on landing or stardust, and *shatters
  debris* you dash through.
- **The Collapse** — a rising tide of black ink now chases you up the page,
  replacing the old static death line. Standing still is fatal.
- **Stardust → Chain → Surge** — collect dust to build a chain multiplier and
  charge Surge, a launch that shoves the ink back down the sheet.
- **Six platform types**: solid slabs, drifting, crumbling, phasing, launch
  kickers, and realm gates.
- **Hazards**: tumbling debris and telegraphed pulsar sweeps in the upper realms.
- **Realm gates** print a band across the sky, pay out score and push the ink back.
- Variable jump height (hold to go higher), coyote time and input buffering.

### New audio
- Full procedural soundtrack and SFX via WebAudio — no audio files. Per-realm
  drone bed and a low rumble that rises as the ink closes in.

### New interface
- Printed instrument panels: altitude, score, dust, flow meter, dash pips, chain.
- Vertical altimeter tape showing your position, the ink, and every realm band.
- Redesigned title, pause and run-summary cards with full run stats.
- Rebuilt touch controls and a mobile layout.

### Fixes
- Falling fast no longer drops you straight through platforms.
- Altitude is now resolution-independent (it used to scale with window height).
- The launch field has an actual floor instead of a bottomless pit.
