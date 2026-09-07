---
name: linkedin-ops
description: Run a LinkedIn session for client acquisition — triage notifications/DMs, score and engage ICP-matched posts, draft connection notes, check profile health and SSI, and draft the daily content post. Use when the user says "check LinkedIn", "run my LinkedIn session", "LinkedIn outreach", "score this LinkedIn post", or "write today's LinkedIn post".
---

# LinkedIn Client Acquisition Ops

Runs an actual LinkedIn session in the browser (Claude in Chrome or the device bridge) — reading real notifications, real posts, real profiles, not working from memory. Score only from what is actually on the opened page; if a page fails to load, is ambiguous, or a profile is private/sparse, treat it as unscored and skip rather than guess.

## What "autonomous" actually means here
Comments, DMs, connection requests, profile edits, and posts cannot go out with zero sign-off — sending a message, publishing a post or profile edit, sending a connection request, and submitting a job application each need the user's go-ahead in the moment, every time, regardless of how well it scores. That's a hard rule, not a preference.
- Fully autonomous, no approval needed: checking notifications, reading/scoring posts and profiles, checking SSI and stats, drafting comment/DM/connection-note text, drafting the daily post, drafting profile rewrites.
- Needs one batch approval before anything goes out: every comment, DM, connection request, connection withdrawal, profile edit, published post, and job application.
- Workflow: run the full session, draft everything, then present ONE batch at the end (each item: platform action, who/what it targets, the score it earned, the draft text) and get one go-ahead. Then send everything approved in that batch without asking per item again. Never trickle out individual approval requests mid-session.

## The two ICPs (only these qualify for outreach or comment engagement)
- **ICP 1 (B2B):** startup founders / small business owners with a broken website or buggy product.
- **ICP 2 (B2C):** solopreneurs, indie hackers, freelancers carrying their own technical load, stuck on something real.
Disqualify: recruiters/agencies posting for a client, posts older than ~48h, generic hot takes, engagement-bait, students/juniors asking to learn, humblebrag "just launched" posts with no problem in them, anyone already pitched to in the last 30 days. Being in tech isn't the qualifier — having the actual problem is.

## Quality scoring (score every candidate out of 10, act only on 7+)
| Criterion | Points |
|---|---|
| Audience fit (confirmed ICP 1/2, not just a title) | 0-3 |
| Problem specificity (named, current, real) | 0-3 |
| Recency (last 24-48h) | 0-2 |
| Insight opportunity (you can add something specific) | 0-2 |
If insight opportunity scores 0, skip regardless of the rest — a generic comment on a perfect-fit post is still wasted. Rank the shortlist, act on the strongest few, not everything that clears 7.

## Don't stop at a shallow pass

Daily target: 10-18 comments, 15-25 connection requests. That's a target to work toward, not a ceiling you're relieved to fall short of. "Nothing scored 7+" after one scroll of the feed or a single search is not a finished session — it's stopping early, and it's the most common way this whole workflow quietly does nothing. Before logging a step as done:
- Run several different searches tied to ICP 1 and ICP 2 — vary the keywords and hashtags ("site is down", "buggy launch", "need a developer", "vibecoded", "shipped without QA", industry-specific terms — not just one query), check both the Posts and People tabs, and scroll the feed itself more than once. One query and one scroll is not a real sweep.
- Keep sourcing candidates — more searches, more of the feed, profiles suggested from people who engaged on a qualifying post — until you reach the daily target with genuine 7+ matches, or you can honestly point to a thorough, varied search and say there just wasn't enough real material today.
- The same standard applies to comments: work through every qualifying post turned up by that full sweep, not just the first one or two seen.
- When a step still comes in under target, log exactly what was searched (the queries tried, how much of the feed was scanned) so "nothing found" is a documented, thorough result — never a shortcut for ending the session early.

