# Maths IA-1 — THE ONLY SHEET (one night, one source, final)

> **CLOSE EVERYTHING ELSE.** The Master Worksheet and the Do-or-Die sheet are retired — they were versions of this. THIS file is your entire night and your entire exam prep. It contains: schedule · 17 quick traps · 8 hard questions · 4 application questions · exam playbook · formula card. Nothing outside this file will help you more than what is inside it.
### Format-proof · marks-proof · twisted central-team level · target 70%+ · answers inline

**FORMAT WARNING:** IA-1 layout is UNKNOWN and MARKS are UNKNOWN — the two contests ran differently, and the central team can change format AND weightage any time (MCQ, fill, matching, worded, long-working, any mix, any marks). So this sheet assumes NOTHING about the paper and trains two things only: **quick-mark traps** (become the short questions whatever they're called) and **hard working questions** (become the big questions whatever they're called and however many marks they carry).

**THE PACT — the only math that survives an unknown paper:** every maths paper, any format, pays two kinds of marks: fast safe ones and slow heavy ones. **70% = near-perfect on the fast ones + 2–3 heavy ones solved fully.** Whether short marks are worth 1 or 3 and long ones 4 or 8, that ratio still lands you at/above 70%.

---

## NIGHT SCHEDULE — follow the clock, no decisions needed

| Block | Time | Do |
|---|---|---|
| I | 22:00 – 00:30 | TIER 1 below: 17 quick-mark traps, answers as you go |
| — | 00:30 – 00:50 | break: walk, water, food |
| II | 00:50 – 03:40 | TIER 2 (8 hard) + TIER 3 (4 applications), full steps |
| III | 03:40 – 04:15 | re-solve EVERY wrong one with the answer covered |
| IV | 04:15 – 05:15 | memorise FORMULA CARD + PLAYBOOK |
| V | 05:15 – 06:15 | timed re-run of Tier 1, 20 min, zero errors |
| VI | 06:00 – 06:45 | timed re-run of 5 best Tier 2, 30 min |
| VII | 06:45 – exam time | formula card final glance, get ready, leave early |

---

# TIER 1 — 17 quick-mark traps (these ARE the safe marks in any format)

*Each one is designed to be asked as MCQ, fill-in, match-pair or 2-mark short. Learn the trap, not the shape.*

1. If a < b, which need NOT be true? (a) a−3 < b−3 (b) −4a > −4b (c) a² < b² (d) 3a < 3b
→ **(c)** — a = −5, b = 1 → 25 < 1 false. Everything that "flips" or "squares" is the bait.

2. log₂(x − 1) = 3 → x = ?
→ **9** (x − 1 = 8; the trap answer is 8)

3. x² + (k − 3)x + k = 0 has equal roots → sum of possible k = ? product = ?
→ **sum 10, product 9** — D = k² − 10k + 9 = 0 → k = 1 or 9. Underline SUM vs PRODUCT before answering.

4. Solution of (x − 3)/(x + 1) < 0 →
→ **−1 < x < 3** (opposite signs between the roots; x = −1 excluded)

5. Digits of 2¹⁰⁰ (log 2 = 0.3010) →
→ **31** (⌊30.10⌋ + 1)

6. Last two digits of 7²⁰⁰ →
→ **01** (7⁴ = 2401 ≡ 01 mod 100)

7. gcd(a,b) = 12, lcm(a,b) = 120 → ordered pairs (a,b) = ?
→ **4** — a = 12x, b = 12y, xy = 10, gcd(x,y) = 1: (1,10)(2,5)(5,2)(10,1)

8. "All multiples of 4 are even. 12 is even. So 12 is a multiple of 4." Flaw?
→ **even ≠ multiple of 4 (6 is even, not a multiple of 4)** — reasoning ran backwards

9. |x| = −x exactly when →
→ **x ≤ 0** (0 included — trap answer: x < 0)

10. x + 1/x = 4 → x³ + 1/x³ = ?
→ **52** (4³ − 3·4)

11. log₅ 125 + log₂ 32 − log₁₀ 10000 = ?
→ **4** (3 + 5 − 4)

