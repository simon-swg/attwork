# TASK_001 — The site is launch-ready on its own domain

**Status:** In progress
**Opened:** 2026-08-18

## Output

`attwork.com` serving the current site, with correct brand assets and a contact form that
delivers a real enquiry to a real inbox.

## Constraints

- Single-file `index.html`, no framework, no build step (canon, What must not be touched).
- II Vorkurs, lime page, green mark — unchanged (canon, What must not be touched).
- Copy changes are Simon's sign-off, not an AI's (canon, Principle 6).
- No registration numbers, ownership splits or financial figures enter this repo, whatever
  the fix requires (canon, What must not be touched).

## Done when

- [ ] `attwork-wordmark-tag.svg` reads "traders", not "trades"
- [ ] The ant artwork is vector and fills the brand green exactly, in every asset that uses it
- [ ] `green-monogram.svg` sits optically centred in its frame
- [ ] Both forms submit end-to-end to a live inbox and a test enquiry has been received
- [ ] `privacy-policy.html` carries a real date, one confirmed contact address, and one registered company address
- [ ] `attwork.com` resolves to the Vercel deployment

A task without a checkbox list has no exit condition, and a task with no exit condition
never closes. Tick what is actually done, never aspirationally. When complete,
`git mv` this file to `tasks/done/` — never `rm`.
