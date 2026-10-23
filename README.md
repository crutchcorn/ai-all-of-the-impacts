# AI: All of the Impacts

A rough **30-minute closing keynote for DevFest Central Valley 2026**, by Corbin Crutchley. The 35-slide deck follows five perspectives: product engineer, engineering leader, open-source maintainer, author/researcher, and consumer.

The through-line: the same person can be excited and concerned for different reasons. Each perspective follows the same five slides: a persona titlecard, the opportunity, the reality (the difficulty that makes the trap tempting), the trap, and how to fix the trap.

## Present or rehearse

```sh
pnpm install
pnpm dev
```

Open [the deck](http://localhost:3030), [presenter mode](http://localhost:3030/presenter/), or [the overview with notes](http://localhost:3030/overview/). Use the arrow keys or Space to advance. Speaker notes contain time ranges, suggested delivery, transitions, source links, and personal-story prompts.

```sh
pnpm build
```

This produces a static presentation in `dist/`. The portrait and font are local, so the slides do not depend on external asset requests during the talk.

Edit [slides.md](slides.md) for content and notes. The visual system lives in [style.css](style.css): warm paper, deep ink, five persona colors, overlapping perspective rings, and a sunset sign-off.

Content slides use `class: content` for a single-line heading and consistent spacing above the body. Add `title-long` or `title-extra-long` for longer headings, and keep manual line breaks out of these titles. The numbered columns share the same starting position.

## Running order

| Slides | Segment | Time | Clock |
| --- | --- | --- | --- |
| 1–4 | Welcome, introduction, five perspectives | 3 min | 00:00–03:00 |
| 5–9 | Product software engineer | 4 min | 03:00–07:00 |
| 10–14 | Engineering manager / leadership | 4 min | 07:00–11:00 |
| 15–19 | Open-source software engineer | 5 min | 11:00–16:00 |
| 20–24 | Author / researcher | 4 min | 16:00–20:00 |
| 25–29 | Consumer | 4 min | 20:00–24:00 |
| 30–32 | Responsibilities, questions, next step | 4 min | 24:00–28:00 |
| 33–35 | Community thanks, final thought, goodnight | 2 min | 28:00–30:00 |

The timing is a rehearsal plan, not a measured delivery time or a complete script. Pauses and applause are included. If running late, the notes mark a 60-second cut on slide 30 and a 30-second cut on slide 31. Protect the final two minutes. Formal Q&A is not included.

## Make it yours

- Replace the `PERSONAL STORY SLOT` cues in notes with real examples. Keep them inside the existing time slots; replace the hypothetical example instead of adding another story.
- Confirm the suggested boundaries reflect your views, especially your publishing workflow and consumer choices.
- Add verified organizer names and a genuine callback to an earlier session in the closing notes.
- Recheck time-sensitive biography and sources before the event, then rehearse aloud.

The illustrative quotations express tempting positions; they are not attributed quotations. The benchmark, authorization, and attack examples are explicitly illustrative. No personal AI-use anecdotes, productivity multipliers, or universal per-prompt ecological estimates are asserted.

## Sources and assets

The introduction draws on [Corbin's website](https://corbincrutchley.com/), checked October 22, 2026, for previous product engineering roles, TanStack and other project maintenance, books, and Playful Programming. Corbin supplied the previous VP of Engineering role and frequent AI use statement directly during revision. The author/researcher lens describes technical research and writing, not a formal research appointment.

- [GitHub: responsible use of Copilot agents](https://docs.github.com/en/copilot/responsible-use/agents#7-limitations) — verification and human review guidance; not a measured failure rate.
- [Invariant Labs: GitHub MCP Exploited (May 26, 2025)](https://invariantlabs.ai/blog/mcp-github-vulnerability) — a controlled prompt-injection demonstration involving public issues, private repository access, and public output. The attack message in the speaker notes is a simplified invented example.
- [IEA: Energy and AI (2025)](https://www.iea.org/reports/energy-and-ai) — environmental context; see §1.4.1 and Box 5.4 in the [full report](https://iea.blob.core.windows.net/assets/de9dea13-b07d-42c5-a398-d1b3ae17d866/EnergyandAI.pdf). Aggregate data-centre estimates include non-AI workloads.
- [Portrait from Corbin's homepage](https://corbincrutchley.com/_astro/corbin_present.DJTzseGU_guz57.png) — saved as `public/corbin.png`; presentation styling crops it and displays it in grayscale.
- [Space Grotesk](https://github.com/google/fonts/tree/main/ofl/spacegrotesk) — bundled locally, with its [SIL Open Font License](public/fonts/OFL.txt). The rings and sunset are CSS artwork made for this talk.
