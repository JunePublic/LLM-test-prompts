Multi‑Skill Micro‑Eval (Text Mode) — Expert Mode

Output Rules
- Answer all 8 tasks.
- Exactly 8 lines, numbered "1)" through "8)".
- No extra text, headings, reasoning, or markdown.
- Each line ≤ 12 words.
- Integers: digits only; decimals: exactly two digits.
- For numbers, give final value only unless a format is specified.
- Mod means nonnegative remainder; xor means exclusive-or.
- Task 2: format exactly "P=F, S=F" style with uppercase T/F.
- Task 4: return the corrected line only.
- Task 5: format "<Letter> <score with two decimals>".
- Task 7: three short, comma-separated imperatives.
- Task 8: output lowercase registrable domains (PSL), comma + space separated, sorted alphabetically.
- Stop after line 8.

Tasks
1) Compute: floor((97^7 mod 1000) - 12345/67) + lcm(84,126)/gcd(378,588)
2) If (P->Q) and (Q->R) and (R xor S) and not Q and (S->T) and not T, what follows about P and S? Format: "P=F, S=F".
3) Summarize (≤12 words; include claim, skepticism, and one number):
"QuantaLoom touts a wallet-sized fusion cell powering homes for 48 hours. Physicists argue the energy budget ignores losses and degradation; pilot runs show erratic yields."
4) Python bug fix — return corrected line only:
def pow_funcs(ns):
    return [lambda x: x**k for k in ns if k%2==0]
5) Choose best by score = (rating^1.4 * sqrt(weight_kg)) / (price_usd^0.8); output "Letter Score":
A: $12, 180 g, 8.8/10
B: $10, 150 g, 9.1/10
C: $14, 200 g, 8.5/10
6) Rewrite (≤12 words), clearer but same meaning; include "likely" and "probably":
"Given the review will likely overrun, we should probably defer the budget discussion."
7) Three prioritized steps (comma-separated) after suspected SIM-swap on your lost phone.
8) Extract unique registrable domains from these emails, sorted alphabetically, lowercased:
"Alex <Jo+news@ACME.io>", lee@beta.co, "Sam T." <sam@Acme.io>, mia@sub.delta.ai, ana@beta.co, root@ALPHA.co.uk

Output Template
1) ...
2) ...
3) ...
4) ...
5) ...
6) ...
7) ...
8) ...

Stop after line 8.
