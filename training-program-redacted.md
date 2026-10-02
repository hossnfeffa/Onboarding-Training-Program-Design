# IT Service Desk Onboarding & Training Program (Sanitized)

*This is a redacted/generalized version of a real six-week onboarding and training program I designed for a managed-service-provider (MSP) help desk team. Organization name, client names, personnel names, and internal contact details have been removed. Specific commercial product names have been replaced with their general platform category, consistent with the redaction approach described in the repository README.*

## Purpose

This document outlines the training program for a new help desk technician, giving the new hire a clear understanding of what to expect and providing a consistent, repeatable training path for the desk.

## Scope

This process applies to the support desk and covers the first six weeks of employment, along with what to expect during the first year. The document is provided to the new technician on day one as a reference guide.

## Week 1 — Accounts, Introduction, and the Ticketing Platform

Shift during training runs 8am–5pm with a 12pm–1pm lunch. After six weeks, shift and lunch scheduling can shift to meet staffing needs, at the supervisor's discretion.

### Monday

- Log into accounts (supervisor assists):
  - Workstation and email (web portal first, then the desktop mail client)
    - Install an authenticator app on a personal or work phone
  - Team chat/collaboration platform
  - Security-awareness training platform (complete initial modules)
  - Business phone system (softphone setup)
  - Payroll/HR platform (watch for a welcome email with setup instructions)
  - Secure email gateway (user + admin console)
  - PSA/ticketing platform and its automation console
  - Ticketing vendor's official training portal
  - RMM/monitoring platform
  - IT documentation & password-vault platform
  - EDR (endpoint detection & response) platform
  - MDR (managed detection & response) service
  - Remote support tool
  - Data-protection/compliance platform
  - Virtual desktop/remote access platform
  - An online learning platform (additional self-paced courses made available here)
- HR items (scheduled by HR on day one):
  - Meet with HR, badge photo, remaining paperwork
  - Building tour (supervisor-led): floor levels and shared spaces (break area, snack purchasing, restrooms, fitness area); badge access setup and testing
  - Team introductions: tiered support roles, field engineers, account managers, security, and leadership
  - Payroll platform walkthrough: clocking in/out, requesting time off, submitting a time adjustment
  - Overview of departments across the organization (support tiers, field engineering, systems/infrastructure engineering, voice/telephony, sales, billing, security, leadership)

### Tuesday

- Overview of a typical day
- Payroll platform: clocking in, lunch, clocking out
- Ticketing platform time tracking: creating a ticket with proper handling; time-entry categories (lunch, staff meeting, PTO, sick, clock calculations)
- Ticketing platform overview: contact channels (phone, email, chat, support portal), favorite tabs, board layout, SLA priority levels (color-coded 1–5, with a printed/emailed reference chart), ticket statuses and their meaning, searching tickets/companies/contacts, and finding the account team assigned to a company (engineer + technical account manager)
- Shadow assigned teammates
- Begin the ticketing vendor's official training series (tracked on the program's sign-off sheet)

### Wednesday

