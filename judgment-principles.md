# Call 1 · Judgment — Full Script

**Segment:** Before AI: fix the workflow first
**Speaker:** Alexios
**Length:** ~25 min (≈15 min talk + ~7 min live exercise + buffer)

> Read this as written if you want, but it is built to be spoken, not recited. The bracketed lines are stage directions, not words to say. Slide cues match the deck.

---

## 1 · Open and positioning  (≈3 min) — slides 1–2

I want to start by saying something that should probably get me thrown off the mentor list. I am the mentor on this programme who is going to spend the next twenty-five minutes trying to talk you out of using AI.

Not entirely, so let me be precise, because the precision is the whole point. I am not anti-AI. I have built more legal tools in the last year than I can keep track of. What I am against is reaching for AI as the first move. Most of the time, when a lawyer says "I want to use AI for this," the honest answer is that the thing they are trying to solve was never an AI problem. It is a workflow problem wearing an AI costume.

So before any of you opens an IDE this fortnight, I want to give you two things. A way to fix the thing in front of you with no technology at all. And a test for deciding whether technology is even warranted. If you leave with nothing else, leave with the test.

[Beat. This is the contract with the room. Do not rush it.]

---

## 2 · Fix the workflow first  (≈5 min) — slides 3–5

Here is the first uncomfortable truth. Almost none of your workflows were designed. They were inherited. Someone three associates ago set up a way of doing things, it survived, people copied it, and now it is simply how the work happens. Nobody chose it. It accreted.

That matters, because when something is inherited rather than designed, it fills up with dead weight that nobody can see, because everybody is too close to it.

So the first exercise is not technical at all. Take one workflow that you personally find painful. Not the one you think is most important. The one that actually annoys you, because annoyance is a reliable signal that something is wrong.

Map it as it actually runs, not as the policy says it runs. Every step, every handoff, every approval, every place the work sits in an inbox waiting for someone to get to it.

Then time each step. Roughly is fine. You are looking for where the hours actually go, and you will be wrong about where they go. Everyone is.

When you do this honestly, you tend to find that thirty to forty percent of the elapsed time is dead weight. An approval that exists because of a problem from 2014 that no longer exists. A reformatting step that the next person undoes anyway. A document that gets produced and never read. None of that needs AI. It needs deleting. Deleting it is free, it is reversible, and it teaches you what the workflow is actually for.

Do that first. Because if you automate a broken process, all you have done is build a broken process that runs faster and that you now trust more. That is worse than where you started.

[This is the line that should make a few of them wince. Let it land.]

---

## 3 · The test: do I actually need AI?  (≈6 min) — slides 6–8

Now suppose you have cleaned the workflow and there is still real friction left. This is the moment people reach for AI, and this is exactly the moment to slow down.

I use four questions. Volume, Pattern, Stakes, Verification. A task earns AI only if it passes all four. Miss one and you are usually better off with a checklist, a template, or a junior.

**Volume.** Does this happen often enough to matter? If you do something twice a year, the time you spend building and maintaining a tool will never be repaid. Be ruthless here, because we all overestimate how often the interesting problems recur.

**Pattern.** Is the task patterned enough that a machine can do it, and varied enough that a fixed template cannot? That is the sweet spot, and it is narrower than people think. If every instance is identical, you do not need AI, you need a form. If every instance is genuinely novel, the model will guess, and you will not catch the guess.

**Stakes.** What happens if it is wrong, and who carries that? This is the question lawyers are uniquely equipped to ask and uniquely prone to skip when a new tool excites them. High stakes do not disqualify AI. They change the design. They mean a human signs off on every output, they mean you keep a record of what the model saw and what it produced, and they mean you stay honest that you are accountable for the result whatever the machine did.

**Verification.** Can you check the answer faster than you could have produced it yourself? This is the one that quietly decides everything. If verifying the output takes as long as doing the work, the AI has saved you nothing. It has moved your labour from production to inspection and added a layer of false confidence on top. The tasks worth automating are the ones where you can confirm a good answer at a glance, even though writing it yourself would have taken an hour.

Let me run two real tasks through this so it is concrete.

First, drafting a non-disclosure agreement from a counterparty's redline. Volume, high, you see these constantly. Pattern, yes, the moves repeat but every redline is a little different, so a template alone fails. Stakes, real but bounded, and a partner reads it before it goes out. Verification, fast, an experienced lawyer spots a bad clause in seconds. That passes all four. Build it.

Now, advising on a genuinely novel regulatory question in a jurisdiction you have never worked in. Volume, low, it may never recur. Pattern, none, that is what makes it novel. Verification, slow, you would have to do the whole analysis yourself to know whether the model was right. That fails three of the four. Do not build it. Do the work.

So run a real task through the four questions in your head right now. Most tasks fail at least one. The ones that pass all four are your candidates for this fortnight, and there are fewer of them than you are hoping.

---

## 4 · If you do build  (≈2 min) — slides 9–10

Say a task passes. Two quick warnings before you build, because this is where senior people waste the most time.

First, build inside the stack your firm has actually approved, not the ideal stack you read about on a Saturday. The most elegant tool in the world is worthless if your IT function will not let it near a client document. Start from what is permitted and work backwards. Constraint first, capability second.

Second, default to throwaway. Most of what you build this fortnight should be a script you run a few times and then delete. The instinct of careful people is to build something permanent, robust, and documented. Resist it. A permanent build is a maintenance commitment, and the moment you take on maintenance you have quietly started becoming a developer. Which brings me to the last thing.

---

## 5 · The real edge, and close  (≈2 min) — slides 11–12

Here is what I want you to walk away holding.

The point of building is not to become a developer. You will not out-engineer the engineers, and you should not try. The point of building is that it changes your judgment. Once you have actually tried to make a machine do a piece of legal work, you understand in your hands where it is strong, where it is dangerous, and where it is quietly wrong in a way that only a lawyer would catch. That understanding is not available from reading about AI or sitting through a demo. It comes from building, and then stepping back.

So the senior lawyer's real edge at the end of this is not a tool. The tool is disposable. The edge is a judgment that has been informed by building. You become the person in the room who can look at an AI workflow and say, with authority, here is where this fails and here is who is liable when it does. That is worth more than any tool you will ship, and it is the one thing this residency is actually here to give you.

So the method is simple to state, even if it is hard to practise. You fix the workflow before you reach for technology. You put every candidate task through the four questions and you build only the ones that pass all four. You keep the build disposable so it never turns into a second job. And you treat the whole exercise as a way of sharpening your own judgment rather than a way of producing software.

[Hand off to Erin.]

Then you hand it to Erin, who is going to tell you whether anyone other than you will ever actually use the thing you built.

---

## 6 · Live exercise  (≈7 min) — slide 13

> Run this if the format allows it. It is worth more than another five minutes of me talking.

**Prompt to the room:**
"Pick one task you do that you wish a machine would do for you. Take ninety seconds and run it through the four questions. Volume, Pattern, Stakes, Verification. Write a yes or no next to each."

[Silence for ~90 seconds. Resist filling it.]

**Then:**
"Hands up, who had a task that passed all four? ... Now, who had one fail on Verification specifically?"

[Take two or three out loud. The Verification failures are the most instructive, because they are the ones people most wanted to automate. Use them to reinforce the point: the task you most want to hand to AI is often the one you can least afford to.]

**Close the exercise:**
"Keep the one that passed. That is your candidate for week one. Bring it to your mentor."
