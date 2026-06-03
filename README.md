# `/before-ai`

**Fix the workflow before you automate it.**

A Claude Code command that takes one real workflow you bring and helps you decide — from first
principles — what to *delete*, what to *simplify*, and only then whether any of it has actually
*earned* AI. It is built on one idea from a residency talk on judgment: most of the time, when someone
says *"I want to use AI for this,"* the honest answer is that the thing was never an AI problem — it
was a workflow problem wearing an AI costume.

## The one thing that makes it different: it asks, it never advises

`/before-ai` will not tell you "delete this step" or "build that tool." It asks you questions — one at
a time, logically sequenced — until *you* can see the answer, and then it has you rate it yourself. The
judgment stays with you. That's the whole point: the residency's lesson is that a senior person's real
edge is *judgment informed by building*, not the tool. So the command sharpens your judgment instead of
substituting for it.

## What it does (≈25–35 minutes)

1. **Maps your workflow as it really runs** — every step, handoff, approval, and the time work sits
   waiting in someone's inbox.
2. **Interrogates every step from first principles** — does this stop a *real, current* risk, or is it
   inherited, political, or duplicated? Could the same result happen with less bureaucracy? *You decide
   and rate each step.*
   > Example: appointing a subsidiary CEO needs five approvals. What is each reviewer actually
   > checking? Which is a live risk control and which is inherited or political? What breaks if it's
   > one or two instead of five — and who's accountable then? You conclude; the command only asked.
3. **Runs the survivors through the four-question test** — a task earns AI only if it passes **all
   four**:
   - **Volume** — does it happen often enough to repay building a tool?
   - **Pattern** — patterned enough for a machine, varied enough that a fixed template fails?
   - **Stakes** — if it's wrong, what happens, and who's accountable?
   - **Verification** — can you check a good answer faster than producing it yourself? *(The quiet
     decider — the command pushes hardest here.)*
4. **You reach your own decision** — delete, simplify, template, junior, or build it as a *throwaway*
   in your firm's approved stack.
5. **An optional skeptic** pressure-tests your conclusions before you commit.

You walk away with **two files you own**: a redesigned `workflow.md` and a `judgment-report.md` to
bring to your mentor.

## Install

```
/plugin marketplace add SaifAlYounan/before-ai
/plugin install before-ai
```

Then run it:

```
/before-ai approving a new subsidiary CEO
```

Already mapped your process? Jump straight to the four-question test:

```
/before-ai --quick
```

## A 30-second taste

```
You:  /before-ai approving a new subsidiary CEO

It:   [orientation panel — what this is, the 5 steps, ~25–35 min]
      Full walkthrough, or --quick?
You:  Full.
It:   Who runs this approval today, and how often does it happen?
You:  Group legal coordinates it; maybe 6–8 times a year.
It:   Walk me through it — what's the very first thing that happens once a name is proposed?
      ... [maps every step + the waiting] ...
It:   Five people sign off. Take the second reviewer — what are they checking that the
      first one didn't?
You:  ...honestly, the same thing.
It:   So if that second sign-off vanished tomorrow, what concretely goes wrong — and who's
      accountable if it does?
You:  Nothing really. It's there so the regional head feels included.
It:   Is that protecting the work, or protecting a person's visibility? And on a 1–5 — how
      essential is this step?
You:  Political. 2.
      ... [you reach "five approvals → two", then the four-question test, then your decision] ...
```

It never said "cut it." You did.

## What's under the hood

One self-contained command file (`commands/before-ai.md`) holds the engine: the orientation panel, the
*ask-never-advise* law, the six phases, the step-interrogation rubric, and the four-question test. The
two deliverable scaffolds live in `templates/`. The verbatim source talk the method comes from is in
`judgment-principles.md`. No accounts, no API keys, no external service — it runs on your own Claude,
and everything it produces is plain markdown you own and can edit.

## License

MIT © Alexios van der Slikke-Kirillov. See [LICENSE](LICENSE).