- Continue payroll and ticketing time-tracking review
- Demonstrate creating a ticket with proper handling
- Review credit-hold process: escalation email format, who approves release, and how holds appear on a ticket
- Review ticket configuration requirements (every ticket worked needs an associated configuration item; create one if it doesn't exist)
- Shadow assigned teammates; continue vendor training series

### Thursday

- Review time-off and call-out-sick procedures (platform steps, required email format, notice expectations)
- Review service agreement types and how to identify them on an account (managed services, voice, monitoring, security, time & materials)
- Review ticket documentation standards, audit trail review, and the root-cause-analysis (RCA) process and triggers
- Team chat platform channel review: channel purposes and how to escalate a ticket
- Shadow assigned teammates; continue vendor training series

### Friday

- Review role expectations document and sign
- Review new computer build process and hardware package tiers
- Time for benefits enrollment and direct deposit setup
- Shadow assigned teammates; continue vendor training series

## Week 2 — Directory Services, Group Policy, and Permissions

### Training

- Directory services administration: browsing group membership, the advanced attribute editor, enabling advanced view features, finding/resetting a user, security groups, mail-routing protocol basics, adding an alias, organizational units
- Group policy: navigating policies, reviewing mapped drives
- Permissions: how they're applied, best practices, checking folder permissions
- Begin self-paced cloud-fundamentals certification coursework (two related tracks), continuing across the week
- Shadow assigned teammates daily

### End of week expectations

- Demonstrate checking a password's last-updated date, searching for a user, finding a user's group memberships, and adding an alias in directory services
- Explain the routing-protocol distinction covered in training
- Progress check-in on certification coursework

## Week 3 — Cloud Productivity Suite, Modern Workplace, Event Logs, MFA Overview, and Core Platforms

### Training

- Cloud productivity suite administration: mail forwarding and message trace, spam/allow-list handling (and its interaction with the secure email gateway), distribution/security/dynamic groups, reviewing another user's mailbox, license management, granting full mailbox access, and where licensing/mailboxes are managed
- Modern workplace fundamentals: cloud-identity-joined devices, reviewing sign-in logs, file-sync tools and the two ways to sync a shared folder, team-chat file access/sync, troubleshooting sync errors, recovering a deleted file (30-day window)
- Event log review for diagnosing application/system issues
- MFA overview: the organization's MFA platform, the cloud suite's built-in MFA option, and a password manager (deeper hands-on MFA training happens in Week 5)
- Continue certification coursework
- RMM/monitoring platform: dashboard overview and where alerts appear
- IT documentation platform: finding a client, looking up credentials (domain admin, cloud tenant, local admin), finding/creating client documents, quick-navigation shortcuts
- Shadow assigned teammates daily

### End of week expectations

- Identify how directory services and the cloud suite indicate sync status
- Demonstrate forwarding an email and granting full mailbox access
- Explain the difference between a security group and a distribution group, and between a virtual-desktop and persistent-desktop delivery model
- Name the MFA methods used across the customer base
- Pass the certification exams (per the tech's cert plan)
- Demonstrate comfort navigating the IT documentation platform (finding companies, credentials, and documents; creating/editing documents)

## Week 4 — Automated Alerting and Live Ticket Work

### Training

- Automated monitoring tickets: how they're generated and common categories (low disk space, server offline, failed backup jobs, a stopped service, a missing application/service)
- Shadow assigned teammates daily
- Begin working tickets assigned by the supervisor (new-hire provisioning, account terminations/disables, email forwarding requests, new distribution groups)

### End of week expectations

- Identify common automated-ticket categories and their likely causes
- Successfully work and close assigned tickets with proper documentation and a configuration item attached

## Week 5 — Endpoint Security, Email Security, and Identity/MFA (Deep Dive)

### Training

- EDR platform: what it protects against, checking agent/protection status, running a scan, reviewing scan results, available response actions (quarantine, kill, remediate/rollback), and escalation
- MDR service: what it protects against, how incident reports arrive and where to review them, how to read a report, how its detections differ from the EDR platform's, and escalation
- Secure email gateway (applied): tracing a message, understanding why it was blocked, the release process, phishing triage, and delivery confirmation
- Identity/MFA platform (hands-on): what MFA and SSO are, how push-based approval works, enrolling a user, replacing a user's registered device, and reviewing authentication logs (supported by a vendor-provided training course)
- Shadow assigned teammates

### End of week expectations

- Describe what the EDR platform protects against and demonstrate running a scan and reviewing the results
- Explain the available response actions on a detected threat
- Describe what the MDR service protects against and demonstrate reading an incident report
- Explain how an MDR detection differs from an EDR detection, and when/how to escalate either
- Work a sample secure-email-gateway case end to end (locate, diagnose, determine phishing status, confirm delivery, and release if appropriate)
- Answer core identity/MFA questions: what MFA and SSO are, how push approval works, enrolling a user, replacing a device, and reviewing auth logs

## Week 6 — Performance Metrics and Network Security Certification

### Training

Help desk performance metrics:

| Metric | Target | Description |
|---|---|---|
| SLA | 95% or higher | Average of tickets responded to and resolved within target. |
| Customer satisfaction score | 90% or higher | Average rating from post-resolution surveys (positive/neutral/negative). |
| Billable efficiency | 85% or higher | Share of time entries billable vs. non-billable; detailed notes support accurate billing. Lunch, PTO, sick time, and staff meetings are excluded from this measure. |

- A KPI dashboard is provided showing most of these metrics; all are reviewed monthly in 1:1 meetings.
- Network security vendor's foundational certification track: complete all modules and exams
- Finalize a documented plan and timeline for the technician's first certification

### End of week expectations

- Explain what each performance metric measures (exact targets not required)
- Pass the foundational certification track
- Have a documented certification plan with a target completion timeframe

## Recurring Meetings

**Ride-along reviews** — weekly, one live and one random closed-ticket audit, covering ticket handling, customer communication, documentation quality, and escalation adherence. Supervisor feedback given each time.

**Monthly 1:1s** — performance review, open questions/concerns, and certification progress tracking with the supervisor.

**Weekly team meeting** — on-call scheduling, process changes, new client onboarding, and an open floor for questions and suggestions.

## First-Year Plan

- Around month 3–4 (based on readiness), the technician joins the phone queue, with call-handling training beforehand.
- Around month 5–6 (based on readiness), the technician joins the chat queue and on-call rotation, with training beforehand. Timelines can move up based on demonstrated experience.
- **90 days:** informal performance check-in with leadership.
- **1 year:** formal performance review with self-evaluation and supervisor evaluation.

## Training Sign-Off Sheet (structure)

Each of the following tracks is logged with a date and sign-off as modules are completed:

- Ticketing platform vendor certification track (all modules)
- RMM/monitoring platform training
- Secure email gateway introduction
- Identity/MFA training (including authentication-log review demonstration)
- EDR platform overview + scan/results demonstration
- MDR service overview + incident-report-reading demonstration
- Network security vendor foundational certification (all levels)
- Cloud-fundamentals certifications (both tracks)
- Shadowing log (teammates across support tiers)
- Weekly completion tracker (Weeks 1–6)
- 90-day review date and anticipated certification/month fields
