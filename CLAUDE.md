# CLAUDE.md — CloudOps leadership context

Read this first, every session. `AGENTS.md` points here for other AI tools.

## What this is

The context needed to lead Huma's CloudOps team (also called SRE, Infrastructure, DevOps or Platform).
Written for **Kiarash Azarnia**, who takes over team leadership from **Mohammad (Mo) Amirkhani** in
December 2026. It exists so that Kia, or an AI tool connected to this repo, can answer four questions
when Mo cannot be asked: **what is the state of X, who owns it, what is due, and why is it this way.**

It is not:

- system documentation — that lives in the infra knowledge hub repos and the internal docs site
- a task tracker — that is Jira (`COPS` internal, `COSM` on-call)
- a copy of Mo's private notes — only what a successor needs is extracted, one topic at a time

Link to those sources. Do not copy them here.

## Read order

1. This file.
2. `state.md` — every line of work, its owner and how far the transfer has got.
3. The `lines/` file for the topic in question.
4. `calendar.md`, `access.md`, `decisions.md` when the question is about a date, an account or a "why".

## Map

| Path | Holds |
|---|---|
| `state.md` | The lines of work, owner per line, transfer status, open questions |
| `lines/` | One page per line of work, written from `lines/_template.md` |
| `calendar.md` | Dated and recurring obligations: renewals, expiries, reviews, audits |
| `access.md` | Which account or person owns each system. Never the secret itself |
| `decisions.md` | Decisions that still bind the team, each with its reason |
| `inbox.md` | Raw notes from meetings, not yet filed |

## Rules for writing here

1. **One page per line of work.** If a page grows past two screens, it is copying a source it should link to.
2. **Every fact carries a date and a source**: `(as of 2026-11-20, Mo)` or a link. This repo ages; an undated fact cannot be trusted later.
3. **Link, don't copy.** Jira key, repo path, doc URL, dashboard. One line of substance beside each link, so the link is not an errand.
4. **No secrets.** No passwords, tokens, keys or recovery codes. Write where the secret lives and who can reach it.
5. **No personal data about people**: pay, performance, health, reasons for leave. That is handed over in person and lives in the HR system.
6. **Unknown is written as unknown.** Mark a guess with `?`. Never fill an owner by inference.
7. **English only.**
8. **Raw notes go to `inbox.md`.** File each into a line within a week, or delete it.

## Rules for an AI answering from this repo

- Answer from the files and name the file and the as-of date. If the date is more than about three months old, say it may be stale and point to the live source.
- If the answer is not here, say "not in this repo". Do not infer an owner, a state or a deadline.
- When Kia states something durable (a new owner, a decision, a date), propose the edit to the right file in the same reply.

## People (as of 2026-11-20, Mo)

- **Kiarash Azarnia (Kia)** — team lead from December 2026.
- **Hamid Mansouri** — the team's manager after the handover.
- **Milano** — CTO.
- **Mo Amirkhani** — previous lead; wrote the first version of this repo.

The team roster and who is on what belongs in `lines/team-management.md`.
