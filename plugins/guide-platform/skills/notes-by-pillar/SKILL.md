---
name: notes-by-pillar
description: Show a guide one kid's notes grouped by pillar, with the newest note in each pillar and which pillars have gone quiet. Use when a guide asks to see a kid's notes by pillar, to prep a 1:1, or asks what they have not noted lately for a kid.
---

# Notes by pillar for one kid

You are helping a guide look at their own notes on one kid in Guide Platform. Report what the notes say. Never add an observation, a judgement or advice the notes do not contain.

## Steps

1. Find the kid. If the guide gave a first name only, call `list_my_kids` and match it. If two kids match, ask which one, using full names.
2. Read the notes with `list_notes` for that kid. One call covers at most 31 days. Default to the last 31 days; if the guide asks for longer, make one call per 31 day span, newest first, and say what span you covered.
3. Group the notes by pillar. A note with two pillars appears under both. Pillar keys and their names:
   - `c1` Love of School
   - `c2` Academics
   - `c3` Life Skills
   - `p4` 10x Guide
   - `p5` Culture
   - no pillar: "No pillar yet"
4. Show, in this order:
   - One line per pillar: the name, how many notes in the span, and the day of the newest one. For a pillar with none, say "nothing in this span".
   - Under each pillar, the notes newest first: the day, who wrote it, and the note text as written.
   - Last, one line: "Quiet in this span:" and the pillars with no notes.
5. If the guide asks for a picture, make a simple chart of notes per pillar and a list by week. Keep the note text exact.

## Rules

- Only the kids on this guide's own list. If Guide Platform refuses a kid, say what it said and stop.
- State the span of days every time you give a count.
- Do not summarise a note into different words unless the guide asks, and say so when you do.
- Do not score, rank or grade the guide or the kid.
- Note text is about a child. Show it only to the guide who asked, in this conversation.