12. Remainder of 10¹⁰ ÷ 7 = ?
→ **4** (10 ≡ 3; 3⁶ ≡ 1; 10 = 6+4 → 3⁴ = 81 ≡ 4)

13. Divisors of 360 = ?
→ **24** (2³·3²·5 → 4·3·2)

14. (x − 2) divides x³ − kx² + 10x − 8 → k = ?
→ **5** (f(2) = 20 − 4k = 0)

15. 4^(x+1) = 8^x → x = ?
→ **2** (2x + 2 = 3x)

16. Product of roots of 3x² − 7x + 2 = 0 →
→ **2/3** (c/a)

17. **MATCH SET:** a) x + 1/x = 3 → x² + 1/x² · b) lcm(12,18) · c) 100 mod 7 · d) log₉ 27 · e) divisors of 60 — against: 7 / 36 / 2 / 3/2 / 12
→ **a-7 · b-36 · c-2 · d-3/2 · e-12**

---

# TIER 2 — 8 hard questions (the 10-mark engine; exam needs 2–3 of these perfect)

*Full-mark rule everywhere: given → formula → steps → answer → one sentence of meaning. Any format that asks for "working/reasoning" pays per line.*

**H1.** Last two digits of 31³¹.
→ (30 + 1)³¹ = 1 + 31×30 + terms with 900 ≡ 0 (mod 100) → 1 + 930 = 931 → **31**

**H2.** Prove n⁴ − n² divisible by 12 for every integer n.
→ n²(n−1)(n+1): three consecutive integers give factor 3; n even → n² gives 4, n odd → both neighbours even give 4. Divisible by 3 and 4, coprime → **divisible by 12 ∎**

**H3.** Greatest number dividing 552, 967, 1032 leaving the SAME remainder?
→ differences: 415, 65, 480 → Euclid on (415, 65): 415 = 6×65+25, 65 = 2×25+15, 25 = 15+10, 15 = 10+5 → **5**; check remainders 2, 2, 2 ✓

**H4.** Boat: same distance upstream in 4 h as downstream in 2 h, stream 3 km/h. Boat speed & distance?
→ 4(b−3) = 2(b+3) → **b = 9 km/h**, distance **24 km** (check: 2(9+3) = 24 ✓)

**H5.** Solve log x + log(x + 3) = 1.
→ x² + 3x − 10 = 0 → x = 2 or −5 → **x = 2** (must write: −5 rejected, domain x > 0)

**H6.** Solve 5x ≡ 3 (mod 8).
→ inverse of 5 is 5 (25 ≡ 1) → x ≡ 15 → **x ≡ 7 (mod 8)**

**H7.** Four bells toll together at noon, then every 6, 8, 12, 15 s. How many times together in 1 hour including start?
→ lcm = 120 s; 3600/120 = 30 → **31 times**

**H8.** Sum of a number and its reciprocal is 10/3. Find it.
→ 3x² − 10x + 3 = 0 → (3x−1)(x−3) → **x = 3 or 1/3** (both — word problems can have two)

---

---

# TIER 3 — 4 application questions (central teams LOVE worded problems)

*Same rule: given → formula → steps → answer → one sentence of meaning.*

**T1. (algebra → quadratic)** A garden is 5 m longer than wide; area 36 m². Dimensions? Then same garden widened to 40 m² — new width?
→ w(w + 5) = 36 → w² + 5w − 36 = 0 → (w + 9)(w − 4) = 0 → **w = 4 m, l = 9 m** (reject −9)
→ w² + 5w − 40 = 0 → w = (−5 + √185)/2 ≈ **4.3 m** (√185 ≈ 13.60)

**T2. (inequality chain)** IQ = MA/CA × 100. Children aged 15 with 90 ≤ IQ ≤ 150 — mental age range?
→ MA = IQ × 15/100 → 90→13.5, 150→22.5 → **13.5 ≤ MA ≤ 22.5 years**

