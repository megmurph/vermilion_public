# vermilion_public

Public, reusable [Claude Agent Skills](https://docs.claude.com) from Vermilion — made to share with portfolio founders.

## Skills

| Skill | What it does |
| --- | --- |
| [`launch-playbook`](skills/launch-playbook/) | Vermilion's tiered product-launch and funding-announcement playbook — pick a launch tier, get an owner-and-timing plan, and fill in the messaging / LinkedIn / Product Hunt templates. |

## For founders — two ways to use this

**Read it.** Open [`skills/launch-playbook/SKILL.md`](skills/launch-playbook/SKILL.md) and the [`references/`](skills/launch-playbook/references) folder right here on GitHub. The tier checklists, one-pager templates, and LinkedIn / Product Hunt guides are all plain Markdown — no setup required.

**Run it in Claude.** `launch-playbook` is a standard Claude Agent Skill. Once installed, Claude pulls it up automatically whenever you're planning a launch or announcement — "we're shipping next week," "help us announce our raise," "PH launch Tuesday" — and produces the full plan for you.

To install it:

1. Download this repo: **Code → Download ZIP** (or `git clone`).
2. Zip the `skills/launch-playbook/` folder into a file named `launch-playbook.skill`.
3. In Claude (Cowork / desktop), use **Save skill** / add it to your skills directory.

## Repo layout

Each skill is a self-contained folder under `skills/` — a `SKILL.md` plus a `references/` folder of templates and guides. The press target list is intentionally kept private and is not bundled here.
