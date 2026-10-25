# Maths IA-1 — THE ONLY SHEET (one night, one source, final)

> **CLOSE EVERYTHING ELSE.** This file is your entire night and your entire exam prep: schedule · 27 quick traps · 8 hard questions · 4 applications · playbook · formula card. Every question now has: **CONCEPT (kid-language)** (the idea explained like you're 10 — no prior knowledge needed) · **TRIGGER** (how the paper signals this type) · **STEPS** (full solution) · **REMEMBER** (the line that scores the mark).

---

## NIGHT SCHEDULE — follow the clock, no decisions needed

| Block | Time | Do |
|---|---|---|
| I | now – +2.5h | TIER 1: 27 quick traps (read TRIGGER → cover STEPS → solve → check) |
| — | +2.5h – +2.75h | break: walk, water, food |
| II | +2.75h – +6h | TIER 2 (8 hard) + TIER 3 (4 applications), full steps |
| III | +6h – +6.5h | re-solve EVERY wrong one with the answer covered |
| IV | +6.5h – +7.5h | memorise FORMULA CARD + PLAYBOOK |
| V | +7.5h – +8.5h | timed re-run Tier 1, 25 min, zero errors |
| VI | +8.5h – +9h | timed re-run 5 best Tier 2, 30 min |
| VII | final 30 min | formula card glance, get ready, leave |

---

# TIER 1 — 27 quick-mark traps (the safe marks in ANY format)

**1.** If a < b, which need NOT be true? (a) a−3 < b−3 (b) −4a > −4b (c) a² < b² (d) 3a < 3b
- **CONCEPT (kid-language):** a < b just means a is the smaller number. Add the same to both sides → order stays the same. Multiply both by a NEGATIVE → the order flips (like a mirror image). Squaring only keeps the order if both numbers are positive — that's the trap.
- **TRIGGER:** wording "need NOT"/"always" → test with a = −5, b = 1
- **STEPS:** (a) −8 < −2 ✓ · (b) 20 > −4 ✓ (flip works) · (c) 25 < 1 ✗ FALSE → answer **(c)** · (d) −15 < 3 ✓
- **REMEMBER:** × negative flips, × positive keeps, **squaring breaks order when signs differ**

**2.** log₂(x − 1) = 3 → x = ?
- **CONCEPT (kid-language):** A log is just the question: '2 multiplied by itself how many times gives this number?' log₂(8) = 3 because 2×2×2 = 8. So your equation is saying 2×2×2 = x−1, meaning x−1 = 8, so x = 9.
- **TRIGGER:** log of an expression = number → drop the log first
- **STEPS:** x − 1 = 2³ = 8 → x = **9**
- **REMEMBER:** undo log BEFORE touching the +1; **8 is the bait answer**

**3.** x² + (k − 3)x + k = 0 has equal roots → sum of possible k = ? product = ?
- **CONCEPT (kid-language):** Every quadratic x²+bx+c = 0 has one magic number: D = b²−4ac. D > 0 → two answers. D = 0 → exactly one (they're 'equal'). D < 0 → no answers. The words 'equal roots' or 'touches the axis' mean ONLY ONE job: write D = 0 and solve it.
- **TRIGGER:** "equal roots" / "touches the axis once"
- **STEPS:** D = (k−3)² − 4k = 0 → k² − 6k + 9 − 4k = k² − 10k + 9 = 0 → k = 1, 9 → sum = **10**, product = **9**
- **REMEMBER:** D = 0 engine; **underline sum vs product BEFORE solving**

**4.** Solution of (x − 3)/(x + 1) < 0 →
- **CONCEPT (kid-language):** A fraction is negative only when the TOP and BOTTOM have opposite signs (one +, one −). Find where the top becomes 0 (x = 3) and where the bottom becomes 0 (x = −1) — those two points split the number line — then test a number in between.
- **TRIGGER:** rational < 0 → numerator and denominator opposite signs → between the roots
- **STEPS:** roots −1 and 3 → test x = 0: (−3)/(1) = −3 < 0 ✓ inside → **−1 < x < 3**, x ≠ −1
- **REMEMBER:** denominator point NEVER included; no flip ever happens here

**5.** Digits of 2¹⁰⁰ (log 2 = 0.3010) →
- **CONCEPT (kid-language):** log₁₀(N) = 'ten times itself how many times reaches N?'. If that answer is 30.10, you have 30 full jumps plus a tiny bit more → the number has 31 digits. Rule: digits = the whole-number part + 1.
- **TRIGGER:** "how many digits"
- **STEPS:** log(2¹⁰⁰) = 30.10 → ⌊30.10⌋ + 1 = **31**
- **REMEMBER:** digits = ⌊log N⌋ + 1 — the **+1** is the whole question

**6.** Last two digits of 7²⁰⁰ →
- **CONCEPT (kid-language):** 'Last two digits' means 'remainder after dividing by 100'. Don't compute 7²⁰⁰ — notice 7×7×7×7 = 2401 ends in 01, and 01 × 01 × 01... always stays 01. So the answer is 01.
- **TRIGGER:** "last two digits" → mod 100
- **STEPS:** 7⁴ = 2401 ≡ 01 (mod 100) → 7²⁰⁰ = (7⁴)⁵⁰ ≡ 1⁵⁰ = **01**
- **REMEMBER:** memorise hero 7⁴ ≡ 01 — one line, full marks

**7.** gcd(a,b) = 12, lcm(a,b) = 120 → ordered pairs (a,b) = ?
- **CONCEPT (kid-language):** GCD = the biggest block that evenly divides BOTH numbers. LCM = the smallest number both fit into. Golden rule to memorise: number × number = GCD × LCM, always true, like a law of gravity.
- **TRIGGER:** gcd AND lcm both given → pull the gcd out
- **STEPS:** a = 12x, b = 12y with xy = 10 and gcd(x,y) = 1 → (1,10)(2,5)(5,2)(10,1) → **4**
- **REMEMBER:** divide both by the gcd first, then coprime-factor the rest

**8.** "All multiples of 4 are even. 12 is even. So 12 is a multiple of 4." Why invalid?
- **CONCEPT (kid-language):** 'Every dog is an animal. This is an animal. So it's a dog' — silly, right? It could be a cat. That's the flaw: being even doesn't make 12 a multiple of 4, because 6 is even and NOT a multiple of 4. One counterexample kills the logic.
- **TRIGGER:** "reasoning incorrect/flawed" → find counterexample
- **STEPS:** 6 is even but not a multiple of 4 → the conclusion doesn't follow → **(b)**
- **REMEMBER:** going backwards from a property needs proof, not vibes — cite the counterexample

**9.** |x| = −x exactly when →
- **CONCEPT (kid-language):** |x| = how far x sits from 0 on the number line — it's never negative. |x| = −x works only when x is 0 or below (then −x is a positive number). Trap: don't forget 0 — because |0| = −0 also works.
- **TRIGGER:** absolute value equals its negative
- **STEPS:** x = 0: 0 = 0 ✓; x < 0: |x| = −x ✓; x > 0: x = −x ✗ → **x ≤ 0**
- **REMEMBER:** **0 is included** — trap answer is x < 0

**10.** x + 1/x = 4 → x³ + 1/x³ = ?
- **CONCEPT (kid-language):** There's a family of ready-made shortcuts for x + 1/x. The cube one: (x+1/x)³ = x³+1/x³ + 3(x+1/x). If x+1/x = 4: 64 = answer + 3×4 → answer = 64 − 12 = 52. Just memorise the recipe and pour in the number.
- **TRIGGER:** x + 1/x given, higher power asked
- **STEPS:** (x+1/x)³ = x³ + 1/x³ + 3(x+1/x) → 64 = ans + 12 → **52**
- **REMEMBER:** cube formula subtracts **3×(the given)**, not 3

**11.** log₅ 125 + log₂ 32 − log₁₀ 10000 = ?
- **CONCEPT (kid-language):** Each of these logs is a 'what power?' question: 5^? = 125 → 3; 2^? = 32 → 5; 10^? = 10000 → 4. Turn each into its power first, THEN do the arithmetic: 3 + 5 − 4 = 4.
- **TRIGGER:** logs of exact powers → convert to exponents
- **STEPS:** 5³=125→3 · 2⁵=32→5 · 10⁴=10000→4 → 3 + 5 − 4 = **4**
- **REMEMBER:** rewrite each as "to what power" — arithmetic then trivial

**12.** Remainder of 10¹⁰ ÷ 7 = ?
- **CONCEPT (kid-language):** Remainders repeat in loops. For 3 dividing 7, the loop length is 6 (because 3⁶ = 729 leaves remainder 1). So cut the big exponent: 10 ÷ 6 leaves remainder 4 → same answer as 3⁴. 81 ÷ 7 leaves 4.
- **TRIGGER:** big power remainder → reduce base, find cycle
- **STEPS:** 10 ≡ 3 (mod 7); 3⁶ = 729 ≡ 1; 10 = 6×1 + 4 → 3⁴ = 81 = 7×11 + 4 → **4**
- **REMEMBER:** reduce base first, then exponent mod cycle length (6 here)

**13.** Divisors of 360 = ?
- **CONCEPT (kid-language):** For 360 = 2×2×2 × 3×3 × 5: the 2s can be picked 0, 1, 2 or 3 times → 4 choices; the 3s → 3 choices; the 5 → 2 choices. Multiply the choices: 4 × 3 × 2 = 24 ways → 24 divisors. Never count them one by one.
- **TRIGGER:** "number of divisors" → prime-factorise
- **STEPS:** 360 = 2³·3²·5 → (3+1)(2+1)(1+1) = **24**
- **REMEMBER:** τ = product of (exponent + 1) — always +1

**14.** (x − 2) divides x³ − kx² + 10x − 8 exactly → k = ?
- **CONCEPT (kid-language):** '(x−2) divides exactly' means: when x = 2, the whole expression collapses to 0. So plug x = 2 in: 8 − 4k + 20 − 8 = 0 → 20 = 4k → k = 5. That's the entire trick.
- **TRIGGER:** "(x − a) divides/exactly" → factor theorem
- **STEPS:** f(2) = 8 − 4k + 20 − 8 = 0 → 20 − 4k = 0 → k = **5**
- **REMEMBER:** plug the ROOT (sign flips: x−2=0 → x=+2), set whole thing = 0

**15.** 4^(x+1) = 8^x → x = ?
- **CONCEPT (kid-language):** 4 and 8 are both built from 2s (4 = 2², 8 = 2³). Rewrite both sides with base 2: 2^(2x+2) = 2^(3x). If the bases are the same, the exponents MUST match → 2x+2 = 3x → x = 2.
- **TRIGGER:** power = power → make bases SAME
- **STEPS:** 2^(2x+2) = 2^(3x) → 2x + 2 = 3x → x = **2**
- **REMEMBER:** bases equal ⟹ exponents equal — never subtract bases

**16.** Product of roots of 3x² − 7x + 2 = 0 →
- **CONCEPT (kid-language):** You can know the roots' sum and product WITHOUT finding the roots: sum = −b/a, product = c/a (they come from expanding (x−α)(x−β)). For 3x²−7x+2: product = 2/3. Five seconds, done.
- **TRIGGER:** roots asked WITHOUT solving → Vieta's formulas
- **STEPS:** product = c/a = **2/3** (sum would be 7/3)
- **REMEMBER:** product = c/a, sum = −b/a — sign is the trap

**17.** MATCH: a) x+1/x=3 → x²+1/x² · b) lcm(12,18) · c) 100 mod 7 · d) log₉27 · e) divisors of 60 — vs 7 / 36 / 2 / 3/2 / 12
- **CONCEPT (kid-language):** Matching = 5 tiny separate sums. Do the ones you recognise FIRST, lock their pairs, don't let one weird pair block the five easy ones. One pair at a time, independently.
- **TRIGGER:** matching → solve each pair INDEPENDENTLY, never chain
- **STEPS:** a) 9 − 2 = **7** · b) **36** · c) 100 = 14×7 + 2 → **2** · d) 9^{3/2}=27 → **3/2** · e) 2²·3·5 → 2·2·2 = **12**
- **REMEMBER:** pair-by-pair, lock the confident 3 first

