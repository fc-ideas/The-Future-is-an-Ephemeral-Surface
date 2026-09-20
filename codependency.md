# The Strange Cognitive Tax of Working With AI

**Fabrizio Costa**  | September 2026

*AI can make you dramatically more productive while leaving you more dependent, more exhausted, and strangely unable to remember what you actually did.*

Open a repository you have been working on for three days. You know the project. You remember the reason for it, the rough shape of the architecture, and the last problem you were trying to solve.

Then you look at the files.

There is a `src` directory, a test directory, some configuration, a handful of services, and a long trail of small decisions. The names are familiar. The relationships are not. You find a function and remember asking for it. You do not remember writing it. You could probably explain what it is supposed to do. You would have to ask the machine to explain how it does it.

The repository has become an object.

This is one of the less visible changes AI is making to knowledge work. The loud questions are about capability, hallucinations, jobs, and productivity. The quieter question is what happens to the mind of a person who spends all day directing work they do not personally execute.

Programming used to force a fairly long walk from intention to artifact. You had an idea, chose an architecture, broke it into parts, and wrote the parts. The work contained plenty of drudgery, but the drudgery gave you contact with the thing you were making.

An AI coding system shortens that walk. You can stay at the level of intention:

“Build a service that does this.”

“Add authentication.”

“Write tests for these cases.”

“Find the bug.”

“Refactor this.”

The requests are not fake work. Choosing the goal, describing the constraints, and judging the result all require skill. But the code starts to feel less like something you wrote than something you commissioned.

That creates an awkward question: how do you know what you have?

The obvious answer is to ask the AI. Does the service handle concurrent requests? Are the tests meaningful? Is there a race condition? What happens when the network fails halfway through an operation?

The same system that built the object now gives you the tour.

You are no longer reading the code. You are reading an account of the code. That account may be useful. It may also leave out the exact thing you needed to notice.

The missing question is often the important one. You can ask the model to look for twelve weaknesses and still fail to ask about the thirteenth. You can approve a design because its explanation sounds complete. A smooth explanation can hide the fact that you never formed an independent picture of the system.

So the human task moves up another level. First you direct the implementation. Then you inspect the explanation. Then you have to decide what an adequate inspection would have looked like in the first place.

AI helps with that too. It can interview you, list assumptions, propose adversarial tests, and suggest criteria for success. This is powerful. It is also a little strange. The machine keeps removing the need to perform one task, and the human keeps acquiring a more abstract task in its place.

The abstraction has a cost.

At the end of a long AI-assisted session, you may not feel distracted. You may feel trapped inside the problem. The model produces one change. You inspect it while composing the next instruction. A new edge case appears. You revise the specification. The next result arrives before the previous decision has settled.

Lunch goes cold beside the keyboard.

The work resembles deep focus, but the object of focus is larger than it used to be. You are holding the goals, interfaces, constraints, failure modes, and future changes in your head at the same time. The code is out of sight, so more of the surrounding system has to remain mentally available.

That is why a short email can feel impossible in the middle of the session. It is not that the email is difficult. Leaving the problem means unloading a structure that took hours to assemble.

The machine has made you intensely monotask.

The waiting time of current systems can even help. A slow generation gives you a minute to rethink a decision or notice that your instruction was vague. A faster system may produce changes faster than you can form judgments about them. The bottleneck will not be execution. It will be thought.

And then the thought goes away.

While you are working, the project feels present. You know why the database is shaped that way. You know which shortcut you accepted and which one you rejected. You can see the whole arrangement, or at least it feels that way.

A few days later, you open the repository and have to load it again.

You read the documentation. You inspect the commits. You ask the model what changed. Gradually the system returns to view. The experience is not quite debugging and not quite learning. It is closer to reopening a half-remembered conversation.

Normally, making something and learning it happen together. Writing a function forces you to meet its constraints. Debugging teaches you where it breaks. Rewriting leaves a map in your head. Even tedious work has an encoding effect.

AI separates the two activities. You can produce an impressive amount of software without performing enough of the small acts that would make the software familiar.

The output remains. The residue may not.

That residue is part of expertise. A programmer develops instincts from thousands of encounters with awkward interfaces, bad assumptions, slow queries, and failures that appeared only after midnight. A researcher learns where useful evidence tends to hide. Someone who plans their own journeys eventually carries a rough map of rail lines, airports, and connections.

Delegate the encounters and some of the map never gets drawn.

This is where convenience starts to look like dependence. Imagine asking an AI to plan every train journey. It checks the times, notices the connection, and chooses the sensible route. After a while, planning the journey yourself does not feel like a skill waiting to be used. It feels like an avoidable administrative punishment.

The ability is still there. The friction has changed.

Walking feels slow after a bicycle. Manual arithmetic feels ridiculous after a spreadsheet. Looking through 20,000 lines of code feels irrational after you have become accustomed to asking, “Tell me what matters here.” The dependency does not arrive as helplessness. It arrives as a new baseline for what effort ought to cost.

That does not mean the answer is to use AI less. The higher-level work is real. Choosing the right abstraction, finding the hidden assumption, deciding what matters, and judging whether an artifact actually serves its purpose are not consolation prizes for people who can no longer implement things. They are often the work experts were trying to reach.

But we do not yet have good habits for keeping our understanding while working at that altitude.

One useful habit would be deliberate reconstruction. Close the model and explain the architecture from memory. Draw the dependency graph. Write down the three assumptions most likely to hurt you. Predict the next failure before asking for a review. Implement one awkward part yourself, even when delegation would be faster.

The point is not to worship friction. It is to spend enough of it that the work leaves a trace.

It may also help to keep the machine from becoming the first and last witness to every decision. Read the code before requesting a summary. Make a guess before asking for a diagnosis. When the model proposes a design, state what you think is wrong with it before asking what it missed.

These practices will feel inefficient. That is partly the point. Learning has always required some contact with resistance.

The odd possibility is that AI will create people who are more capable and less self-sufficient at the same time. They will build systems that would once have required a team. They will spend whole days in serious concentration. They will make decisions at a level of abstraction that used to belong to senior engineers and managers.

Then, a week later, they will open the project and ask the machine:

Remind me what we built.

---
[[back]](README.md)
