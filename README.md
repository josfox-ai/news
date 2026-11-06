# News of the `.jos` open standard and the JOSFOX tools

This repository is the public changelog of two things that share one format. Items about the **JOS community** charism cover the `.jos` specification, its reference kernels and its community; reading them and using what they announce requires no account. Items about the **JOSFOX** charism cover products and distributions that JOSFOX LLC builds on top of the standard. Every item says which of the two it belongs to in its first lines.

`.jos` is an open JSON format for declaring an AI agent's intention, success criteria and guardrails, served as `application/vnd.jos+json`. This repository tells you when any of that changes and gives you the source for each statement.

## Why a repository instead of a blog

- A news item here is a plain Markdown file under `news/`, named `YYYY-MM-DD-slug.md`, so it can be diffed, quoted and cited by commit.
- Each statement that carries a number or a status points to where it was measured. If a fact cannot be sourced, it is left out.
- A correction is a new item that names the item it corrects. Published items are not rewritten.
- Nothing here is paywalled, tracked or gated behind a signup.

## How to follow

- **Watch** this repository on GitHub, or subscribe to its commit feed: `https://github.com/josfox-ai/news/commits/main.atom`.
- Browse the `news/` folder; the file name sorts by date, newest at the bottom.
- Open an issue in this repository to report an error in an item. Questions about the format itself belong in the [specification issue tracker](https://github.com/josfox-jos/jos-spec/issues).

## Latest item

[2026-11-06 — Specification 2.0.0 under IANA review, kernels 2.1.0 on npm and PyPI, the JOS Omni hub opens](news/2026-11-06-first.md)

## Format of an item

```
# <title>
Date: YYYY-MM-DD · Charism: JOS community | JOSFOX
<one-paragraph summary: what changed and why it matters to you>
## Details
<facts, each with its source in an HTML comment>
## Not yet
<what is announced but not yet verifiable, stated as such>
```

## Where the news comes from

- [The `.jos` specification repository, normative text and conformance kit](https://github.com/josfox-jos/jos-spec) — version tags and the IANA registration status.
- [The `.jos` community start page and reference tool guide](https://github.com/josfox-jos/jos) — kernels and command line.
- [JOS Omni, the distribution documentation hub](https://github.com/josfox-ai/jos-omni) — platform targets and their availability.
- [The `.jos` landing page source](https://github.com/josfox-jos/jos.mx) — the short public summary of the standard.
- [The 0.0.7 draft that preceded the standard](https://github.com/josfox-ai/jos-format-spec) — history, for readers of old documents.
- [Agent2Agent protocol fork carrying `.jos`](https://github.com/josfox-ai/A2A.jos) and [its JavaScript SDK fork](https://github.com/josfox-ai/.jos-a2a-js) — interoperability work.
- [The JOSFOX AI deep-link helper](https://github.com/josfox-ai/josfoxai-deep-link) and [its reserved mirror name](https://github.com/josfox-jos/josfoxai-deep-link) — JOSFOX product utilities.

---

Items are published under CC BY 4.0 unless an item states otherwise. `.jos` is maintained in the open by JOSFOX LLC as change controller.