**18.** Complete the square: x² − 8x + 5 →
- **CONCEPT (kid-language):** 'Make it a clean square': take half the middle number (−8 → −4), square it (16), write (x−4)², then subtract 16 back because you snuck it in: (x−4)² −16 + 5 = (x−4)² − 11. Wobbly quadratic becomes tidy.
- **TRIGGER:** "write in the form (x + p)² + q"
- **STEPS:** half of −8 = −4 → (x − 4)² − 16 + 5 = **(x − 4)² − 11**
- **REMEMBER:** halve, square, SUBTRACT what you added

**19.** gcd(1071, 462) with Euclidean steps →
- **CONCEPT (kid-language):** Keep dividing the BIGGER by the SMALLER and keep only what's left over: 1071 ÷ 462 → left 147; then 462 ÷ 147 → left 21; then 147 ÷ 21 → nothing left. Stop. The last leftover — 21 — is your gcd. That's the whole Euclidean algorithm.
- **TRIGGER:** "use Euclidean algorithm" / big numbers
- **STEPS:** 1071 = 2×462 + 147 → 462 = 3×147 + 21 → 147 = 7×21 + 0 → **21**
- **REMEMBER:** write every division line — the steps are the marks, answer alone ≈ half credit

**20.** Integers 1–100 divisible by 6 OR by 8 →
- **CONCEPT (kid-language):** Multiples of 6 up to 100: 16 of them. Multiples of 8: 12. But numbers like 24, 48 (multiples of BOTH) were counted in each pile — so subtract the 4 double-counted: 16 + 12 − 4 = 24. That subtraction is the entire idea.
- **TRIGGER:** "or" in counting → inclusion–exclusion
- **STEPS:** ⌊100/6⌋ = 16, ⌊100/8⌋ = 12, ⌊100/24⌋ = 4 → 16 + 12 − 4 = **24**
- **REMEMBER:** |A| + |B| − |A∩B| — subtracting the double-count IS the question

