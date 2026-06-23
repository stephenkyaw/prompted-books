# Prompted Books

> Original, AI-generated technical books for working engineers — clean, practical, and built around real projects.

**Prompted Books** is a growing library of tech books, each one generated with AI, reviewed by a human, and typeset to read like a real published book. Every title focuses on a single stack and teaches it the way it's actually used in production — not as an API reference, but as a project you build from start to finish.

The first title covers React. Backend, Python, and more are on the way.

---

## What this is (and isn't)

This is **not** a curated list of other people's books. Every book here is **original content**, written from scratch through a prompt-driven workflow and then reviewed for accuracy and clarity.

Each book is:

- **Practical and project-based** — concepts are introduced, then immediately applied to one running project that grows across the whole book.
- **Production-minded** — the focus is on what teams actually ship: real libraries, real patterns, real trade-offs.
- **Written for people who already code** — no "what is a variable." These books assume programming fundamentals and move fast.
- **Typeset, not dumped** — clean covers, readable typography, syntax-highlighted code, and proper PDF formatting.

## How these books are made

Each book follows the same repeatable pipeline:

1. **Content generation** — a detailed structured prompt produces the full manuscript, chapter by chapter, around a single project spine.
2. **Human review** — the draft is read for technical accuracy, outdated APIs, and clarity. Code is sanity-checked.
3. **Typesetting** — the reviewed content is rendered into a clean, book-style PDF (custom cover, running headers, calm code blocks, consistent layout).

The prompts used to generate and style the books live in [`/prompts`](./prompts) so the process is transparent and reusable.

## ⚠️ Accuracy note — please read

These books are **AI-generated and human-reviewed**, but they are not infallible. Large language models can produce subtle mistakes: a wrong function signature, an outdated version behavior, or a pattern that's fallen out of favor. Treat each book as a strong, fast-moving learning companion — **not** as authoritative documentation.

Always cross-check critical details against the official docs for the tools involved, and **open an issue** if you spot something wrong. Corrections make the whole library better.

## Catalog

| Book | Stack | Status | Format |
|------|-------|--------|--------|
| **Production React App 2026** | React, TypeScript, Next.js, TanStack Query, Zustand, Tailwind, shadcn/ui, RHF + Zod, testing | ✅ Available | PDF |
| **Production Backend** *(working title)* | TBD | 🛠️ Planned | — |
| **Practical Python** *(working title)* | TBD | 🛠️ Planned | — |

*More titles added as they're written. Suggestions welcome via Issues.*

## Format & design

Every book ships as a typeset PDF with:

- A clean cover and consistent visual identity per series.
- Readable body typography with generous spacing.
- Syntax-highlighted, copy-friendly code blocks.
- Running headers, page numbers, and a table of contents.

Source HTML is included alongside each PDF where available, so you can re-export or adapt the styling yourself (open in Chrome → Print → Save as PDF reproduces the book).

## Repository structure

```
prompted-books/
├── react/
│   ├── production-react-app-2026.pdf
│   ├── production-react-app-2026.html
│   └── README.md            # book-specific notes & changelog
├── backend/
├── python/
├── prompts/                 # generation + styling prompts
│   ├── content-prompt.md
│   └── style-prompt.md
├── assets/                  # shared covers, logos, fonts
└── README.md                # you are here
```

Each stack gets its own folder. Each book is a self-contained PDF (plus optional source) inside it.

## Reading & downloading

Open any book's folder and download the `.pdf` directly, or browse the rendered file on GitHub. No build step is required to read — the PDFs are the product.

## Roadmap

- [x] First title: **Production React App 2026**
- [ ] Backend fundamentals book
- [ ] Python book
- [ ] Publish the generation + styling prompts
- [ ] Consistent series cover system across all books
- [ ] EPUB exports in addition to PDF

## Contributing & feedback

This is a personal project, but feedback is genuinely useful:

- **Found an error?** Open an Issue with the book, page, and what's wrong.
- **Want a topic covered?** Open an Issue describing the stack and who it's for.
- **Improvements to a prompt or to the styling?** PRs welcome.

## License

Suggested setup (adjust to your preference before publishing):

- **Prose / book content:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — free to share and adapt with attribution.
- **Code samples:** [MIT](https://opensource.org/licenses/MIT) — use them anywhere.

> Decide and commit a `LICENSE` file before making the repo public.

## Author

Built and maintained by **[your name]** — [github.com/yourusername](https://github.com/yourusername).

If these books help you, a ⭐ on the repo is appreciated and helps others find it.
