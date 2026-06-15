---
name: launch-playbook
description: >-
  Vermilion's tiered product-launch and funding-announcement playbook for
  portfolio companies. Use this whenever a portfolio company (or the GP acting on
  their behalf) is planning, preparing, coordinating, amplifying, or
  running a product launch, feature release, major update, version/GA milestone,
  or funding/fundraise announcement. This includes any request to build a launch
  plan or checklist, pick a launch tier, set a launch timeline, draft launch or
  announcement messaging and one-pagers, coordinate social/LinkedIn/blog/press/
  Product Hunt amplification, line up investor and network resharing, or run a
  launch-day runbook. Trigger even when the user never says "checklist," "tier,"
  or "playbook" — phrasings like "we're shipping X next week," "help us announce
  our raise," "how do we make a splash," "we're going live Tuesday," "PH launch,"
  "we just closed our seed," or "help us coordinate the release" should all pull
  this skill in. When in doubt about whether a launch or announcement is
  involved, use this skill.
---

# Launch Playbook

This is Vermilion's playbook for helping a portfolio company run a launch — a product/feature release or a funding announcement. It encodes a tiered checklist (Tier 3 → Tier 2 → Tier 1) plus a separate funding-announcement flow, with owners and timing for every task, and pointers to the supporting templates founders should actually fill in.

Your job when this skill triggers: figure out what's being launched, pick the right tier (or the funding path), and produce a concrete, owner-and-timing-stamped plan from the checklists below. Pull in the bundled resource files when the founder needs the underlying template or guide — don't make them from scratch.

## Pick the tier first — it sets the timeline

Decide the tier early, because it determines how far ahead you have to start. The tiers are **cumulative**:

- **Tier 3 (Baseline)** — every launch runs this, no matter how small. Ship cleanly, update the surfaces, tell your people. Starts ~1 week out.
- **Tier 2 (Amplified)** — **everything in Tier 3, plus** coordinated messaging, network/friendly resharing, investor amplification, and customer proof. Starts ~1–2 weeks out.
- **Tier 1 (Full)** — **everything in Tier 3 + Tier 2, plus** a longer-form content push, press strategy and materials, influencers, Product Hunt, spokesperson prep, and a formal launch-day runbook. Starts ~3–4 weeks out (press and influencers have the longest lead).

How to choose:

- Routine feature ship, dot-release, or quiet update → **Tier 3**.
- A release you want the market to notice — a real new capability, a milestone, something worth rallying the network and customers around → **Tier 2**.
- A flagship moment — GA/1.0, a category-defining launch, or anything you want press and a coordinated multi-channel push behind → **Tier 1**.
- Announcing a **raise** → use the **[Funding announcement flow](#funding-announcement-flow)** below. It's its own path, not a tier (though a big product launch tied to a raise will borrow from Tier 1).

Once the tier is set, work the relevant section(s) below. For Tier 2 and Tier 1, **do the lower tiers too** — those items are not repeated here; they're inherited and pointed to.

Timing is expressed relative to launch day (e.g. "2–3 days before"). Owners use the sheet's roles: Founder, Marketing, Eng, Product, Data, Ops, PR.

---

## Tier 3 — Baseline

Every launch runs this. The goal is a clean ship and that the people closest to you (team, support/sales, existing customers) aren't surprised.

### Product

| Task | Owner | Timing |
| --- | --- | --- |
| Feature/product live and QA'd in production | Eng | Launch day |
| Analytics & event tracking in place to measure adoption | Eng / Data | Before launch |
| Rollback or kill-switch plan confirmed | Eng | Before launch |

### Site

| Task | Owner | Timing |
| --- | --- | --- |
| Homepage updated (hero / banner if relevant) | Marketing | Launch day |
| Feature or landing page live | Marketing | Launch day |
| Pricing page updated if pricing is affected | Marketing | Launch day |

For homepage/landing copy, see `references/homepage-messaging.md` (Fletch's 4-step framework).

### Docs

| Task | Owner | Timing |
| --- | --- | --- |
| New feature updated on docs | Product / Eng | Before launch |
| Changelog / release notes entry published | Product | Launch day |
| API reference updated if relevant | Eng | Before launch |

### Newsletter & Social

| Task | Owner | Timing |
| --- | --- | --- |
| Newsletter inclusion drafted (next send or dedicated) | Marketing | 1 wk before |
| Social posts queued — company X & LinkedIn | Marketing | 1–2 days before |
| Prep mini screencast and/or demo | Product / Eng | 1–2 days before |
| Founder posts from personal account** | Founder | Launch day |

** The founder's personal post is the one everyone on the team amplifies and comments on. For how to structure it, see `references/linkedin-launch-playbook.md`.

### Internal

| Task | Owner | Timing |
| --- | --- | --- |
| Team heads-up so they can reshare | Founder / Ops | Launch day AM |
| Support & sales briefed on what changed | Ops | 1–2 days before |

### External

| Task | Owner | Timing |
| --- | --- | --- |
| Customer and prospect touch point (1:1 follow ups) | Founder / Marketing | Around launch |

---

## Tier 2 — Amplified

**Do everything in [Tier 3](#tier-3--baseline) first.** Tier 2 adds coordinated messaging, network amplification, investor pickup, and customer proof on top of the clean ship. The items below are net-new beyond Tier 3.

### Messaging

| Task | Owner | Timing |
| --- | --- | --- |
| Draft one-page "what are we launching and why it matters" | Marketing | ~1 wk before |

→ Use the **product one-pager template** in `references/one-pager-product.md` (this is the "Example" the sheet links). Fill it in; don't start from a blank page.

### Newsletter, Blog & Social (additions to Tier 3)

Tier 3's Newsletter & Social items still apply. Tier 2 adds:

| Task | Owner | Timing |
| --- | --- | --- |
| Founder thought-leadership posts related to the release | Founder | 1–2 wks before |
| Blog product update | Marketing / Product | 2–3 days before |

### Network & friendlies

| Task | Owner | Timing |
| --- | --- | --- |
| Line up friendlies to reshare day-of (advisors, community, founder friends) | Founder | 3–5 days before |
| Draft ready-to-post copy others can lift verbatim | Marketing | 3 days before |
| Tap the Vermilion network for amplification | Founder | 2–3 days before |

→ For ready-to-lift copy and the pre-launch "here's the favor" email to friendlies, see the sample in `references/linkedin-launch-playbook.md` (the "Example" the sheet links in this row).

### Investors

| Task | Owner | Timing |
| --- | --- | --- |
| Notify investors in advance with launch details | Founder | 2–3 days before |
| Send investors ready-to-post tweet/LinkedIn drafts | Founder | 1–2 days before |

### Co-marketing & proof

| Task | Owner | Timing |
| --- | --- | --- |
| Line up happy customer / design-partner champions to reshare or use as a use case | Marketing | 1 wk before |
| Collect 2–3 customer quotes or early-user reactions | Marketing | 1 wk before |

---

## Tier 1 — Full

**Do everything in [Tier 3](#tier-3--baseline) and [Tier 2](#tier-2--amplified) first.** Tier 1 is the flagship treatment: a longer-form content push, a press play, influencers, Product Hunt, spokesperson prep, and a formal launch-day runbook. Press and influencers have the longest lead times, so start ~3–4 weeks out. The items below are net-new beyond Tier 2.

> Reality check on press: it's genuinely hard to get coverage for product news unless it's tied to funding. Run the press track if it fits, but don't let it block the launch.

### Amplified content

| Task | Owner | Timing |
| --- | --- | --- |
| Founder writes a thread / longer-form post (not a one-liner) | Founder | 1–2 days before |
| Coordinate post timing across all accounts | Marketing | Launch day |

### Press strategy *(hard for pure product news — mainly relevant if tied to funding)*

| Task | Owner | Timing |
| --- | --- | --- |
| Decide approach: exclusive vs. embargo | Founder / PR | 3 wks before |
| Build target reporter / outlet list | PR | 2–3 wks before |
| Pitch reporters | PR | 2–3 wks before |

→ Vermilion keeps its press target list (reporters, outlets, agencies) private — ask the GP for it rather than guessing. It's intentionally not bundled in this public skill.

### Press materials

| Task | Owner | Timing |
| --- | --- | --- |
| Announcement / press release drafted & approved | PR / Marketing | 2 wks before |
| Fact sheet, founder quotes, screenshots & assets ready | Marketing | 1–2 wks before |

> A wire release (EIN Presswire, PRWeb) is purely for SEO / internet presence — it will not get you press. Don't confuse it with earned coverage.

### Influencers / creators

| Task | Owner | Timing |
| --- | --- | --- |
| Identify target influencers & line up timed campaigns (paid) | Marketing | 4 wks before |

> Tool worth trying for creator campaigns: Passionfroot.

### Product Hunt *(still drives traffic even outside the top 10)*

| Task | Owner | Timing |
| --- | --- | --- |
| Prep materials for Product Hunt | Marketing | 1–2 wks before |

→ Full field-by-field PH checklist (coming-soon + launch assets) is in `references/product-hunt-checklist.md`.

### Spokesperson prep

| Task | Owner | Timing |
| --- | --- | --- |
| Prep spokesperson: key messages, hard questions, what not to say | Founder / PR | 1 wk before |

> Only relevant if press bites — and they normally just want an email Q&A and your draft launch post.

### Launch day

| Task | Owner | Timing |
| --- | --- | --- |
| Launch-day runbook with timeline & single owner | Founder / Ops | 2–3 days before |
| Coordinated sequence: press live → company/founder posts → network amplifies | Marketing | Launch day |
| Monitoring & rapid-response: someone watching mentions, ready to engage/correct | Marketing | Launch day |

---

## Funding announcement flow

A raise is its own path, not a tier. The money is validation, not the story — the news is the problem you're solving, the proof it's working, and why now. This flow runs ~3–4 weeks (press/embargo lead time). A flagship product launch tied to a raise can also borrow the Tier 1 sections above.

### Messaging

| Task | Owner | Timing |
| --- | --- | --- |
| Draft one-page "who we are, why we matter, why now" internal doc | Marketing | ~2 wks before |

→ Use the **fundraise one-pager template** in `references/one-pager-fundraise.md` (this is the "Template" the sheet links). A reporter should be able to lift the "who we are" paragraph verbatim.

### Newsletter, Blog & Social

| Task | Owner | Timing |
| --- | --- | --- |
| Newsletter inclusion drafted (next send or dedicated) | Marketing | 1 wk before |
| Social posts queued — company X & LinkedIn | Marketing | 1–2 days before |
| Blog fundraise announcement | Marketing / Product | 2–3 days before |
| Prep mini screencast and/or demo | Product / Eng | 1–2 days before |

→ The funding announcement is **founder-led on LinkedIn**. For the post structure (hook → why → what → gratitude → ask → photo), posting mechanics, blog guidance, and example templates, see `references/linkedin-launch-playbook.md`.

### Network & friendlies

| Task | Owner | Timing |
| --- | --- | --- |
| Line up friendlies to reshare day-of (advisors, community, founder friends) | Founder | 3–5 days before |
| Draft ready-to-post copy others can lift verbatim | Marketing | 3 days before |
| Tap the Vermilion network for amplification | Founder | 2–3 days before |
| Line up happy customer / design-partner champions to reshare or use as a use case | Marketing | 1 wk before |
| Collect 2–3 customer quotes or early-user reactions | Marketing | 1 wk before |

### Press

| Task | Owner | Timing |
| --- | --- | --- |
| Decide approach — one exclusive is usually the best bet (founder-led pitch & outreach) | Founder / PR | 3 wks before |
| Build target reporter / outlet list | PR | 2–3 wks before |
| Pitch reporters | PR | 2–3 wks before |
| Set & confirm embargo with each outlet (if applicable) | PR | 1 wk before |

→ Vermilion's press target list is private — ask the GP for it (not bundled in this public skill).

### Press materials

| Task | Owner | Timing |
| --- | --- | --- |
| Announcement / press release drafted & approved | PR / Marketing | 2 wks before |
| Fact sheet, founder quotes, screenshots & assets ready | Marketing | 1–2 wks before |

> Wire services (EIN Presswire, PRWeb) are for SEO / internet presence only — not earned press.

### Influencers / creators

| Task | Owner | Timing |
| --- | --- | --- |
| Identify target influencers & line up timed campaigns | Marketing | 4 wks before |

### Spokesperson prep

| Task | Owner | Timing |
| --- | --- | --- |
| Prep spokesperson: key messages, hard questions, what not to say | Founder / PR | 1 wk before |

### Site

| Task | Owner | Timing |
| --- | --- | --- |
| Add announcement banner to site | Marketing | Launch day |

### Launch day

| Task | Owner | Timing |
| --- | --- | --- |
| Founder posts from personal account** (team amplifies and comments) | Founder | Launch day |
| Launch-day runbook with timeline & single owner | Founder / Ops | 2–3 days before |
| Coordinated sequence: press live → company/founder posts → network amplifies | Marketing | Launch day |
| Monitoring & rapid-response: someone watching mentions, ready to engage/correct | Marketing | Launch day |

---

## Bundled resources — when to load each

Load these on demand. They resolve the placeholder cells in the source sheet ("Example", "Template", "LinkedIn resource doc", "PH prep") and hold the real templates and guides — use them instead of inventing your own.

| Resource file | Load it when… | Resolves sheet cell |
| --- | --- | --- |
| `references/one-pager-product.md` | Drafting the "what are we launching and why it matters" product one-pager (Tier 2 / Tier 1 Messaging). | "Example" (product Messaging) |
| `references/one-pager-fundraise.md` | Drafting the "who we are, why we matter, why now" fundraise one-pager (Funding Messaging). | "Template" (fundraise Messaging) |
| `references/linkedin-launch-playbook.md` | Writing the founder LinkedIn post, the company blog, ready-to-lift reshare copy, or the pre-launch email to investors/friendlies. | "LinkedIn launch resource doc" + "Example" (Network & friendlies) |
| `references/product-hunt-checklist.md` | Prepping a Product Hunt launch (Tier 1 Product Hunt). | "PH prep" / "Tiered Launch Plans" |
| `references/homepage-messaging.md` | Updating homepage / landing-page copy (any tier, Site). | Site / homepage |

Each reference file keeps its live Notion URL at the top followed by a content snapshot, so the skill still works if Notion isn't reachable. When Notion is reachable, prefer the live page in case it's been updated.
