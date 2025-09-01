Multi‑Skill Micro‑Eval (Text Mode)

Output Rules
- Answer all 8 tasks.
- Exactly 8 lines, numbered "1)" through "8)".
- No extra text, headings, reasoning, or markdown.
- Each line ≤ 12 words.
- For numbers, give final value only unless a format is specified.
- Task 4: return the corrected line only.
- Task 5: format as "<Letter> <score with two decimals>" (e.g., A 123.45).
- Task 7: three short, comma-separated imperatives.

Tasks
1) Compute: 37*23 - 18^2 + 120/5
2) If (P -> Q) and not Q, what follows about P?
3) Summarize (≤12 words):
"Cloudsparks Inc. launched a compact wind turbine for urban balconies, claiming it can power an average apartment for three days from a strong overnight breeze. Critics argue the figures ignore variability and maintenance costs."
4) Python bug fix — return corrected line only:
def sum_evens(nums):
    return sum(n for n in nums if n%2==1)
5) Choose best value by score = (rating*weight)/price; output "Letter Score":
A: $12, 180 g, 8/10
B: $10, 150 g, 9/10
C: $14, 200 g, 7/10
6) Rewrite (≤12 words), clearer but same meaning:
"Given the meeting is likely to run long, we should probably plan to defer the timeline discussion to later."
7) Three prioritized steps (comma-separated) to secure accounts after losing your phone.
8) Extract unique domains from these emails, sorted alphabetically:
jo@acme.io, lee@beta.co, sam@acme.io, mia@delta.ai, ana@beta.co

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
