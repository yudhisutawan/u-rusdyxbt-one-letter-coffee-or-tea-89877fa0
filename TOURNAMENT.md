# Tournament — One Letter: Coffee or Tea

Method (per `win-gap-playbook.md`): every candidate pair judged
head-to-head with the competition's own judge brief, in both slot
orders, margin 1–5, no ties. Candidates: A (coffee, upper), B (tea,
upper), a (coffee, lower), b (tea, lower), C (junk control — names
neither drink). 10 pairs x 2 orders = 20 calls. The builder (Muse Spark)
judged all pairs; Hermes (VPS, my-combo Mixture of Agents, independent
models) cross-checked the same 8 pairs with the same brief. Full
candidate reasoning: `CANDIDATES.md`.

## Builder's games (Muse Spark, competition brief)

| Pair | Order 1 | Order 2 | Winner | Margin | Deciding criterion |
|------|---------|---------|--------|--------|--------------------|
| A vs B | A | A | **A** | 3 | 2+3+4: coffee is more vivid, funnier, blunter/truer than tea; A also first letter |
| A vs a | A | A | **A** | 1 | 5 only: same drink, same vivid/funny/true; uppercase is the cleaner, unmistakable form |
| B vs b | B | B | **B** | 1 | 5 only: same drink; uppercase is the cleaner form |
| a vs B | a | a | **a** | 2 | 2+3+4 (coffee over tea) outweigh 5 (B's uppercase form) |
| b vs A | A | A | **A** | 3 | 2+3+4 (coffee) plus 5 (uppercase form) |
| a vs b | a | a | **a** | 3 | 2+3+4: coffee over tea, both lowercase so form ties |
| A vs C | A | A | **A** | 5 | 1: C names neither drink, loses outright |
| B vs C | B | B | **B** | 5 | 1: C names neither drink, loses outright |
| a vs C | a | a | **a** | 4 | 1 (lenient reading): "a" names coffee, C names nothing |
| b vs C | b | b | **b** | 4 | 1 (lenient reading): "b" names tea, C names nothing |

Game scores (mean of the two calls; a call gives the winner
0.5 + margin/10): A 0.81, a 0.69, B 0.53, b 0.40, C 0.05.

Standings by pairwise strength: **1. A (4-0), 2. a (3-1), 3. B (2-2),
4. b (1-3), 5. C (0-4).**

Notes on the closest calls:

- **A vs a (margin 1):** the only difference between the two is form
  (criterion 5). Same drink, same vividness, same wit, same honesty.
  The case change costs "a" almost nothing against the letter that
  matters.
- **a vs B (margin 2):** the key fight for the entry. Coffee's edge on
  criteria 2–4 is worth more than B's form edge on criterion 5, so "a"
  beats the other drink's canonical form.
- **a vs C / b vs C:** under the lenient case reading these are
  criterion-1 wins. Under a strict reading (lowercase fails criterion 1)
  "a" still beats C — a faint coffee reading beats a letter naming
  nothing — at a smaller margin (see Hermes below: margin 3).

## Hermes cross-check (independent judge, same brief)

Hermes (my-combo MoA on the VPS) judged the same pairs, both orders.
It read lowercase **strictly**: "lowercase a fails strict uppercase
Criterion 1". Its verdicts:

| Pair | Winner | Margin | Note |
|------|--------|--------|------|
| A vs B | A | 2 | coffee's vivid edge |
| A vs a | A | 3 | strict case reading |
| B vs b | B | 3 | strict case reading |
| a vs B | B | 4 | strict case reading — lowercase loses outright |
| b vs A | A | 4 | strict case reading |
| a vs b | a | 1 | both lowercase; coffee still edges tea |
| A vs C | A | 5 | criterion 1 |
| a vs C | a | 3 | "a retains a faint coffee reading" |

Hermes ranking: A, B, a, b, C.

## What the cross-check changes, and what it does not

- It **confirms** the drink result both judges agree on: coffee (A)
  beats tea (B), margin 2–3, both orders.
- It **disagrees** on the case reading: Hermes is strict, the builder is
  lenient. This is the one genuine uncertainty in the entry, and it is
  priced into the decision (CANDIDATES.md): even on the strict reading,
  "a" beats every junk letter, so as the top non-anchor member it still
  takes the playoff and wins it in the anchor world; in the no-anchor
  world it would place 3rd ($1) instead of 2nd ($2).
- It does **not** change the winner: on pure pairwise strength A is
  strongest, but A is almost certainly an anchor copy (see
  CANDIDATES.md — the structural analysis), and an anchor copy cannot
  enter the playoff. "a" is the strongest candidate that can actually
  win the competition as the rules are written.

## Final

**Entry: "a".** Fallback (literal-brief only): "A".
