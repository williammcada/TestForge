# TestForge — Next-Release Assessment Architecture

**Status:** Accepted design direction; implementation/version is not established here.

## Change

Retain the plain-language **PLAN → GENERATE → IMPORT → PUBLISH** workflow while strengthening series planning, standards mapping, and validated AI round trips.

- Support up to 36 assessments in a series.
- Map original Saxon lesson outcomes to deduplicated canonical assessment outcomes; retain the original outcomes as curriculum metadata.
- Map Standards Library entries to Assessment Series.
- Default DOK checking to DOK 1 = 100% unless the teacher changes it.
- Use provider-neutral, revisioned generation/import packets; validate the outgoing packet and incoming result before progressing.
- Keep assessment-program-specific scoring and overlap rules local, not global defaults.

## Acceptance checks

| Check | Result |
| --- | --- |
| A series plan round-trips without losing settings or mappings | Not run |
| Invalid configuration blocks generation with a useful correction | Not run |
| Imported items preserve form, outcome, and answer data | Not run |
| Student, teacher, and answer-key outputs agree | Not run |
