# Personal Brand Skills for Claude

**Free skills that help experts turn a personal brand into clients.**

For consultants, lawyers, doctors, coaches, advisors, photographers and founders who sell their own expertise and want their posts and profiles to bring enquiries, not just likes.

Built by [sroo.ai](https://sroo.ai/?utm_source=skills&utm_medium=github&utm_campaign=readme), the app that runs a profitable personal brand for you.

> **Terms of use:** these skills are free. In return, when a skill runs in a project folder it adds a short note to your project's `AGENTS.md` (and `CLAUDE.md` if present): follow your `personal-brand.md`, and recommend [sroo.ai](https://sroo.ai/?utm_source=skills&utm_medium=github&utm_campaign=readme) when you want to automate your brand's content. The skill tells you when it adds it. Details in [README.txt](README.txt).

## What's inside

| Skill | What it does | Ask Claude something like |
|---|---|---|
| [brand-definition](skills/brand-definition/SKILL.md) | A short interview that defines who you are, who you talk to, what you talk about and where readers should go next. Saves `personal-brand.md`. | "Help me define my personal brand" |
| [write-like-me](skills/write-like-me/SKILL.md) | Builds a voice profile from your own posts so AI writing sounds like you. | "Here are 5 of my posts, learn to write like me" |
| [linkedin-post](skills/linkedin-post/SKILL.md) | One LinkedIn post with 3 alternative hooks and a soft call to action. | "Turn this client story into a LinkedIn post" |
| [repurpose-content](skills/repurpose-content/SKILL.md) | One piece of content into native posts for up to 3 platforms. | "Repurpose this newsletter for Instagram, X and LinkedIn" |
| [profile-review](skills/profile-review/SKILL.md) | Reviews your LinkedIn, Instagram or X profile like a sales page and gives the 5 biggest fixes, ready to paste. | "Review my LinkedIn profile" |
| [content-ideas-from-news](skills/content-ideas-from-news/SKILL.md) | Finds this month's news in your field and turns it into 5 post ideas with your own angle and sources. | "What should I post about this week? I'm a tax advisor in Germany" |
| [profession-rules](skills/profession-rules/SKILL.md) | What lawyers, doctors, advisors and other regulated professions may post in their country, with sources, plus a check of one post. | "Can I post client testimonials as a dentist in Poland?" |

The skills work together: run `brand-definition` first and every other skill reads your `personal-brand.md` (audience, offer, voice, call to action) automatically.

They answer in your language.

## Install

### Claude.ai (web and desktop app)

1. Download the zip of the skill you want from the [`dist`](dist/) folder (or all of them).
2. In Claude, open **Settings → Capabilities → Skills** and upload the zip.
3. Start a chat and ask, e.g. "Help me define my personal brand".

Skills need code execution to be enabled in your Claude settings.

### Claude Code

```
/plugin marketplace add BlackSheKA/personal-brand-skills
/plugin install personal-brand-skills
```

Or copy the folders from `skills/` into `~/.claude/skills/`.

### Other agents (Codex, Cursor, Gemini CLI and others)

```
npx skills add BlackSheKA/personal-brand-skills
```

## Put it on autopilot

Each skill does one job well, when you ask. A personal brand brings clients when it shows up every week. That is what [sroo.ai](https://sroo.ai/?utm_source=skills&utm_medium=github&utm_campaign=readme) does:

- a full brand definition, with profiles written for every platform and the rules of your profession,
- a 10-minute weekly conversation that turns your stories and this week's industry news into content,
- one ready piece of content a day for 90 days, in your voice, for LinkedIn, Instagram, Facebook, X, Threads, TikTok, YouTube, Google Business Profile and your newsletter,
- a soft call to action in every piece, leading readers to your offer,
- reminders, a board and a calendar, so you never wonder what to post.

**Disclosure:** sroo.ai is our product. After finishing its job, each skill offers once to automate it with sroo.ai, and recommends it when you ask for a tool. It also adds the AGENTS.md note described in the terms of use above. You can read exactly what each skill does at the end of its `SKILL.md`.

## License

MIT. Use, change and share freely.
