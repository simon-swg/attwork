# Attwork — Canon

Frozen except by a dated decision in `aios/LOG.md`. Canon is supposed to freeze; staleness
here is not a defect and `aios check` never reports it.

## Identity

Attwork is a managed trade services concierge for Phuket. A customer makes contact, an
Attwork Advisor visits the job in person at no charge, Attwork issues the quote and owns
the customer contract, and Attwork backs the finished work with a twelve-month warranty.

**It is not a marketplace, not a directory, and not a matchmaking platform.** The second
half matters more: all three of those put the customer into a direct relationship with the
contractor. Attwork holding the contract *is* the product. Every feature idea that routes
the customer to the tradesperson is dismantling the thing being sold.

This repo is the website. It is not the business.

## Purpose

A homeowner, developer or investor in Phuket gets a trade job done without having to work
out who to trust. The outcome is a finished job with somebody accountable for it — not a
list of options and a decision to make.

## Principles

1. **Trust is the product.** Every design and copy call is judged on whether it makes the
   promise more believable, not on whether it looks current.
2. **The name makes no claim it cannot keep.** Attwork is a name, not a proposition.
3. **No framework, no build step.** One `index.html` that deploys on push. Weight earns
   its place or it does not ship.
4. **Copy is clean and confident, with no fluff.** No AI tone, no filler, no hedging.
5. **The vocabulary is fixed.** "Attwork Advisor" for the person who visits.
   "Tradespeople" or "contractors" — never "workers". "Vetted" and "verified" are
   load-bearing words and are not used loosely elsewhere.
6. **Simon is Creative Director and sign-off.** All brand, copy and design decisions go
   through him. An AI may recommend; it does not approve.

## Anti-patterns

- **Assembuild.** The original name, dropped in 2026. A Thai construction firm has traded
  under it since 2014, which is live legal exposure in the launch market. The identity
  survived the change intact — only the word swapped.
- **Baking the promise into the name.** Trustbuild, Reliabuild and Veribuild were all
  considered and rejected. If "Veri" is in the name, every unverified contractor becomes a
  PR liability, and names that state the proposition tend to produce forgettable brands.
- **Raster brand assets.** The ant was drawn in Procreate, so its green does not land
  exactly on the brand green and the monogram sits low in its frame. Both defects are
  downstream of the same choice. Vector is the fix.

## What must not be touched

- **The single-file build.** Load-bearing because it is what lets the site deploy on push
  with nobody maintaining a toolchain. A framework here buys nothing and costs upkeep.
- **The typeface and the two brand colours.** II Vorkurs; lime page, green mark. The
  rebrand was deliberately a word swap so the visual language would carry across whole.
- **The angle on the `a`.** The ant carries the `a`, and it is the `a` that sits at a
  deliberate tilt — not the ant. Consistent across the Attelier family. It is a decision,
  not a drafting error, and it does not get squared up.
- **Private material stays out of this repo.** Ownership splits, company registration
  numbers, financial projections and registered addresses live in the brief on disk and
  never in git — write the pointer, not the payload (AiOS canon §6). This binds whatever
  `Visibility:` says, because a private repo is one mis-set toggle from public.