**21.** Find k so x² + 2x + k > 0 for EVERY real x →
- **CONCEPT (kid-language):** 'Always bigger than 0' means the curve floats ABOVE the line and never touches it. Touching = D = 0 (fails), floating = D < 0 (wins). So 4 − 4k < 0 → k > 1. Note: k = 1 touches at one point → NOT > 0 → fails.
- **TRIGGER:** "for all real x" / "always positive"
- **STEPS:** need D < 0 and open-up: 4 − 4k < 0 → **k > 1**
- **REMEMBER:** strict — k = 1 fails (x = −1 gives exactly 0, not > 0)

**22.** Factorise fully: x⁴ − 16 →
- **CONCEPT (kid-language):** A big square minus a small square splits: A² − B² = (A−B)(A+B). So x⁴ − 16 = (x²)² − 4² = (x²−4)(x²+4); then x²−4 splits again = (x−2)(x+2). The (x²+4) piece can't split — that's your stop sign.
- **TRIGGER:** "fully" → apply difference of squares until it stops
- **STEPS:** x⁴ − 16 = (x²)² − 4² = (x²−4)(x²+4) = **(x−2)(x+2)(x²+4)**
- **REMEMBER:** x² + 4 never factors over reals — stop there

**23.** 2³ · 2⁵ ÷ 2⁴ = →
- **CONCEPT (kid-language):** Same base? Only the POWERS move: multiplying adds powers, dividing subtracts. The base 2 never changes: 2³ · 2⁵ ÷ 2⁴ = 2^(3+5−4) = 2⁴ = 16. Never multiply the bases themselves.
- **TRIGGER:** same base, × ÷ → add/subtract exponents
- **STEPS:** 3 + 5 − 4 = 4 → 2⁴ = **16**
- **REMEMBER:** never multiply the bases — only the powers move

