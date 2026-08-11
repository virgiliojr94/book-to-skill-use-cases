# book-to-skill — Use Cases

Real accounts of what people did with [book-to-skill](https://github.com/virgiliojr94/book-to-skill): the document, the command, the numbers, and what the generated skill is actually good for.

Each entry is one line here and a Gist on the author's own account. This repository hosts **no generated skills and no book content** — only the index.

**[study.md](study.md)** · **[work.md](work.md)** · **[research.md](research.md)**

---

## What belongs here

A use case is **evidence of use**. Bring one of these two — both if you have them:

- **The numbers from the run.** The document (format, pages), the command including `--mode`, and what the extractor reported: tokens, chapters detected, ToC found or not.
- **What came of it.** What the skill was used to produce or decide, and at what scale — a survey that reached 300 people, a manual that stopped being re-read, a decision that changed.

And, always, **where it fell short**. That part is not optional. An account where nothing went wrong is an advertisement, and reads like one.

Say whether you had the right to read the document — bought copy, company material, open licence, public domain.

Write in whatever language you think in. The index line follows your Gist's language.

## What does not

- **Generated skill content.** Do not paste chapter summaries, glossaries, or any part of the skill's output. See the [Copyright & fair use](https://github.com/virgiliojr94/book-to-skill#️-copyright--fair-use) policy: skills derived from third-party books stay private, and that rule does not stop applying because the copy is in a Gist.
- **Book text.** Not a paragraph, not a page.
- **Product promotion.** If the point of the entry is a tool, service, or course you sell, it is an ad. Entries without measurements are read as ads.

This is not the place to get your project linked from book-to-skill — that is [covered in CONTRIBUTING](https://github.com/virgiliojr94/book-to-skill/blob/master/CONTRIBUTING.md) and reserved for sponsors. A use case is about the conversion you ran, not about you.

## How to submit

1. Write your account as a **public Gist** on your own account, following [TEMPLATE.md](TEMPLATE.md).
2. Fork this repository and add **one line** to the file that fits — `study.md`, `work.md`, or `research.md`.
3. Open a pull request. No template, no checklist, no CI — a one-line change gets a fast look and a merge.

### Line format

```markdown
- [Short title, what you converted and why](gist-url) — <the evidence, short> — by [@you](https://github.com/you)
```

The middle field is whichever evidence your account carries — the run's numbers, or what came of it:

```markdown
- [Turned a 312-page regulatory manual into a lookup skill](gist) — PDF, 312p, technical, ~240K tokens — by [@someone](https://github.com/someone)
- [A DevEx book became a skill, then a survey of 300+ engineers](gist) — EPUB → survey applied to 300+ developers — by [@someone](https://github.com/someone)
```

Keep it to one line. If the title needs a second sentence, that sentence belongs in the Gist.

---

## Housekeeping

Entries belong to their authors, who are responsible for what their Gists contain. The index itself is MIT, like the project.

Dead links are removed when noticed. If your Gist moves or you want your entry gone, open an issue or a PR removing the line — no explanation needed.