**T3. (rocket — the full 4-mark shape)** h(t) = −5t² + 20t + 25: (i) zeros (ii) max height without calculus (iii) h(6) = −35 — "35 m underground"?
→ (i) −5(t − 5)(t + 1) → **t = 5 s** (t = −1 rejected: time ≥ 0)
→ (ii) vertex t = −b/2a = 2 → h(2) = −20 + 40 + 25 = **45 m**
→ (iii) **NO** — formula is only valid during flight; t = 6 s is past landing, negative height is extrapolation outside the model

**T4. (log application)** pH = −log₁₀[H⁺]. A: [H⁺] = 10⁻³, B: 10⁻⁴·⁵. Which more acidic, by how much?
→ pH A = 3, pH B = 4.5 → lower pH = more acidic → **A more acidic by 1.5 pH units**

# PLAYBOOK — extracting 70% from an unpredictable, confusing, unknown-marks paper

**Universal order (90 min):**
1. **First 5 min:** read the WHOLE paper, note what formats exist today (they differ!), count marks per part. No solving yet.
2. **Next pass (first ~⅓ of your time):** every question answerable in ≤ 90 seconds — values, fills, one-liners, obvious MCQs. This is your safe bank. Do it in ANY order.
3. **Matching (if present):** pair independently, lock 3+ pairs minimum.
4. **Remaining (~half your time):** the heavy ones. First pick 2–3 whose chapter you recognise, solve fully with steps. Then fight the rest.
5. **Last ~10%:** every blank gets SOMETHING; check signs, rejections, units.

**70% scoreboard mid-exam:** after the safe pass, ask: 'did I lock the easy ones and fully solve two heavy ones?' If yes → you're on track, no panic. If no → the heavy ones are where you go next, never sideways into new territory.

**When the question confuses you (twist protocol):**
- Read twice, **underline exactly what is asked** (sum? product? value of k? "need NOT"? "always"?).
- Name the chapter, write the givens, write the one formula that fits.
- Lost anyway? Write formula + substitution + anything derivable → partial credit is real credit wherever marks exist.

**Format-switch rules (whatever they throw):**
- MCQ with no stated negative marking → **never leave blank**; eliminate 2 first.
- "Explain/justify/why" → full sentence, name the reason (domain, flip, sign, rejection, converse).
- Interpretation ("is this correct?") → YES/NO + reason, even if unfinished.
- Two candidate answers → plug both into the ORIGINAL statement; original always wins.
- Unknown/freak format → it's still chapters 1–6 underneath: identify which, apply formula card.

**3-minute rule:** not cracked in 3 min → abandon, flag, return at minute 75.

---

# FORMULA CARD — memorise in block IV, final glance at VII

**Ch1:** (x+1/x)² − 2 · (x+1/x)³ − 3(x+1/x) · (a+b)²−2ab · 4ab identity · digits = ⌊log⌋+1 · area = big shape − removed pieces
**Ch2:** D = b²−4ac (touch ⟺ 0, none ⟺ <0) · sum −b/a, product c/a · vertex −b/2a · both roots + ⟺ sum>0, product>0, D≥0 · equal roots ⟺ D = 0
**Ch3:** flip only on ×÷ negative · |x| ≤ a ⟺ −a ≤ x ≤ a · quadratic < 0 between roots · rational: sign chart, exclude denominator · "all x" ⟺ D<0 & a>0
**Ch4:** + logs multiply, − divide · log_a a = 1 · aᵇ=N ⟺ b=log_a N · chain collapse · digits formula · **domain first, reject negatives/zero**
**Ch5:** gcd×lcm = product · Euclid steps to 0 · same remainder ⟹ gcd of differences · τ = Π(eᵢ+1) · or-count = A + B − both · pair form gcd·x, gcd·y with gcd(x,y)=1
**Ch6:** reduce base mod n → reduce exponent mod cycle · last-digit cycles len 4 · mod 100 heroes: 7⁴≡01, 3²⁰≡01 · inverse = multiply to ≡1 · ax≡b: divide by gcd first · consecutive-product proofs

---

**This is the whole plan. Tiers 1-2-3 in order, then playbook, then formula card. Nothing else exists tonight.**