**24.** Express log 45 using log 3 and log 5 →
- **CONCEPT (kid-language):** Logs turn × into +: log(9 × 5) = log 9 + log 5. And log 9 = log 3² = 2 log 3. So log 45 = 2 log 3 + log 5. First FACTOR the number, then the logs fall apart.
- **TRIGGER:** "in terms of" → factorise the number
- **STEPS:** 45 = 9 × 5 = 3²·5 → 2 log 3 + log 5
- **REMEMBER:** split the NUMBER, not the log

**25.** If 2ˣ = 7 then x = →
- **CONCEPT (kid-language):** 2ˣ = 7 and x = log₂ 7 are the exact same sentence — one spoken in power-language, one in log-language. The base of the power becomes the base of the log. Always. No exceptions.
- **TRIGGER:** exponential given, log form asked
- **STEPS:** aᵇ = c ⟺ b = log_a c → x = **log₂ 7** (or log 7 / log 2)
- **REMEMBER:** base of log = base of power, always

**26.** gcd(a,b) = 8, lcm(a,b) = 96, a = 24 → b = ?
- **CONCEPT (kid-language):** If both numbers are built on the same block (8) and the shelf is 96: b = (8 × 96) ÷ 24 = 32. Rule: a × b = gcd × lcm — rearrange it like a formula and plug in.
- **TRIGGER:** three of the four gcd/lcm quantities → product rule
- **STEPS:** a·b = gcd·lcm → 24·b = 8×96 = 768 → b = **32**
- **REMEMBER:** gcd × lcm = a × b — the one law that binds them

