# STACK: Narrow Lane

A minimalist arcade stacking game built as a constraint experiment.

One lane.  
One stack.  
Counterbalance to climb.

---

## Play

**Controls**
- Move base: Mouse / A–D / ← →
- Fast drop: Space / Click
- Bank score: S
- Reset: R
- Pause: P

The goal is simple: stack falling blocks as high as possible inside a narrow lane.
Bad placements tilt the tower.
Good counterbalances restore stability.

Mistakes can be corrected — but only if you read the structure.

---

## Design Intent

STACK: Narrow Lane was designed under strict limitations:

- Single HTML file
- No external libraries
- One core mechanic
- No progression systems
- No content unlocks
- No audiovisual excess

The challenge was not to add features, but to **remove everything unnecessary** while keeping tension, fairness, and replayability.

This project draws inspiration from:
- Classic arcade clarity
- Amiga / demo-scene restraint
- Modern minimalist UI design

---

## Mechanics Overview

- **Narrow Lane**  
  Movement is deliberately constrained to emphasize precision over speed.

- **Tilt & Stability**  
  Each block affects the tower’s balance. Too much tilt ends the run.

- **Counterbalance Bonus**  
  Landing opposing off-center blocks in sequence stabilizes the tower,
  rewarding intentional correction rather than perfection.

- **Banking**  
  Players may bank their run score at any time to secure progress,
  trading risk for safety.

---

## Scoring

- **Run** — score accumulated during the current stack
- **Bank** — secured score from previous runs
- **Height** — highest block reached
- Best scores are saved locally via `localStorage`

---

## Files

- `stack.html` — the entire game (HTML + CSS + JS)

No build step.  
No dependencies.  
Open the file and play.

---

## Status

**Version:** 1.0  
This release is considered complete.

Future visual or mechanical experiments (2D polish, 3D reinterpretations)
will live in separate prototypes to preserve the integrity of v1.

---

## License

MIT  
Do whatever you want. Attribution appreciated, not required.

---

## Credits

Design & implementation: MK  
Conceptual collaboration: iterative constraint-based exploration

# STACK: Narrow Lane

A minimalist arcade stacking game built as a constraint experiment.

One lane.  
One stack.  
Counterbalance to climb.

---

## Play

**Controls**
- Move base: Mouse / A–D / ← →
- Fast drop: Space / Click
- Bank score: S
- Reset: R
- Pause: P

The goal is simple: stack falling blocks as high as possible inside a narrow lane.
Bad placements tilt the tower.
Good counterbalances restore stability.

Mistakes can be corrected — but only if you read the structure.

---

## Design Intent

STACK: Narrow Lane was designed under strict limitations:

- Single HTML file
- No external libraries
- One core mechanic
- No progression systems
- No content unlocks
- No audiovisual excess

The challenge was not to add features, but to **remove everything unnecessary** while keeping tension, fairness, and replayability.

This project draws inspiration from:
- Classic arcade clarity
- Amiga / demo-scene restraint
- Modern minimalist UI design

---

## Mechanics Overview

- **Narrow Lane**  
  Movement is deliberately constrained to emphasize precision over speed.

- **Tilt & Stability**  
  Each block affects the tower’s balance. Too much tilt ends the run.

- **Counterbalance Bonus**  
  Landing opposing off-center blocks in sequence stabilizes the tower,
  rewarding intentional correction rather than perfection.

- **Banking**  
  Players may bank their run score at any time to secure progress,
  trading risk for safety.

---

## Scoring

- **Run** — score accumulated during the current stack
- **Bank** — secured score from previous runs
- **Height** — highest block reached
- Best scores are saved locally via `localStorage`

---

## Files

- `stack.html` — the entire game (HTML + CSS + JS)

No build step.  
No dependencies.  
Open the file and play.

---

## Status

**Version:** 1.0  
This release is considered complete.

Future visual or mechanical experiments (2D polish, 3D reinterpretations)
will live in separate prototypes to preserve the integrity of v1.

---

## License

MIT  
Do whatever you want. Attribution appreciated, not required.

---

## Credits

Design & implementation: MK  
Conceptual collaboration: iterative constraint-based exploration

