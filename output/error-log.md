# Error log

Format: `date | milestone | mistake | correction | times seen`

Log a mistake the first time it happens and bump "times seen" if it recurs — recurring
items are what `review` pulls from. Move an item to Fixed once it stops recurring
(3+ correct in a row / mastery gate passed for that specific point).

| date | milestone | mistake | correction | times seen |
|------|-----------|---------|------------|------------|
| 2026-08-25 | 1 | Predicted `a + b` (12,4) would print "12" (digit-concat intuition) instead of 16 | Pointed at the line; self-explained correctly after seeing actual output | 1 |
| 2026-08-25 | 1 | Didn't know why `a/b` prints `3.0` not `3` | Told directly (not self-discovered): `/` always returns float in Python; `//` gives floor/int division | 1 |
| 2026-08-26 | 1 | Assigned string without quotes (`name=Mohamad`) → NameError | Self-explained after error: strings need `""` | 1 |
| 2026-08-26 | 1 | Used hyphens in a variable name (`apple-per-bag`) → SyntaxError | Pointed at line; realized `-` is parsed as subtraction | 1 |
## Fixed

(move rows here once solid)

| 2026-08-26 | 1 | Predicted reassigned var (`x=.../` then `x=...//`) would show the `/` result (3.0); missed that 2nd assignment overwrites 1st | Self-caught after running, but prediction itself was wrong — reassignment/overwrite not yet internalized | 1 — fixed 2026-08-30, 4/4 unaided incl. variable-to-variable copy case |