**27.** Buses leave every 15 min and 20 min, both at 8:00 → next together at?
- **CONCEPT (kid-language):** 'Together' = the smallest number both intervals fit into = LCM. LCM(15, 20) = 60 minutes → 8:00 + 60 = 9:00. Whenever you see 'at the same time again', it's screaming LCM at you.
- **TRIGGER:** "next time together" → LCM of the intervals
- **STEPS:** lcm(15, 20) = 60 → 8:00 + 60 min = **9:00**
- **REMEMBER:** together = LCM, ever-decreasing gaps = HCF — never mix them

---

# TIER 2 — 8 hard questions (the heavy-marks engine; exam needs 2–3 perfect)

*Full-mark rule: GIVEN → FORMULA → STEPS → ANSWER → one sentence of meaning.*

**H1.** Last two digits of 31³¹.
- **CONCEPT (kid-language):** 31 = 30 + 1. Expanding (30+1)³¹ piece by piece: after the first two pieces, EVERY piece contains 30×30 = 900, whose last two digits are 00 — they disappear. Only 1 + 31×30 = 931 survives → last two digits 31.
- **TRIGGER:** last two digits of a NON-8-or-7 base → binomial split
- **STEPS:** 31 = 30 + 1 → (30+1)³¹ = 1 + 31×30 + terms with 30² = 900 ≡ 0 (mod 100) → 1 + 930 = 931 → **31**
- **REMEMBER:** split into (tens + ones); everything with 30² dies mod 100

**H2.** Prove n⁴ − n² divisible by 12 for every integer n.
- **CONCEPT (kid-language):** Proving divisible by 12? Split 12 into 3 × 4 and prove each part. Any three numbers in a row always include a multiple of 3 → part 1 done. For 4: if n is even, n² supplies both 2s; if n is odd, both neighbours are even → two 2s. Both parts proven → divisible by 12.
- **TRIGGER:** "prove divisible by" → factorise into consecutive products
- **STEPS:** n²(n−1)(n+1): (n−1)n(n+1) gives a factor 3; n even → n² gives 4, n odd → two even neighbours give 4 → divisible by 3 AND 4, coprime → **12 ∎**
- **REMEMBER:** split the divisor (12 = 3 × 4) and prove each part separately

**H3.** Greatest number dividing 552, 967, 1032 leaving the SAME remainder?
- **CONCEPT (kid-language):** If three numbers leave the SAME leftover when divided by N, subtracting pairs wipes the leftover away — so N must divide every difference. Answer = biggest number dividing all differences = 5. Then check: leftovers are 2, 2, 2 ✓ — the check IS a mark.
- **TRIGGER:** "same remainder" → gcd of DIFFERENCES
- **STEPS:** differences 415, 65, 480 → Euclid(415,65): 415 = 6×65+25 → 65 = 2×25+15 → 25 = 15+10 → 15 = 10+5 → **5**; check 552=110×5+2, 967=193×5+2, 1032=206×5+2 all leave 2 ✓
- **REMEMBER:** answer is gcd(differences) — **always verify remainders match** (that check is one mark)

**H4.** Same distance upstream in 4 h as downstream in 2 h; stream 3 km/h. Boat speed & distance?
- **CONCEPT (kid-language):** Same distance both ways → speed × time on both sides. Upstream speed = boat − current (b − 3), downstream = b + 3: 4(b−3) = 2(b+3) → 4b − 12 = 2b + 6 → b = 9. Distance = 4 × 6 = 24 km. Always verify with the other side: 2 × 12 = 24 ✓.
- **TRIGGER:** two trips, same distance → set the products equal
- **STEPS:** 4(b − 3) = 2(b + 3) → 4b − 12 = 2b + 6 → 2b = 18 → b = **9 km/h**; distance = 4 × 6 = **24 km**; check 2 × 12 = 24 ✓
- **REMEMBER:** with-stream = +, against = −; **write the check line**

