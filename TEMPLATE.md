# Gist template

Copy this into a public Gist on your own account, fill it in, delete the notes in parentheses. Nothing here asks for the skill's content — keep it out.

Sections you cannot fill are better left out with a line saying so than filled with guesses. "I did not keep the extraction metadata" is a real answer; an invented token count is not. The two sections that carry the account are **what came of it** and **where it fell short** — if you have those, send it.

---

## What I converted

(Format, page or section count, and what kind of document it is. Name the title only if you are comfortable doing so — "a 400-page machine-learning textbook" is a perfectly good answer. State that you had the right to read it: bought copy, company document, open licence, public domain.)

## Why

(What you wanted the agent to be able to do afterwards. Be concrete: "answer regulatory questions without me re-reading the manual" beats "study it better".)

## The run

```bash
python3 scripts/extract.py <...>
/book-to-skill <...>
```

(Include `--mode` and any flags. If you ran it more than once because the first pass came out wrong, that is the interesting part — show both.)

## What the extractor reported

(From `metadata.json`: chars, words, estimated tokens, chapters detected, ToC found or not. Paste the numbers, not the text.)

```json
{
  "estimated_tokens": ...,
  "chapters_detected": ...,
  "has_toc": ...
}
```

## What the skill is good for

(In practice, weeks later: what do you ask it? What does it answer well?)

## What came of it

(Optional if you filled in the numbers above, essential if you did not: what did the skill help you produce or decide, and at what scale? A survey, a document, a decision, a process that changed.)

## Where it fell short

(Required. Extraction problems, chapters it missed, questions it answers badly, anything you had to fix by hand. An account with an empty section here is not useful to anyone — and if the tool really did everything right, say what you expected to break and didn't.)

## Environment

(OS, Python version, which optional extractors `--check` reported, the agent host you ran it in.)

---

*Generated skill content and source text do not go in this Gist. Summaries, glossaries, chapter files and book passages all stay on your machine — see the [copyright policy](https://github.com/virgiliojr94/book-to-skill#️-copyright--fair-use).*
