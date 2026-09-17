# Project Brief — TestForge

**Brief version:** 0.2 — audited documentation revision  
**Owner:** William McAda · **Credit:** A WILLIAM MCADA PRODUCT  
**Status:** Revised record for owner review; not an application release or fresh feature approval.  
**Repository destination:** williammcada/TestForge (verify existence/current branch before source edits).  
**Current running version:** Not independently verified in this documentation task.  
**Source/baseline:** Records identify v1.4 delivery and earlier v1.2 benchmark migration; exact latest HTML and current repository commit remain unverified.  
**Next work:** Establish latest source baseline; preserve v1.4 features; implement canonical-outcome refinement only against an approved change spec.

## 1. Purpose, audience and detailed scope

- Subject-neutral, standalone offline single-HTML assessment design application. No mandatory server, cloud account, CDN, AI API or OCR. External AI generation is a teacher-mediated exchange, not embedded model access.
- Support one assessment, assessment series and year planning up to 36 assessments, spiral/fixed/cumulative planning, equivalent forms by default, allocation overrides, presets and dashboard. Simple/Advanced settings and contextual help must remain.
- PLAN → GENERATE → IMPORT → PUBLISH: plan stable blueprint slots; export complete provider-neutral packet; validate deterministic item import; review and publish student, teacher and answer-key artifacts.
- Import XLSX/CSV/text/PDF/DOCX where supported. Imported standards remain read-only; custom standards editable. Preserve portable project import/export and version migration.
- v1.4 recorded features: automatic current/review lesson sequencing, adjustable new-lesson increment and per-test overrides; independent sequence positions for Investigations (10.1 etc.); visible standard descriptions; series/assessment/item point inheritance.
- DOK 1 and Short Answer default to 100%; distribution totals must equal 100% before finalization. Retain DOK/Bloom settings without importing AAC restrictions.
- Canonical Saxon assessment outcomes remove repeated assessment constructs while retaining original lesson metadata. Track INTRODUCED/REVISITED/EXTENDED; current content follows genuinely first-introduced outcomes, not every recursive lesson mention.
- Preserve stable slot IDs, actual project/design revision, complete examples, outgoing validation, stale/wrong-project rejection, actionable import diagnostics, valid-work preservation and explicit supported migrations.
- Benchmark migration record: 331 objectives, 96 selected targets/claims/locked slots, four 24-item/100-point assessments (20 items at four points, four at five). These are benchmark-program rules, not global defaults.
- Preserve blueprint/packet/project exports and supported JSON/XLSX/PDF/DOCX/study-guide outputs; verify exact output menu against source. Branding and Blueprint Beaver remain.

## 2. This task and boundaries

This revision repairs documentation only. It does not implement features, run application tests, upload source, deploy a site, or alter a repository. Retain the exact current source before implementation. Historical reported functionality is a preservation checklist to reconcile against that source, not permission to recreate the program from prose.

## 3. Standards and adoption

[Canonical handbook](https://github.com/williammcada/mcada-project-handbook). File blob revisions consulted: AI-START-HERE.md 6557a45aaa6d29d7d1abde808e6d0ac248b08820; UNIVERSAL-RULES.md aed6fe311aa2e88983f862a30a2d8f05d2ffc04d; CONDITIONAL-STANDARDS.md dad2d3a05ca0f18260196ea51ac6351bffffdc1c; PROJECT-TEMPLATE.md 574f4c6fcf19ecc2f9e27582fd856fb08123e8da. These are file blobs, not repository commit SHAs.

Relevant rules: U-01 identity, U-02 help, U-03 input validation, U-04 unambiguous math/text where applicable, U-05 reader/device, U-06 preservation, U-07 verification, U-08 local scope. Conditional selection: S-01, S-02, S-04.
Baseline adoption: selected for this documentation task within existing user instructions. Handbook still labels shared scope/modules seeded/draft; no new global rule ratification is inferred. Project-specific approved decisions control their own scope.

## 4. Must-retain behavior

The detailed scope above is the feature-preservation inventory. Preserve existing settings, data, accepted content, assets, exports and compatibility confirmed in source. Distinguish implemented behavior, accepted pending changes and historical requests during intake. A missing entry in this brief is not authorization to remove working behavior. Preserve valid user work during migrations and failures.

## 5. Source, release and deployment discipline

Records identify v1.4 delivery and earlier v1.2 benchmark migration; exact latest HTML and current repository commit remain unverified.

Record exact selected source filename/hash and repository commit when importing it; record live URL/version only after actually opening it. Unknown commit does not mean the product is unbuilt.

DESIGN → CHANGE SPEC → IMPLEMENT → CHECKPOINT → VERIFY → VERIFIED CHECKPOINT → RELEASE → DEPLOY.

Use “implementation checkpoint” or “release candidate” before verification. Preserve candidate bytes and logs before packaging; recover that checkpoint after a ZIP/upload failure. Do not rebuild a verified implementation to fix delivery. Repository upload and website deployment are different operations; existing automatic deployments may run when main changes.

## 6. Known issues, conflicts and open evidence

Prior project/design revision mismatch failures require full export-import-publish regression. Canonical standards mapping is design direction, not proof of completed code. Earlier test claims are historical, not tests rerun here.

| Conflict or risk | Required handling |
| --- | --- |
| Historical claim versus current source | Inspect exact source; keep historical claim labeled until verified. |
| Proposed next scope versus working baseline | Use the approved version-specific specification; do not silently promote proposals. |
| Other project rules | Do not import AAC quotas, other-game retry counts, or a shared backend without explicit scope. |
| Handbook proposals | No additional exception or proposal is adopted by this brief. |

## 7. Verification contract

Round-trip one single and one multi-form series, distributions/point inheritance/investigation ordering, save migration and printed outputs; confirm original curriculum IDs survive canonical mapping.

| Evidence required | Result in this task |
| --- | --- |
| Exact source candidate/commit identified and preserved | Not run — documentation revision only |
| Project-specific checks above, with inputs and expected/actual results | Not run |
| Save/import/export and malformed-input regression | Not run |
| Intended devices and real deployment path, where applicable | Not run |
| Version, release notes and delivered bytes agree | Not run |

The next build report must name the candidate, environment and test results; historical reports of passing tests do not transfer to a changed candidate.

## 8. Handoff and provenance

Required project records: Latest TestForge HTML; portable .testforge.json projects; TESTFORGE_GRADE_5_BENCHMARK_MIGRATION_SPECIFICATION.docx; canonical outcomes mapping; v1.4 release records.

Provenance: previous migration brief and project-history audit in this conversation; directly read dossier/proposal where explicitly stated above. Records not explicitly marked read here are retrieval targets, not claims of fresh inspection. No current app code was tested for this brief.

Before substantive implementation retrieve these records, the current source, approved change spec and applicable handbook. If an indispensable spec is inaccessible, report the gap instead of filling it with invented details. Do not delete unique historical chats/assets until their contents are independently preserved.

## 9. Ecosystem boundary

Shared principles do not establish shared code, accounts or interfaces. MathQuest is engagement, TestForge assessment design, GradePal learner-level evidence, and DataDiver institutional analytics. Integration remains separately specified unless confirmed in source. Other projects remain independent unless their brief explicitly says otherwise.

