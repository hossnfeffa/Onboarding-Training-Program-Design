# Change Log — Onboarding & Training Program Redesign

*Dated revision history across each round of stakeholder feedback. Tool and platform names are generalized to match the redaction approach used throughout this repository.*

## Round 1 — Initial rework

- Added day-one setup for a security-awareness training platform and a business-phone-system softphone, alongside existing account setup
- Removed a legacy team-chat platform reference in favor of the platform actually in use
- Removed a facility-specific monitoring-board walkthrough that no longer matched the current office layout
- Replaced a generic "business team contact" role with the correct "technical account manager" role
- Clarified that certain vendor training is completed through the vendor's own official training portal
- Reordered the curriculum so directory-services/identity fundamentals are introduced before the email-security deep dive (previously the email-security track came first)
- Removed a discontinued bonus-compensation program and its related content from the performance-metrics section
- Removed a client-roster/account-overview section no longer relevant to training
- Removed a training week built around a deprecated troubleshooting tool and a legacy "senior engineer" role that no longer exists on the team, while preserving the certification-planning content from that week

## Round 2 — Scope and resequencing

- Added two new tool introductions (an EDR platform and an MDR service) to day-one account setup and to the curriculum
- Added a mention of a new self-paced online learning platform being made available to new hires
- Renamed the payroll/HR platform reference throughout (the organization switched providers)
- Split a combined identity/cloud-productivity week into two separate weeks to better match a five-day training pace
- Replaced a multi-day certification track for the secure email gateway with a lighter introductory module focused on practical triage questions (locating a message, understanding a block, release process, phishing determination, delivery confirmation)
- Added a dedicated, hands-on identity/MFA training block (SSO, push-based approval, user enrollment, device replacement, authentication-log review) supported by a vendor-provided course
- Trimmed the performance-metrics table to the three measures still in active use
- Moved the network-security certification track into its own training week

## Round 3 — Depth added to new tool training

- Expanded the EDR platform training to include checking protection status, running a scan, reviewing results, and the available response actions on a detected threat
- Expanded the MDR service training to include how incident reports arrive, how to read one, and how its detections differ from the EDR platform's
- Added explicit end-of-week demonstrations for both (run a scan and review results; read an incident report)
- Added corresponding rows to the training sign-off sheet

## Round 4 — Sequencing fix

- Identified that the RMM/monitoring platform and the IT documentation/password-vault platform were being introduced after live ticket work had already started, even though both are prerequisites for working a ticket correctly
- Moved both tools' introductions earlier, into the week immediately before ticket work begins, and confirmed the dependency order end to end

## Round 5 — Timeline and workload rebalance

- Found that one week had become significantly overloaded (six distinct topics, including the start of live ticket work) while two other weeks were comparatively thin
- Rebalanced the six-week structure:
  - Split the overloaded week, keeping the quick tool walkthroughs (RMM/monitoring, IT documentation) with their related content and giving live ticket work its own dedicated week
  - Merged the two lighter weeks (performance metrics and the network-security certification track) into a single week, since both are short on their own
- Verified the final structure keeps every dependency (tool knowledge before the live work that requires it) intact after the rebalance
