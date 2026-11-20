# Team management

**Owner:** Kiarash Azarnia (Kia) · **Backup:** ? · **As of:** 2026-11-20

Source for everything on this page unless marked otherwise: Mo and Kia, handover session 1, 2026-11-20.

## What it is

Leading the CloudOps team: 1:1s, leave, goals and reviews, probation for the three joiners,
the on-call roster, hiring, and keeping the team's priorities aligned with the CTO's.

## State now

**Team**

| Person | Also called | Note |
|---|---|---|
| Kiarash Azarnia | Kia | Team lead from December 2026 |
| Ali Sharifi | | |
| Mostafa Bayat | Mosi | |
| Raziyeh Mohajer | Rosie | Joiner, onboarding |
| Kiarash Norouzi | Cairo | Joiner, onboarding |
| Mahdi Khalifehloo | Matteo | Joiner, onboarding |

Two Kiarashes: use surnames in writing.

**Rituals**

- **Daily:** seated, 30 minutes, 11:00–11:30 in Pascal, sharing a screen, from Mon 2026-11-23. Runs for the onboarding period (about 1–2 months), so the joiners hear each other's explanations. See `decisions.md`.
- **Team Pulse** (the Jira-driven daily check-in tool, COPS-363): keeps running, not mandatory. Kia relies on it for visibility and expects to return to it when the team goes async again.

**Joiner onboarding**

One real task at a time, about one per week. Mo pairs 1–2 days on each, then a catch-up with Kia, so Mo fades out and Kia fades in.

| Joiner | First task | Status |
|---|---|---|
| Kiarash Norouzi | Remove the Craft Cloud database public IP | in progress |
| Raziyeh Mohajer | Tailscale cleanup | proposed |
| Mahdi Khalifehloo | Terraform consolidation, plus monitor and escalation-policy configuration (continues Mostafa's import of the Huma org into Terraform) | proposed |

Held back as later tasks: observability alerting, the Cyber Essentials VM work, Wiz high-severity findings to Jira automation. See `inbox.md`.

**On-call**

Direction set by Kia: the joiners are onboarded into on-call and the on-duty seat rotates across everyone, so Ali is no longer the permanent on-call person. Until the end of 2026 the on-call tasks rotate among the joiners, with Ali assigning them.

## Recurring duties

| What | How often | Where the how-to lives |
|---|---|---|
| Daily | every working day, 11:00 | this page |
| Catch-up with the CTO (Milano) | fortnightly, recommended by Mo | not booked yet `?` |

Not written yet: 1:1 cadence, leave approval, goals and quarterly reviews, probation milestones, on-call roster mechanics, hiring.

## Contacts

- **Milano** — CTO. Mo's advice: keep a regular slot (fortnightly, or half an hour in his standing leadership meeting) to collect his asks and give updates, so the team's priorities do not drift from his.
- **Hamid Mansouri** — the team's manager after the handover.

## Open decisions and risks

- Which of Mo's Q4 2026 goals are dropped or handed over. Needs a three-way with Milano; Kia to ask for it. Without it Mo has no time to pair with the joiners.
- Second and later onboarding tasks per joiner are not chosen.

## Where the truth lives

- Jira `COPS` (team board) and `COSM` (on-call service desk).
- Not written yet: goals documents, performance process, roster.

## History that still matters

- The team ran an async daily on Team Pulse from October 2026. The classic daily came back for onboarding because three people joined at once and need information to flow; it is meant to be temporary.
