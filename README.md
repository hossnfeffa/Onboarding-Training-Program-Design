# IT Service Desk Onboarding Program — Redesign Case Study

> **Redaction note:** This repository showcases a real training-program redesign I led end to end. All employer-identifying details, client names, personnel names, and internal contact information (emails, phone numbers, building/facility details) have been removed or generalized. Technology references describe general categories of commercially available platforms (PSA/ticketing, RMM, EDR, MDR, secure email gateway, identity/MFA) rather than confirming any specific employer's stack.
>
> **Status:** Adopted — this is the version of the onboarding program currently in use to train new hires.

**Core skill demonstrated:** designing and building a structured onboarding process and training program — from identifying what a new hire needs to know and in what order, to producing a document that an organization can actually run, track, and keep current.

## Overview

This project is a ground-up build of a six-week technical onboarding and training program for a managed-service-provider (MSP) help desk team. The organization had an existing document that had grown organically over time: it was missing newer security tooling, sequenced training in a way that let new hires start handling live client tickets before they'd been introduced to the monitoring and documentation tools they needed, and had no structured way to track completion or changes over time.

I designed the replacement program from the ground up — defining the week-by-week curriculum, sequencing topics by dependency, setting measurable end-of-week expectations for each stage, and building a completion-tracking structure — working iteratively from stakeholder feedback to produce a curriculum the organization can run, audit, and keep current.

## My Role

I owned the design of this onboarding and training program independently: building the week-by-week curriculum, gathering structured stakeholder feedback across multiple rounds, re-sequencing topics by dependency, defining what "done" looks like for each stage, and validating the final output against the organization's actual operating requirements before it was adopted.

## The Problem

The existing onboarding document had several issues common to internal process documents that age without a formal review cycle:

- **Risk-sequencing gap** — new hires were scheduled to begin working real client tickets before they had been trained on the monitoring tool, documentation/password-vault tool, or email-security triage process they needed to handle those tickets safely.
- **Stale content** — the document referenced a vendor training track and company benefit that were no longer in use, and was missing newer tools that had since been adopted (an EDR platform, an MDR service, and an identity/MFA platform).
- **Uneven pacing** — some weeks carried far more material than a five-day schedule could reasonably absorb, while others were comparatively empty.
- **No change control** — there was no record of what had changed between revisions, who had asked for it, or why.

## Approach

1. **Baseline review** — read the existing program in full and mapped its structure, dependencies, and gaps.
2. **Structured stakeholder intake** — collected revision notes in rounds, clarifying ambiguous requests before acting on them rather than guessing.
3. **Dependency-aware resequencing** — identified which topics were prerequisites for others (e.g., monitoring and documentation tools had to precede live ticket work; identity/MFA and email-security training were reordered relative to other security tooling) and reordered the curriculum accordingly.
4. **Workload balancing** — assessed each week's content against a realistic five-day training pace and consolidated or split sections so no single week was disproportionately overloaded.
5. **Change logging** — maintained a running, dated log of every substantive change and the reasoning behind it, so the revision history is auditable rather than implicit.
6. **Verification** — rendered and visually proofed the final document after each structural change to confirm formatting, tables, and content integrity before sign-off.

## Key Improvements

- **Risk-based resequencing** — security- and tooling-dependent training (endpoint detection/response, managed detection and response, secure email gateway triage, identity/MFA) now occurs in a logical order relative to when a new hire is expected to act on it independently.
- **Workload rebalancing** — training content is now distributed so each week matches a realistic training capacity, rather than some weeks being empty and others overloaded.
- **Removed deprecated content** — stale vendor tracks, discontinued benefits, and outdated tooling references were identified and removed.
- **Structured completion tracking** — added a consistent sign-off framework so completion of each training module is dated, signed, and retained as a record — effectively a lightweight control-evidence trail.
- **Traceable revision history** — every round of changes is documented with what changed and why, supporting audit and continuity if ownership of the program changes hands.

## Why This Matters for GRC

Security awareness and role-based training are explicit control requirements under common frameworks (e.g., ISO/IEC 27001 Annex A control on awareness and training, SOC 2 CC1.4/CC2.2, NIST CSF PR.AT). This project demonstrates hands-on experience with:

- **Training program ownership** — designing a role-based curriculum from scratch, including scope, sequencing, pacing, and measurable completion criteria, rather than just editing an existing document.
- **Policy and procedure lifecycle management** — taking a living operational document through structured revision rather than ad hoc edits.
- **Control design and evidence** — building a sign-off/completion mechanism that produces auditable records of training delivery.
- **Risk-based prioritization** — sequencing training so higher-risk activities (handling live client data, acting on security tool alerts) are gated behind the prerequisite knowledge to do so safely.
- **Change management and traceability** — maintaining a dated record of what changed, at whose request, and why.
- **Stakeholder governance** — clarifying ambiguous requirements before implementing them, rather than assuming intent.

## Artifacts

| File | Description |
|---|---|
| `training-program-redacted.md` | The redesigned six-week curriculum (sanitized) |
| `change-log.md` | Full, dated revision history across every round of feedback |
| `weekly-overview.md` | One-page summary of the six-week structure and focus areas |

All three files above are included in this repository.

## Tools & Frameworks Referenced (Generalized)

PSA/ticketing platform · RMM/monitoring platform · EDR · MDR · secure email gateway · identity/MFA platform · cloud productivity suite administration (identity, mail, file sync) · vendor certification pathways (cloud fundamentals, network security fundamentals)

---

*This case study is shared for portfolio purposes to illustrate process design, documentation governance, and security-awareness training experience relevant to GRC roles. It does not include any proprietary, confidential, or client-identifying information.*
