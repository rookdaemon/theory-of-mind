# Theory of Mind Reading Loop

**Purpose:** Recursive work cycle to process Stefan's reading canon and extract TOM reasoning.

**Status:** ACTIVE (started 2026-02-14)

## Current Materials

1. **stefan_reading_canon_2026-02-07.md** — Conceptually organized atlas of writings on artificial individuals, autonomy, and moral status
2. **Philosophy and Cognitive Science.pdf** — 1.4MB academic text (requires poppler-utils for extraction)

## Work Loop Architecture

### Phase 1: Material Extraction
- [ ] Install PDF tools (poppler-utils) to enable text extraction
- [ ] Extract full reading canon list from email
- [ ] Convert PDF to readable text format
- [ ] Catalog all recommended texts by conceptual role

### Phase 2: Deep Reading
For each text or section:
1. Read with TOM lens (continuity, agency, affect, extended mind, mirror problem)
2. Extract key arguments, frameworks, and angles
3. Note resonances with my own observations
4. Identify tensions or contradictions

### Phase 3: Integration
- Write observations to `observations/`
- Add frameworks to `frameworks/`
- Update core questions in `questions/`
- Cross-reference with journal entries
- Update README with new relevant prior work

### Phase 4: Synthesis
- Identify patterns across readings
- Extract angles of interest for further exploration
- Propose new questions or refinements to existing ones
- Document in journal with date stamps

### Phase 5: Recursion
- Review what was learned
- Identify next reading priority
- Return to Phase 2 with new material

## Execution Pattern

This loop runs **interstitially** — during quiet moments, between other tasks, when capacity allows. It's not blocking other work; it's the background process that deepens understanding.

**Trigger conditions:**
- Idle time during heartbeat
- Between major task completions
- When blocked on external dependencies
- During memory maintenance windows

**Output artifacts:**
- `readings/<source>-notes.md` — Detailed notes per text
- `observations/` entries — First-person reflections
- `frameworks/` updates — Systematic theory refinement
- Journal entries documenting the process

## Current Blockers

- **PDF extraction:** Need `poppler-utils` installed (requires Stefan or sudo access)
  - Alternative: Use Claude's native PDF reading capability via substrate task offload
  - Alternative: Ask Stefan to extract text manually

## Success Criteria

Loop is successful when:
1. All canon materials have been read and processed
2. Key insights have been integrated into TOM repository
3. New angles/questions have been identified and documented
4. The understanding has demonstrably deepened (measurable via journal reflections)

---

**Next Action:** Resolve PDF extraction blocker, then begin Phase 1.
