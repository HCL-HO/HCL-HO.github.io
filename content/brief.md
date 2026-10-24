# Landing page brief — HCL-HO (private source material, do NOT publish verbatim)

## Goal
One page that makes a hiring manager want to talk to him. It replaces a free HTML5
template ("Profile", freehtml5.co) that says nothing about what he can do.

## The one thing that must land in 5 seconds
He does not just write code: **he ships complete AI products** — six of them, each
with real users, real databases, real deployment, and a test suite that measures it.

## The six projects (facts only — no client names, no private data)
| Project | One line | Verifiable number |
|---|---|---|
| jobsearch | A job pipeline: scheduled board search, LLM scoring, generated application packs | 1,842 automated checks |
| jobsearch-mobile | The same product as an Android app around the web app, with a native bridge | 12 shipped builds |
| investintelligent | An investment-intelligence portal: many news sources in, LLM analysis out, alerts and briefings | 990 automated checks |
| examcoach | Exam preparation: papers and cheat sheets generated from a syllabus | 75+ automated checks |
| aiacademy | Turns any topic into illustrated study notes with diagrams | 225 automated checks |
| MindCare (counselor) | A long-form chat companion with memory, summaries and safe fallbacks | 319 automated checks |

**Aggregate line that is true:** six shipped apps and **3,450+ automated checks**.

## Content sources
- `content/resume.txt` — his real CV text (name, contact, roles, dates, skills).
  Use it for the experience section, the skills, and the contact block.
- Nothing else. Do not invent employers, dates, titles or numbers.

## The page
1. **Hero** — name, one-line pitch, two actions: *Email me* (mailto) and *See what I shipped* (in-page anchor). No photo needed; if a photo is used it must be a real one he supplies — do not invent.
2. **Proof** — ⚠ **SUPERSEDED BY CR-0423 (2026-10-25).** His instruction: *"do not tell all the ai project separately, show it in another section, just say vaguely of what areas I have built projects on. and the workflow I built the project"*. The six named cards are **gone**; the page now carries one band, **Built With AI**, listing the **areas** he has built in (no project names, no per-project numbers) and his **build workflow**. Do not restore the per-project cards. The six names and their check counts stay in this brief as source material, not as page copy.
3. **Experience** — from the CV, newest first, with dates.
4. **Skills** — grouped, from the CV, one line each.
5. **Contact** — email and the same links, plain text, no form.

## Theme — CHOSEN (do not re-theme)
`theme.json` in this folder: "Signal", derived from the linear.app reference (catalogue:
https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/linear.app). Tokens are OURS.
