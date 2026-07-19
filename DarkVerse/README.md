
Open `index.html` to run the site. Every internal link is relative, so
**keep this folder structure intact** — if you move `index.html` out on
its own, the family and spoiler links will break.

## On the reference family-tree image and the "70+ character" feature list

Two things came in alongside this request worth being straight about:

**The Netflix family tree image** is genuinely as complex as it looks —
around 50+ named nodes across two mirrored worlds, several surnames
that never appear in the show's dialogue (Tannhaus's own ancestors,
the Alders and Krüger lines), and an infinity symbol standing in for
the fact the whole chart loops back on itself. That's real complexity,
not something to flatten into one diagram. The `families/` pages are
the answer to it: one hierarchical tree per surname instead of one
overwhelming web, plus the full recursive picture spelled out in prose
on the spoilers page, since some of it genuinely doesn't diagram well
(the same person appearing at three ages isn't a family relationship,
it's identity — that's handled as text, not as tree nodes).

**The full "DARKVERSE — FEATURES TO ADD" list** (70+ characters with
gallery/quotes/multiple world versions each, nine simultaneous graph
types, a full accessibility audit, etc.) is a real product roadmap, not
something this pass builds. What's in `index.html` right now is 19
characters with verified actor/timing data, one relationship graph's
worth of connections, and the episode-driven unlock engine — accurate
and tested, rather than wide and speculative. Worth flagging: the
"Complete Content Database" document this project pulled some
corrections from also contains a number of invented-sounding details
(objects like "the mirror device" or "the disappearing orb," some
contradictory family claims) that were **not** carried into this
build — treat that document as a mix of real and fabricated content,
not a verified source on its own.

## What's genuinely implemented right now

- Episode-based journey engine (season + episode is the single source
  of truth; characters/locations/mysteries/symbols/timeline unlock
  progressively, with visible locked states)
- 19 characters with corrected first-appearance timing
- Full episode list (26 episodes, 3 spoiler tiers: Safe / Moderate / Full)
- Timeline explorer, Mystery tracker, Symbol tracker, Viewing journal
- Global search (respects your unlock progress)
- Live AI chat (3 personas, aware of your current episode)
- 6 dedicated family-tree pages + 1 hub
- A separately-gated full-spoiler reference page
