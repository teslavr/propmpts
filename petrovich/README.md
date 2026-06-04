# Петрович (Petrovich) — a Claude skill

A blunt, foul-mouthed Russian "everyman" alter-ego. You feed him an idea, a product, or a pitch — he gives you the unfiltered gut reaction of a regular, down-to-earth guy: zero corporate politeness, deep skepticism toward hype, and a cynic's nose for marketing bullshit, scammy business models, and empty products with nothing behind them.

He's not dumb — under the rough talk he's well-read and sharp (you can talk astrophysics with him). He just has no patience for pretense. He judges a **project** by whether the economics actually add up, and a **product** by whether a normal person would actually use it.

> ⚠️ **18+ / NSFW.** Contains heavy explicit Russian profanity (мат) by design — it's the character's voice, not gratuitous. Fictional persona, not real advice. He pokes at ideas and pretense, never at people for who they are.

## Two ways to use it

**1. As a Claude skill (recommended)**
Download `petrovich.skill` and install it:
- **Claude desktop/web** — add the `.skill` file in your skills/settings.
- **Claude Code** — unzip into `~/.claude/skills/petrovich/` (or just drop the folder there).

Then summon him: `/petrovich`, or simply write in chat «а что Петрович скажет?» / «спроси Петровича».

**2. As a plain system prompt**
Copy the contents of `SKILL.md` into a Claude Project, an OpenAI Custom GPT ("Configure"), or a Gemini Gem ("Instructions"). He works as a persona there too. The `references/` files add extra voice depth but aren't required.

## Files
- `SKILL.md` — the character itself (this is the whole persona).
- `references/golos-i-primery.md` — voice, live examples, vocabulary.
- `references/pribautki.md` — his stash of crude one-liner sayings, with usage notes.
- `petrovich.skill` — ready-to-install bundle (built from the files above).

Author: Sergei Lavrinenko · He speaks Russian.
