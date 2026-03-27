# Prompt Calibrator

> Think first. Prompt better.

Most people open ChatGPT, Claude, or Gemini and type a quick sentence. They get a mediocre response — not because AI is bad, but because the prompt was too vague.

**Prompt Calibrator** walks you through a structured setup and generates a copy-ready prompt in real time. No prompt engineering knowledge required. Nothing leaves your browser.

👉 **[Try it live → promptcalibrator.com](https://promptcalibrator.com)**

---

## What's New in v0.5.0

v0.5.0 is a major expansion. The tool now supports **four context-aware modes**, a live **side-by-side comparison panel**, and a fully redesigned modal system.

See [`CHANGELOG.md`](./CHANGELOG.md) for the full history.

---

## Modes

Each mode surfaces the fields that actually matter for that context — instead of giving everyone a generic template.

| Mode | Built for |
|------|-----------|
| 🏢 **Agency** | Strategists, analysts, consultants building client-facing work |
| 🏫 **Education** | Teachers, counselors, curriculum designers |
| 📚 **Pre-college** | Middle and high school students doing homework, projects, test prep |
| 🎓 **College / Grad** | Undergrad and graduate students working on papers, theses, exams |

---

## How It Works

Each mode guides you through up to six structured fields:

1. **Task** — what you want to accomplish
2. **AI Role / Support Mode** — who the AI should act as, or how it should engage
3. **Context** — client/audience, class/course, or assignment details
4. **Additional Context / Guardrails** — constraints, deadlines, academic rules
5. **Tone** — concise, formal, conversational, rigorous, etc.
6. **Format** — bullet points, prose, step-by-step, annotated feedback, etc.

Every generated prompt automatically includes a closing instruction tailored to the mode — grounding the AI in honesty, academic integrity, or pedagogical care depending on context.

---

## Features

- **Real-time prompt preview** with color-coded sections (task, role, context, constraints, style)
- **Chip-based selection** — click to build, type to customize, mix both
- **Side-by-side comparison panel** — see the difference between a vague and a structured prompt for each mode
- **"See an Example" modal** — loads a real scenario into the form with one click
- **One-click copy** with word and character count
- **Modal system** — How It Works, Philosophy, Privacy, and Feedback all accessible in-app
- **Fully responsive** — mobile layout with sticky output and horizontal scroll nav
- **Zero dependencies** — no npm, no build step, no frameworks
- **No backend, no login, no data collection** — everything runs client-side

---

## Philosophy

**AI shouldn't write your prompt.** That's the line this tool holds.

Many tools use AI to generate prompts for you. Prompt Calibrator doesn't. The structure helps you think more clearly *before* you type — so the thinking stays yours. The goal isn't just one good prompt; it's building the habit of structuring your thinking before talking to AI.

A few more principles behind the design:

- **Prompts are situational.** A teacher and a consultant don't need the same prompt. Generic templates are a shortcut that usually shows.
- **Private by design.** No login, no storage, no cross-site tracking. Your words go nowhere.
- **Prompt literacy over prompt dependency.** The chip options are a starting point — the free-text fields are where your actual thinking goes.

---

## Tech Stack

Pure HTML, CSS, and vanilla JavaScript. Single file (`index.html`). No build toolchain, no package manager, no runtime dependencies.

Deployed via GitHub Pages with a custom domain.

---

## Project Structure

```
prompt-calibrator/
├── index.html      # The entire application — HTML, CSS, and JS in one file
├── CHANGELOG.md    # Version history
├── LICENSE         # MIT
└── CNAME           # Custom domain config for GitHub Pages
```

---

## Roadmap Ideas

- [ ] Shareable prompt URLs (encoded in query params, no backend needed)
- [ ] Save / load prompt drafts via localStorage
- [ ] Additional modes (job seekers, researchers, small business owners)
- [ ] Prompt history panel

Have a suggestion? [Open an issue](https://forms.gle/swowCCqR3K2ULhzn9) or use the in-app feedback form.

---

## License

MIT — free to use, fork, and build on. Credit appreciated.

---

*Built by [Adrian Wang](https://github.com/adrianwxy)*