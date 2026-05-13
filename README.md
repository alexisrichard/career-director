# Career Director

> An open methodology for running a thorough, professionalized job search alongside an AI assistant.
> Hand this repo to your AI, and it can guide you through the same process end-to-end.

## What this is

A small set of templates and instructions that let an AI assistant act as your **personal head of talent**: someone who runs a long structured interview with you, builds a rich private inventory of your career, helps you design and tailor application materials, scouts the market, and tracks your pipeline.

It started as the workflow one candidate built with [Claude Code](https://claude.com/claude-code) during their own search. Sharing it publicly so anyone can use the same approach.

## Who it's for

- Candidates running a senior or strategic job search (Head of X, leadership, FDE, etc.) where one-size-fits-all CVs lose
- People who want their AI to know them deeply enough to write *actually good* tailored materials, not generic outputs
- Job-seekers willing to invest 2-4 hours upfront in a structured interview to get years of leverage on the output

## How to use it

1. **Clone this repo** into a folder where you'll run your search.
2. **Open it in an AI coding environment** (Claude Code, Cursor, or similar — anything with filesystem access).
3. **Point your AI at [`LLM-INSTRUCTIONS.md`](LLM-INSTRUCTIONS.md)** as the starting point. It tells the AI what to do.
4. **Sit through the long interview** — yes, it's long. That's where the leverage comes from.
5. **Iterate.** The methodology assumes weeks of back-and-forth, not a one-shot generation.

## What's in here

- [`LLM-INSTRUCTIONS.md`](LLM-INSTRUCTIONS.md) — the methodology, written for the AI to read first
- [`templates/`](templates/) — starter files the AI will fill in with you:
  - `CLAUDE.md.template` — project brief / context file the AI keeps loaded
  - `Career_Inventory.md.template` — the master inventory built during the long interview
  - `Tracker.md.template` — application pipeline tracker

Note on the CV: there is intentionally no CV template in this repo. CVs are personal aesthetic artifacts, and a one-size-fits-all template fights every candidate's actual preferences. The methodology instead has the AI ask *you* for a CV you want to model after — your existing one, or one you admire — and build from there.

## Philosophy

- **Preserve your authentic voice.** No buzzwords, no over-claiming, no LinkedIn-About bullshit. The AI is there to amplify *you*, not flatten you into corporate-ese.
- **Build context iteratively.** Most candidates skip the inventory step and go straight to "write me a CV." The leverage is in the inventory.
- **Distinguish public material from private context.** Some things belong on a CV, some in a cover letter, some only in interviews, some never spoken aloud. The AI should learn which is which for you.
- **Be honest.** The AI should function as an adversarial TA specialist, not a yes-man. When your draft is weak, it should say so.

## License

MIT. Take it, fork it, improve it.
