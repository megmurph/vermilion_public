# Founder launch prompt

Founder-facing: a self-contained prompt we hand portfolio founders so they can generate their own launch plan, dated checklist, messaging one-pager, and drafted comms in their own Claude — outside Vermilion's environment. Hand it over when a founder wants to self-serve rather than have the GP run the playbook for them.

**Source:** none — there's no Notion page for this; this file is the canonical copy. (Every other file in this folder opens with a Notion "Live source"; this one is intentionally self-contained.)

---

# Launch Prompt — for Vermilion founders

Most launches don't die because the product is weak. They die quiet — because nobody planned the noise, and "we'll post something Tuesday" isn't a plan. I'd rather you spend your energy shipping than staring at a blank page wondering what a launch is supposed to look like.

So here's a prompt. Paste it into Claude, fill in the brackets with your launch details, and it'll hand you back the whole kit: the right launch tier, a dated checklist with an owner on every task, your messaging one-pager, and **drafted copy** — your LinkedIn post, reshare copy your network can lift, the pre-launch email to investors, and the blog. Edit it to sound like you. It's a starting point, not gospel.

One rule it won't break: it will never invent a metric or a customer name. Anything it doesn't know, it leaves in brackets for you to fill. Don't ship the brackets.

When press enters the picture — usually only when you're announcing a raise — ping me. I keep that list off this prompt on purpose.

## How to use it

1. Copy everything in the box below.
2. Fill in every `[bracket]`. The more specific you are, the less generic the output.
3. Paste it into Claude. Read what comes back with a red pen — it's a draft, you're the voice.

---

```
You are helping me run a launch. I'm the founder. Be concrete and opinionated, not generic.

HERE'S MY LAUNCH
- What we're shipping (1–2 plain sentences): [...]
- Launch day (date): [...]
- What it does / the problem it kills: [...]
- Who it's for (name the segment, not "everyone"): [...]
- Why now: [...]
- Proof I can cite (metrics, customers, design partners) — or write "TBD" and I'll fill it: [...]
- The ask (hiring? beta users? intros? to whom?): [...]
- Who to tag (investors, partners, champions): [...]
- Company name, my name, relevant links: [...]

DO THIS, IN ORDER
1) PICK THE TIER and tell me why. Tiers are cumulative — a higher tier includes everything below it.
   - Tier 3 (Baseline): a routine ship or dot-release. Goal is a clean launch and that nobody close to me is surprised. Start ~1 week out.
   - Tier 2 (Amplified): a release I want the market to notice. Tier 3 PLUS coordinated messaging, network + investor amplification, and customer proof. Start ~1–2 weeks out.
   - Tier 1 (Full): a flagship moment — GA/1.0, a category-defining launch. Tier 3 + Tier 2 PLUS long-form content, a press play, influencers, Product Hunt, and a launch-day runbook. Start ~3–4 weeks out. (Reality: press is hard for pure product news unless it's tied to funding — run it if it fits, don't let it block the launch.)
   - If I'm announcing a fundraise, use the FUNDING path instead: it's its own ~3–4 week flow. The money is validation, not the story — the story is the problem, the proof it's working, and why now.
2) BUILD THE PLAN as a checklist. Convert every timing to a real calendar date working backward from my launch day. Give every task a single owner (Founder, Marketing, Eng, Product, Data, Ops). Group by tier. If my runway is tighter than the tier wants, say so and flag exactly which tasks have to start immediately.
3) FILL THE MESSAGING ONE-PAGER (the single source of truth every post pulls from):
   - What this is (plain, no hype) · Why it matters (problem before / what changes now / why now) · Who it's for · 3–4 key messages, each with proof · positioning in one line · proof points · tone & guardrails.
4) DRAFT THE COMMS — actually write them, don't describe them. Fill with my facts; use [brackets] for anything you don't know:
   - Founder LinkedIn post — founder-led from my personal account (the whole thing falls apart if it's posted from the company account). Structure: hook (first 2 lines, scroll-stopping) → why (what's broken, what I'm fixing) → what (the news, concise) → gratitude (tag the team, early users, investors) → ask (direct) → [founder photo]. No link in the post body — note that the link goes in the first comment. Post 9–11am local.
   - Ready-to-lift reshare copy — short LinkedIn + X versions my network can paste verbatim, led by a one-line note that the most valuable thing they can do is say one true sentence in their own words.
   - Pre-launch "I need a favor" email — to investors, partners, and friendlies, sent ~3 days out: what's launching and when, the favor (quote-post, don't just like), the 3 messages we're leading with, and the logistics/links.
   - Investor ready-to-post drafts — a LinkedIn + an X post my investors can lift, sent the day before so they're loaded.
   - Blog post — tell the story: the problem, why now, why my team, what's next. Not for traffic — for a discoverable, owned asset.
   - Newsletter inclusion + company X/LinkedIn posts.

GUARDRAILS
- Never invent a metric, benchmark, or customer name. If I didn't give it to you, leave a clearly-marked [placeholder].
- I'm the influencer here — keep the founder voice operator-to-operator: specific, plain-spoken, no press-release tone.
- If something needs a human decision before it can ship (a real number, a customer agreeing to go on record), call it out as an open item rather than papering over it.

Ask me at most one clarifying question if my launch details are too thin to pick a tier. Otherwise, go.
```

---

*Questions, or hitting the press/funding case? That's a "ping me" moment, not a prompt.*
