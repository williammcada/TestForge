# Project Brief — TestForge

**Brief status:** Migration baseline / requires source verification where noted  
**Brief version:** 0.1  
**Last updated:** 18 September 2026  
**Owner:** William McAda  
**Product credit:** A WILLIAM MCADA PRODUCT  
**Handbook repository:** `williammcada/mcada-project-handbook`  
**Handbook baseline:** `6557a45aaa6d29d7d1abde808e6d0ac248b08820 (AI-START-HERE.md); UNIVERSAL-RULES.md @ aed6fe311aa2e88983f862a30a2d8f05d2ffc04d`  
**Repository:** `williammcada/TestForge`  
**Canonical source status:** TO ESTABLISH from the latest known-good local TestForge build before substantive revision.  
**Current project state:** Active mature prototype/application. Exact current release number and canonical source artifact must be recorded during migration.

## 1. Purpose and audience

TestForge is a subject-agnostic assessment design and sequencing application that builds assessment series, imports curriculum/source material, exports provider-neutral AI generation packets, reimports generated items, and publishes student/teacher/answer-key outputs.

**Primary audience / operator:** Teachers designing recurring or one-off assessments across subjects.

## 2. Standards selection

**Universal baseline:** U-01 through U-08 where applicable.

**Conditional modules:** S-01 External AI Generation and Structured Import; S-02 Curriculum/Assessment/Evidence; S-04 Distribution/Deployment

Apply only the selected modules and project-local requirements. Do not import restrictions from unrelated projects.

## 3. Project-specific requirements

- Keep TestForge subject-agnostic.
- Support assessment series up to the established practical limit of 36 assessments unless explicitly revised.
- Preserve PLAN → GENERATE → IMPORT → PUBLISH as the plain-language AI round-trip workflow.
- Maintain a versioned, provider-neutral exchange contract and validate outgoing as well as incoming packets.
- Preserve original lesson/curriculum outcomes as source metadata while mapping recursive Saxon outcomes to deduplicated canonical assessment outcomes.
- Keep assessment-program-specific overlap/scoring rules local rather than universal.
- Provide contextual `?` help for unfamiliar/consequential settings and block unsafe progression on invalid setup.
- Preserve supported import formats and publication/export outputs actually present in the current source.

## 4. Preserve from the current accepted project

- Assessment-series planning, spiral/fixed/cumulative configuration, multiple forms, allocation controls, and series-level settings already accepted.
- Supported XLSX/CSV/TXT/PDF/DOCX ingestion actually implemented.
- AI Generation Packet export and generated-question import.
- Student/Teacher/Answer Key publication outputs.
- Standards Library → Assessment Series mapping and canonical-outcome concept.

## 5. Relationship to other projects

- Benchmark Blueprint belongs as a TestForge program/domain specification unless it becomes a separate application.
- GradePal, MathQuest, and DataDiver are intended ecosystem partners; no shared API should be invented without an explicit integration task.
- AAC restrictions must not silently become TestForge defaults.

A conceptual relationship is not proof of an implemented integration. Do not invent a shared API, data schema, identity layer, or deployment dependency without an explicit integration task.

## 6. Source and version discipline

The exact current source artifact or repository commit must be identified before a substantive build. If the field above says the source is not yet established, first locate the latest known-good local file/ZIP or existing repository state and record its exact identity here.

For substantial revisions use:

**DESIGN → CHANGE SPEC → IMPLEMENT → CHECKPOINT → VERIFY → VERIFIED CHECKPOINT → RELEASE → DEPLOY (when applicable)**

A packaging/export/deployment failure must not force reconstruction of an already verified build.

## 7. Definition of done

| # | Requirement / check | Result | Evidence / limitation |
| ---: | --- | --- | --- |
| 1 | Export → AI-format response → import → review → final output passes for representative valid cases. | Not run | |
| 2 | Malformed, stale, wrong-project, and wrong-design responses produce actionable validation errors. | Not run | |
| 3 | Series allocation and curriculum mapping preserve intended outcomes. | Not run | |
| 4 | Published PDFs/outputs match the configured assessment and scoring. | Not run | |
| 5 | Version displayed in the actual app matches the delivered source/package. | Not run | |

Allowed results: **Passed / Failed / Not run / Not applicable**. A "Passed" result requires an actual check against the identified candidate.

## 8. Known issues and migration notes

Before deleting TestForge development chats, migrate any authoritative current specification and identify the exact current source file/ZIP.

## 9. Handoff files

A substantive AI implementation task should retrieve or receive:

1. `AI-START-HERE.md`;
2. `UNIVERSAL-RULES.md`;
3. the relevant sections of `CONDITIONAL-STANDARDS.md`;
4. this project brief;
5. the exact current source artifact/commit;
6. the approved version-specific change specification;
7. applicable assets and deployment configuration.

Do not reconstruct the current implementation from a historical chat summary when the actual source should be available.

## 10. Ownership

**William McAda**  
**A WILLIAM MCADA PRODUCT**