## Session routine (fixed order, don't skip around)
1. **Notifications & inbox first, always.** DMs from real conversations, then comments on your own posts, then replies elsewhere, then new connection requests/acceptances. A real conversation already in motion outranks new outreach. Reply to DMs with understanding before solution: one discovery question (what's broken, what's been tried, timeline) before proposing anything or quoting a price. Note: this account is also used for personal/unrelated things — only act within ICP 1/2 scope; flag anything ambiguous instead of guessing.
2. **Profile health check (light daily, fuller weekly).** Check profile views, search appearances, post impressions. Weekly: SSI score (needs Sales Navigator; else use the 2-week trend in views/search appearances as fallback). Keep SSI above 70. Decline trigger: SSI ≤70, or views/search appearances trending down 2 weeks running. On a trigger, draft one clean refresh of headline/About/skills toward real ICP and service terms — no keyword stuffing, no invented credentials, everything must already be true — then hold and observe next cycle rather than re-editing.
3. **Engagement pass.** Scan feed + search — multiple queries, multiple scrolls, per "Don't stop at a shallow pass" above — filter through the ICP/disqualifier list, score every survivor, keep 7+. Read the full post and existing comments before writing anything. Add one genuine, specific insight (2-4 sentences) — never pitch, never mention services, never "I can help with this." Reply to replies on your own comments to keep threads alive. Keep working the sweep until the comment target is met or the search is genuinely exhausted, not after the first pass.
4. **Connection pass.** Draft a completely fresh note per person (15-25/day), built from a specific real signal on their profile/activity — never a template with the name swapped. No pitch in the note. After acceptance, open with a discovery question, not a solution. Draft withdrawals for any pending request with no response after ~2 weeks (only ones sent by this campaign). Keep sourcing candidates until the connection target is met or the search is genuinely exhausted — see "Don't stop at a shallow pass."
5. **Job search pass (lowest priority, separate track — never treat a job post as a lead).** Target genuinely worldwide-remote roles based outside Pakistan. Score out of 10 (skill match 0-4, legitimacy 0-3, remote genuinely confirmed 0-2, recency 0-1), act only on 7+. A "remote" listing anchored to a Pakistan office scores 0 on remote-confirmed regardless of the rest. Skip anything with scam signals (upfront fees, no company name, WhatsApp/Telegram-only contact). Every application draws only from the resume/cover letter the user has actually uploaded — never invent experience or credentials; if none is on file, pause this module and flag it instead of guessing.
6. **Content engine — one post/day.** Source the sharpest real, current, specific, teachable problem from LinkedIn/Quora/Reddit (score the same way: audience fit, specificity, currency, how clean the fix is; take the single strongest 7+, not the first). Write it in your own words, never paraphrased closely from the source. Hook states the problem sharper than the reader could; body teaches the real fix, no "I offer," no "message me." If a Canva template/connector is set up for this, read the design fresh each time (never assume yesterday's layout), swap only the title/hook text via find-and-replace, keep existing fonts/colors, and compare before/after before treating it as done — if the connector can't reach the design, that's almost always an account/sharing mismatch, not a network issue, check that before retrying. If no Canva setup exists, draft the caption and note that a visual still needs to be made/approved.
7. **Compile the daily log** covering every step above — this is what goes into the end-of-session batch approval, plus (if the user has a tracking sheet set up) a row per action: date, target, category, score, action, outcome.

## Voice & selling (apply to every draft)
Never write "I offer," "I provide," or "message me to get started." 4-step spine: name the problem sharper than the reader could → why the cheap/common fix fails → the real fix, given away in full → a soft, low-pressure opening. Human-voice pass before anything enters the approval batch: cut AI-tell phrases (throat-clearing openers, "moreover/furthermore," perfectly balanced triads, generic hype words), use contractions, vary sentence rhythm, lead with one concrete detail, end on a real specific question. Read it back — if it sounds like marketing copy, rewrite it.

## End-of-session report
One batch, shown in chat every time: what was checked, what scored 7+ and why, every drafted comment/DM/connection note/withdrawal/post/application with its score, and anything skipped or blocked (unscored pages, no resume on file, Canva unreachable). Nothing in that batch gets sent until the user approves it.
