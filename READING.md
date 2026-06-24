# Blood Under Ice — Best Way to Read the Current Draft

**Project:** Blood Under Ice (Book One)  
**Current status:** 36 chapters written (up to "The Road's Due")

## Recommended Reading Method (Easiest)

**Use the single combined file:**

```bash
cd /home/alex/.openclaw/workspace/blood-and-ice

# Best experience in terminal
less reading-versions/current-draft-full.md

# Or open in your editor
code reading-versions/current-draft-full.md
# or
vim reading-versions/current-draft-full.md
```

**Why this is best:**
- Everything in one file (no jumping between folders)
- Clean "Chapter X: Title" headings
- Easy to search (`/Chapter 29` or `/Rook` etc.)
- 286 KB — comfortable to scroll/search

## Reading Order (Context First)

1. `README.md` — quick project overview
2. `docs/story/book-one-outline.md` — full planned structure
3. **`reading-versions/current-draft-full.md`** — the actual story (start here for prose)
4. `docs/continuity/next-scene-queue.md` — **very important** — tells you current frontier, what's been done, and exactly what's coming next (ch37-38 peak crisis)
5. `docs/style/voice-guide.md` — how the prose is supposed to feel

## Alternative: Browse by Parts (if you prefer folders)

```
manuscript/book-one/
├── part-01-wild-boy/           (ch 1-3)
├── part-02-four-tribes/        (ch 4-7)
├── part-03-white-pit/          (ch 8-10)
├── part-04-blood-crown/        (ch 11-20)
├── part-05-after-crown/        (ch 21-24)
└── part-06-fracture-and-system/ (ch 25-36)   ← current work
```

## Quick Navigation Tips

In `less`:
- `/Chapter 20` → jump to chapter
- `G` → go to end
- `?word` → search backwards
- `q` → quit

In most editors: search for `## Chapter 29`

## Quick Status (as of 2026-06-17)

- Packet 6 (ch33-36, "Winter Ledger") is complete
- Next major work: ch37-38 (live public wrapped-spear caller test under crisis)
- Book One target: ~40-42 chapters total
- Ends with first external/mainland signal as cliffhanger

See `docs/continuity/next-scene-queue.md` for the detailed current plan.
