# Migration Baseline — TestForge

**Recorded:** 18 September 2026  
**Repository:** `williammcada/TestForge`  
**Branch:** `main`  
**Source-preservation checkpoint:** `b8ccc620d9e57128d2f9fb2c3c81cc43b7d379d9`  
**Record status:** Current source identity. This is not by itself a functional-test, release, or deployment claim.

## Canonical source identity

| Field | Value |
| --- | --- |
| Canonical source path | `TestForge_v1.4.html` |
| Git blob SHA | `18fc211240c225fe506e9e35caccd6eaddde89de` |
| Version represented | v1.4 source baseline |
| Repository source checkpoint | `b8ccc620d9e57128d2f9fb2c3c81cc43b7d379d9` |

The checkpoint above identifies the application/planning source immediately before this normalization record was committed. Later documentation-only commits do not change the preserved application bytes.

## Verification status

| Check | Result | Evidence / limitation |
| --- | --- | --- |
| Source exists in the default branch | Passed | Repository paths and Git object identities were read directly on 18 September 2026. |
| Byte-preservation comparison | Passed | Passed — the Git blob matched the preserved Library source during the 18 September 2026 audit. |
| Functional workflow | Not run | Source preservation does not establish that imports, gameplay, reports, storage or exports work. |
| Hosted/running application | Not run | Not verified; TestForge is preserved as a standalone offline HTML application. |

## Documentation authority

- [`PROJECT-BRIEF.md`](PROJECT-BRIEF.md) records purpose, scope, must-retain behavior and verification requirements.
- [`change-specs/INDEX.md`](change-specs/INDEX.md) identifies approved or directional change records.
- [`MIGRATION-NOTE.md`](MIGRATION-NOTE.md) is retained as historical migration context but its pre-upload source-status language is superseded by this baseline.
- This file controls current source identity when an older brief or note says the source was unknown or “TO ESTABLISH.”

## Next gate

Use the committed v1.4 source as the canonical baseline; implement canonical-outcome refinement only against an approved change specification and full round-trip verification.

Do not label a future commit a verified release until the exact candidate has passed the project brief’s required verification and that evidence is preserved.