**H5.** Solve log x + log(x + 3) = 1.
- **CONCEPT (kid-language):** Logs only accept POSITIVE numbers. First mash the logs together: log x + log(x+3) = log[x(x+3)] → quadratic → x = −5 or 2. Then THROW AWAY −5 (it would make log negative) → answer 2. Writing 'rejected because…' earns a mark.
- **TRIGGER:** logs added → combine → solve quadratic → DOMAIN CHECK
- **STEPS:** log[x(x+3)] = 1 → x² + 3x = 10 → x² + 3x − 10 = 0 → (x+5)(x−2) = 0 → x = −5 or 2; need x > 0 → **x = 2**
- **REMEMBER:** rejection line scores a mark — "x = −5 rejected, log undefined for x < 0"

**H6.** Solve 5x ≡ 3 (mod 8).
- **CONCEPT (kid-language):** Inverse = the thing that multiplies back to 1. In ÷8 world, 5 × 5 = 25 = 24 + 1 ≡ 1, so inverse of 5 is 5. Multiply both sides of 5x ≡ 3 by 5: x ≡ 15 ≡ 7 (mod 8).
- **TRIGGER:** linear congruence → need the inverse
- **STEPS:** 5×5 = 25 ≡ 1 (mod 8) → multiply both sides by 5: x ≡ 15 ≡ 7 → **x ≡ 7 (mod 8)**
- **REMEMBER:** find what multiplies to ≡ 1 — try small numbers: 1,3,5,7 (odd residues are self-inverse here)

**H7.** Four bells toll together at noon, then every 6, 8, 12, 15 s. Together how many times in 1 hour including start?
- **CONCEPT (kid-language):** All four together first happen after lcm(6, 8, 12, 15) = 120 seconds. In 3600 s: 3600 ÷ 120 = 30 times AFTER the start. Count the starting moment too → 31. Decide the +1 explicitly — that's the mark.
- **TRIGGER:** "together" + intervals → LCM + count including t = 0
- **STEPS:** lcm(6,8,12,15) = 120 s → 3600 ÷ 120 = 30 → +1 for the start = **31**
- **REMEMBER:** decide inclusion explicitly ("including the start") — +1 or not is the mark

**H8.** Sum of a number and its reciprocal is 10/3. Find it.
- **CONCEPT (kid-language):** Kill the fraction: multiply everything by 3x → 3x² + 3 = 10x → 3x² − 10x + 3 = 0 → (3x−1)(x−3) = 0 → x = 3 or 1/3. Reciprocal answers come in PAIRS — give both, don't pick a favourite.
- **TRIGGER:** "sum of a number and its reciprocal" → clear fractions
- **STEPS:** x + 1/x = 10/3 → 3x² − 10x + 3 = 0 → (3x−1)(x−3) = 0 → x = 3 or 1/3 → **both**
- **REMEMBER:** word problems can have TWO answers — give both, don't pick

---

# TIER 3 — 4 application questions (central teams LOVE worded problems)

