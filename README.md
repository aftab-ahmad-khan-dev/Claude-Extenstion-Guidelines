# Claude Extension Guidelines

Personal Claude playbooks for running client acquisition and content across Fiverr, LinkedIn, Meta, and Email — split into small, functionality-specific files so a task only loads what it actually needs instead of one long daily file.

![Repo structure and content flow](assets/repo-structure.svg)

## How it's organized

- **Shared/** — the cross-platform framework every other folder builds on: the indirect-selling formula, current/near-future content trends, the repurposing + proof + metrics system, and personal contact info.
- **Fiverr/**, **LinkedIn/**, **Meta/**, **Email/** — one playbook per channel, each split into numbered files (`01-`, `02-`, ...). The number is the order to follow them; `01-overview.md` in each folder explains what the rest of the files cover.

Every file starts by naming which Master Control Rules and Shared files govern it, so it can be read on its own without pulling in the whole repo.

## Running these as real skills

Each platform folder now also has a `SKILL.md` file (`Fiverr/SKILL.md`, `LinkedIn/SKILL.md`, `Meta/SKILL.md`, `Email/SKILL.md`) — a self-contained, automation-ready version of that folder's playbook, meant to be loaded as an actual Claude skill (Claude Code, or a claude.ai/Cowork skill) instead of read as reference text. Drop a folder into your Claude skills directory, or upload/paste a `SKILL.md` into a skill-creator flow, then say things like "check my Fiverr" or "run my LinkedIn session" to have it actually run: check the platform, draft replies or content, and report back.

One change from the autonomy language elsewhere in this repo: sending a message, publishing a post, sending a connection request, or submitting a job application always needs one human approval in the moment, no matter what a file says. Each `SKILL.md` reads, scores, and drafts everything fully on its own, then presents one batch at the end of the session for a single go-ahead before anything actually sends — not the zero-approval model described in the numbered files below.

## Handling personal info

`Shared/08-contact-info.md` holds the real email and phone number. Treat it as reference data, not content:
- Only open or use it when a task genuinely needs it (an email signature, a proposal footer, a lead who asked for direct contact)
- Never paste it into a public post, comment, caption, or connection note
- Never surface it proactively; if unsure whether a task calls for it, ask first
