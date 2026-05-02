# CV — Oleksandr Honchar

A single-file HTML CV that prints perfectly to one A4 page. Self-hosted on GitHub Pages, served as a public URL — recruiters get an always-fresh CV without me having to email a PDF.

📄 **Live:** **[b1toks.github.io/cv](https://b1toks.github.io/cv/)**

---

## What it is

- One `index.html` file — Tailwind via CDN, FontAwesome icons, Inter typeface
- Print-optimized: `@media print` rules collapse padding, hide buttons, keep section breaks clean. **Ctrl+P → Save as PDF** gives a flawless A4 export
- "Download PDF" button visible on screen, hidden on print
- ATS-friendly text (no images, no SVG-rendered text — everything is real DOM text)
- Linked from [honchar.dev](https://www.honchar.dev) so the portfolio always shows the latest version

---

## Why a static CV repo

A live URL solves the "every recruiter gets a different version" problem. Push once → every link to my CV updates simultaneously. No more "PDF v3 final FINAL.pdf" in email threads.

The HTML is hand-written (~600 lines including print styles) — no static site generator, no build step. `git push` → GitHub Pages auto-publishes within ~30 seconds.

---

Built by **Oleksandr Honchar** · [honchar.dev](https://www.honchar.dev) · [LinkedIn](https://www.linkedin.com/in/honchar-oleksandr/)
