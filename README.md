# book-to-skill — Use Cases

Real accounts of what people did with [book-to-skill](https://github.com/virgiliojr94/book-to-skill): the document, the command, the numbers, and what the generated skill is actually good for.

Each entry is one line here and a Gist on the author's own account. This repository hosts **no generated skills and no book content** — only the index.

**[study.md](study.md)** · **[work.md](work.md)** · **[research.md](research.md)**

---

## What belongs here

A use case is **evidence of use, with measurements**. Yours qualifies if you can state:

- the document — format, page count, and whether you had the right to read it
- the command you ran, including `--mode`
- what the extractor reported: tokens, chapters detected, ToC found or not
- what the skill is good for in practice — and where it fell short

The last part matters as much as the rest. An account where nothing went wrong is an advertisement, not a use case.

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
- [Short title, what you converted and why](gist-url) — FORMAT, Np, MODE, ~NK tokens — by [@you](https://github.com/you)
```

Example:

```markdown
- [Turned a 312-page regulatory manual into a lookup skill](https://gist.github.com/...) — PDF, 312p, technical, ~240K tokens — by [@someone](https://github.com/someone)
```

Keep it to one line. If the title needs a second sentence, that sentence belongs in the Gist.

---

## Housekeeping

Entries belong to their authors, who are responsible for what their Gists contain. The index itself is MIT, like the project.

Dead links are removed when noticed. If your Gist moves or you want your entry gone, open an issue or a PR removing the line — no explanation needed.
