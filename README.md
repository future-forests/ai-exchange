# AI Exchange — Tools, Links & Experiences

A shared space for collecting AI tools, useful links, and first-hand experiences from our research and daily work — what works, what doesn't, and how to use it responsibly.

## Why this repo

AI tools (LLMs, coding assistants, transcription, literature search, image analysis, ...) are changing fast, and everyone is experimenting on their own. This repo is meant to:

- **Avoid duplicated trial-and-error** — if someone has already tested a tool, learn from their experience
- **Share concrete workflows** — prompts, scripts, and setups that actually worked
- **Document pitfalls** — hallucinations, licensing issues, data-protection concerns, reproducibility problems
- **Build common ground** — a basis for discussing good practice in our group

## Structure

```
.
├── README.md             ← you are here
├── tools/                ← one file per tool (template below)
├── links.md              ← annotated link collection: articles, tutorials, papers, talks
├── experiences/          ← short write-ups: "I tried X for task Y, here is what happened"
├── prompts/              ← reusable prompts and prompt patterns
├── scripts/              ← small helper scripts (API wrappers, batch processing, ...)
└── guidelines/           ← data protection, citation, licensing, institutional policies
```

## How to contribute

1. **Add a tool**: copy `tools/_template.md`, fill it in, commit (or open a merge request if you prefer review).
2. **Add a link**: append it to `links.md` with one or two sentences on why it's worth reading and what you took from it — never a bare URL.
3. **Share an experience**: add a short markdown file to `experiences/` — a few paragraphs is enough. Date it and name the tool and task.
4. **Open an issue** to ask "has anyone tried ...?" or to propose a discussion topic.

No contribution is too small. A two-line note saying "tool X failed completely at task Y" saves everyone else an afternoon.

### Tool entry template

```markdown
# Tool name

- **What it does**:
- **Access / cost**: (free, institutional license, paid, self-hosted)
- **Data protection**: (where does your data go? OK for unpublished data?)
- **Tested by**: name, date
- **Verdict**: (short — recommended / promising / avoid)

## Notes
What you tried, what worked, what didn't.
```

### Link entry format (`links.md`)

```markdown
- [Title](https://...) — one or two sentences: what it is, why it's useful,
  what you learned from it. *(added by name, date)*
```

## Ground rules

- **Be concrete.** "ChatGPT is useful" helps no one; "GPT‑x reliably converted my messy field notes CSV to long format with this prompt" does.
- **Mind data protection.** Do not paste unpublished data, personal data, or confidential documents into external tools — and flag tools where this is a risk.
- **Cite and disclose.** Follow journal and institutional policies on declaring AI use in publications.
- **Experiences are opinions.** Dated, personal, and allowed to disagree with each other.

## Getting started

- Browse `tools/` for what's already documented
- Check open issues for current questions
- Add your first experience — even one sentence

---

*Maintained by: [name / group]. Questions and suggestions welcome via issues.*
