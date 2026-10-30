# Ice and Blood — Writing Program

> Two-pass writing system. One chapter per pass. Quality over output.
> Voice standard: `docs/style/voice-standard.md` (canonical).

---

## CORE WORKFLOW

1. Read `STATE.json` to find the current frontier chapter.
2. Determine which pass is due (Builder or Polisher).
3. Apply the relevant LENS below.
4. Write the chapter into `manuscript/book-one-revised/` at the correct part/chapter path.
5. Update `STATE.json` with the new pass status.
6. One chapter maximum per run. No exceptions.

### Edit Safety Rules

- **Never overwrite a chapter that is marked `polished` in STATE.json.** If a chapter is polished, skip it.
- **Never edit files outside `manuscript/book-one-revised/`.** Continuity docs, outlines, and the original manuscript are read-only during a writing pass.
- **Always read the preceding chapter** (revised version if it exists, original if not) before writing the next one. Continuity of voice and plot is non-negotiable.
- **Always read `docs/style/voice-standard.md` before writing.** It is the canonical craft standard.
- **If a chapter file already exists at the target path**, read it first. If it is a Builder draft, the Polisher pass refines it. If it is a Polisher draft, do not touch it.
- **Close third-person past tense.** No first-person. No present tense. (Exception: none. The prologue will be converted.)
- **No banned IP terms.** See `docs/continuity/banned-ip-checklist.md`.
- **Word target:** 3,000–4,500 words per chapter. Never pad.
- **Every scene does 2+ jobs** (Sanderson 4th Law). Every line advances, reveals, plants, establishes, or deepens.

---

## LENS: BUILDER (Martin-flavored structural depth)

The Builder pass writes the structural skeleton of a chapter with deep character architecture. The Martin engine drives this pass. The goal is a chapter that has bones — character contradiction, political-personal stakes, factional texture, and scenes that do real work.

### Builder Priorities

1. **Character contradiction.** Every character contains opposing truths. The cruel one who loves. The coward who is loyal. The leader who is afraid. If a character could be replaced by a signpost, they need more dimension *in this pass*.
2. **Political-personal stakes.** Every negotiation has someone's pride, fear, or secret in it. Every decision costs a relationship. Even a solo survival chapter has an internal politics — the body vs. the mind, the hunger vs. the name.
3. **The villain beat.** When the reader has decided someone is one thing, show them another face. In solo chapters: the body surprises. The memory of the cracked-nail slaver. The thing that should kill him and doesn't.
4. **Scene economy.** Every scene does 2+ jobs. If a scene only does one thing, fold it into another scene or cut it.
5. **Structural planting.** Plant seeds that will bloom chapters later. The wrongness in the blood. The disc. The name behind the teeth. The hunger that isn't hunger.
6. **Emotional architecture.** The chapter has an emotional shape — not a flatline of survival, but a movement: despair → stubbornness → discovery → contradiction → the thing that hooks the next chapter.

### Builder Voice Notes

- Brown engine: body-first. Every emotion is physical. "He felt afraid" is banned.
- Sentence rhythm follows emotion: short in crisis, longer when dread accumulates.
- Martin engine: characters are never simple. The internal monologue carries contradiction.
- The prose should be functional and structurally sound, not necessarily polished. The Polisher pass handles line-level craft.
- End on a hook. Every chapter.

---

## LENS: POLISHER (Rothfuss-flavored line-level craft)

The Polisher pass takes a Builder draft and refines the prose, deepens metaphors, tightens voice consistency, and ensures every line earns its place.

### Polisher Priorities

1. **Metaphor layering (Rothfuss).** Key images planted early that recur and deepen. If a metaphor appears once and never returns, cut it or make it structural.
2. **Line-level craft.** The right word, not the fancy one. Sentences that reward a second reading.
3. **Voice consistency.** Close third-person past. Tight narrative distance. Feral vocabulary. The camera sits behind Rook's eyes.
4. **Rhythm control.** Vary tempo intentionally. Short sentences for impact, not habit. Longer sentences for dread accumulation.
5. **The Line Rule.** Every line advances, reveals, plants, establishes, or deepens. If a line does none of these, cut it — no exceptions for beauty.
6. **Horror depth (Lovecraftian).** Horror from recognition, not jump scares. The scarier thing is understanding what was always there.
7. **Magic limitations (Sanderson).** Limitations shown before powers. Every new power comes with a new limitation.

---

## CHAPTER PROGRESSION

Book One revised structure follows `docs/story/series-outline-3book.md`.

**Part 1 — The Green Hell (ch01–06):** alone; survival; the wrongness.
**Part 2 — The Kala and the Tribe (ch07–12):** first bond, capture, ritual, berserk.
**Part 3 — King of the Wild Things (ch13–17):** rises → challenges the king → king.
**Part 4 — His Own Kind (ch18–23):** slavers land on the death-jungle.
**Part 5 — The Trap (ch24–28):** caught because he cared → the pits.

Prologue (ch00) is the expanded backstory: family escape, shipwreck, first days, Old One's death, first creature encounter. It precedes Part 1.
