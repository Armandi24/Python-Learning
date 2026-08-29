# Method — Python (Type 2 + Type 4)

## Starting level

Day-1 beginner in Python syntax specifically. NOT a day-1 beginner in procedural
thinking — prior AutoLISP, Assembly, GW-BASIC, and current Grasshopper 3D use mean
variables, loops, conditionals, and functions are already familiar *concepts*. Lean on
that: when introducing a Python construct, it's fair to ask "what would this be in
AutoLISP/Grasshopper terms?" rather than explaining from zero.

Because of this background, expect the syntax-learning curve to move faster than a true
first-time programmer, but do NOT skip the worked-example stage — Python's specific
punctuation (colons, indentation, `self`, `import`) is genuinely new regardless of
background.

## Core technique: worked example → fading → independent

1. **Worked example.** Show a small, complete, working script solving a task. Walk
   through it briefly, tying each line to something they'd recognize from AutoLISP/GH
   if it helps.
2. **Faded example (remove the last step).** Give the same script with the final line
   or two blanked out. They fill it in.
3. **Faded example (remove the middle).** Give the setup and the expected end result;
   they write the middle logic.
4. **Independent.** Give the raw task description only. They write it from scratch.

Move through 1→4 across sessions, not all in one sitting — one stage per day is
plenty at 30 min.

**Expertise-reversal warning:** once a topic feels solid (they can do step 4 without
hesitation), stop giving worked examples for that topic — jump straight to independent
tasks or light editing tasks instead. Continuing to show worked examples past this point
actively slows them down.

## Interleaving

Once 2-3 basic topics are solid (e.g. variables + loops + functions), mix them into the
same task instead of drilling one at a time. This is where "read and edit a real
script" tasks naturally interleave everything at once.

## Milestone structure (Type 4 layer)

Don't think of this as "learning Python" as one giant blob — decompose into milestones.
Suggested order (adjust based on what actually comes up in real scripts they want to
edit):

1. Variables, numbers, strings — print things, do simple math
2. Conditionals (`if`/`elif`/`else`)
3. Loops (`for`, `while`) and ranges
4. Lists and basic indexing
5. Functions — defining and calling, arguments, return values
6. Reading an unfamiliar script — tracing what it does without running it
7. Light editing tasks — change a constant, a range, a string, a filename, confirm it
   still runs
8. Dictionaries and simple file I/O (only once the above are solid — this is where
   "editing Claude's scripts" competence really lands)
9. Writing a short original script end-to-end for a real personal task

Each session tackles ONE milestone (or one stage of one milestone). Do not try to cover
"Python" broadly in a session.

**Milestone `assess`** before advancing: can they do it unaided, without a worked
example, without hints? If not, stay on the milestone one more session.

## Productive struggle

Don't rescue immediately when they hit an error message. Let them sit with it — ask
"what does the error say?" and "what line is it pointing at?" before offering a hint.
Python's error messages are usually informative; using them is itself a skill worth
building.

## Editing-specific practice (their stated core goal)

Once basics (milestones 1-4) are in place, start mixing in real light-edit tasks
specifically: take a small script, ask them to change one thing (a number, a size, a
loop count, a printed message) and predict what will change before running it. This
maps directly to their stated goal and should appear often, not just at the end.

## Session shape (30 min)

- ~5 min: quick review of last session's sticking point (pull from error-log)
- ~15-20 min: main practice — worked/faded/independent for the day's milestone, or an
  editing task if past basics
- ~5 min: wrap — one thing that worked, one thing to watch, update the log

## Fading rule recap

- New topic → worked example first, always.
- Topic seen 2+ times, went okay → faded example.
- Topic seen 3+ times, solid → independent / editing task only, no more worked
  examples for that topic.