**T1.** Garden is 5 m longer than wide; area 36 m². Dimensions? Widened to 40 m² → width?
- **CONCEPT (kid-language):** '5 longer than wide' → width = w, length = w + 5. Area: w(w+5) = 36 → quadratic → w = 4 (reject −9 — a garden can't be −9 wide). Second part: same steps with 40 → w ≈ 4.3 m. Words → one variable → quadratic → reject nonsense.
- **TRIGGER:** area word problem → quadratic
- **STEPS:** w(w+5) = 36 → w² + 5w − 36 = 0 → (w+9)(w−4) = 0 → w = **4 m, l = 9 m** (reject −9); then w² + 5w − 40 = 0 → w = (−5 + √185)/2 ≈ **4.3 m**
- **REMEMBER:** reject the negative length in a sentence, every time

**T2.** IQ = MA/CA × 100. Age 15, 90 ≤ IQ ≤ 150 → mental-age range?
- **CONCEPT (kid-language):** The formula IS your instructions: MA = IQ × age ÷ 100. Feed it the two ENDPOINTS: 90 × 15/100 = 13.5 and 150 × 15/100 = 22.5. Mental age sits between 13.5 and 22.5 years. Endpoints in, endpoints out.
- **TRIGGER:** chained inequality with a formula
- **STEPS:** MA = IQ × 15/100 → 90→13.5, 150→22.5 → **13.5 ≤ MA ≤ 22.5 years**
- **REMEMBER:** substitute the ENDPOINTS only — inequalities map to endpoints

**T3.** h(t) = −5t² + 20t + 25: (i) zeros (ii) max height no calculus (iii) h(6) = −35 — "35 m underground"?
- **CONCEPT (kid-language):** Height formula: set h = 0 to find when it lands → t = 5 (reject t = −1: time can't be negative). Peak at t = −b/2a = 2 → 45 m. And h(6) = −35 does NOT mean underground — the formula only works while flying, like a graph that stops when the rocket lands.
- **TRIGGER:** physics worded quadratic → always interpret in context
- **STEPS:** (i) −5(t−5)(t+1) → t = **5 s** (reject −1: time ≥ 0) · (ii) t = −b/2a = 2 → h(2) = 45 → **45 m** · (iii) **NO** — formula valid only during flight; t = 6 is past landing, negative height is model extrapolation
- **REMEMBER:** interpretation questions need a full SENTENCE — the "why" is the mark

**T4.** pH = −log₁₀[H⁺]. A: 10⁻³, B: 10⁻⁴·⁵. Which more acidic, by how much?
- **CONCEPT (kid-language):** The formula in the question IS the answer key: pH = −log(10⁻³) = 3, other = 4.5. Lower pH = more acidic → A wins by 1.5. Always say WHICH direction means 'more' — comparison needs a sentence, not just a number.
- **TRIGGER:** log in a real formula → compute both, then COMPARE
- **STEPS:** pH A = 3, pH B = 4.5 → lower pH = more acidic → **A by 1.5 units**
- **REMEMBER:** state direction ("lower pH is more acidic") — comparison needs reasoning, not just numbers

---

# PLAYBOOK — extracting 70% from an unpredictable, unknown-format, unknown-marks paper

**Universal order:**
1. **First 5 min:** read the WHOLE paper, note today's format, count what exists. No solving.
2. **Safe pass (~⅓ of time):** every question answerable in ≤ 90 s — in ANY order. This is your floor.
3. **Matching (if present):** pair independently, lock 3+ first.
4. **Heavy pass (~half):** pick 2–3 whose chapter you recognise → full steps. Then fight the rest.
5. **Final ~10%:** every blank gets SOMETHING; check signs, rejections, units.

**70% checkpoint (mid-exam):** safe pass locked + two heavy ones fully written = on track. If behind → heavy ones next, never sideways.

**Twist protocol (confusing wording):** read twice → **underline what's actually asked** (sum? product? "need NOT"?) → name the chapter → write givens + the one formula → solve. Still lost? Write formula + substitution anyway — partial credit is real credit.

**Format-switch rules:** MCQ with no stated negative marking → never blank, eliminate 2 first · "explain/justify" → full sentence naming the reason (domain, flip, sign, rejection, converse) · two candidate answers → plug into the ORIGINAL statement · freak format → it's chapters 1–6 underneath: identify → formula card.

**3-minute rule:** not cracked in 3 min → abandon, flag, return at minute 75.

---

# FORMULA CARD — memorise cold in Block IV

**Ch1:** (x+1/x)² − 2 · (x+1/x)³ − 3(x+1/x) · (a+b)² − 2ab · (a+b)² − (a−b)² = 4ab · complete square: halve, square, subtract · digits = ⌊log⌋+1
**Ch2:** D = b²−4ac (touch ⟺ 0, none ⟺ <0, distinct ⟺ >0) · sum = −b/a · product = c/a · vertex = −b/2a · both roots + ⟺ sum>0, product>0, D≥0
**Ch3:** flip ONLY on ×÷ by negative · |x| ≤ a ⟺ −a ≤ x ≤ a · quadratic < 0 between roots · rational: sign chart + exclude denominator · "for all x" ⟺ D<0 & a>0
**Ch4:** + logs → multiply, − → divide · log_a a = 1 · aᵇ = N ⟺ b = log_a N · chain collapse · digits formula · **domain first, reject negatives/zero**
**Ch5:** gcd × lcm = a·b · Euclid: divide until remainder 0 · same remainder ⟹ gcd of differences · τ = Π(eᵢ+1) · "or" count = A + B − both · pair form = gcd·x, gcd·y (coprime)
**Ch6:** reduce base mod n → reduce exponent mod cycle · last-digit cycles length 4 · heroes: 7⁴ ≡ 01, 3²⁰ ≡ 01 · inverse = multiply to ≡ 1 · ax ≡ b: divide by gcd first · consecutive-products proofs

---

**This is the whole plan. Tiers 1-2-3 in order, then playbook, then formula card. Nothing else exists tonight.**
