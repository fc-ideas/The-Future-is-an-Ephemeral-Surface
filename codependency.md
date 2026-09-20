# The Strange Cognitive Tax of Working With AI

**Fabrizio Costa**  | September 2026

*AI can make you dramatically more productive while leaving you more dependent, more exhausted, and strangely unable to remember what you actually did.*

There is a peculiar moment that arrives when you have been working with an AI system for long enough. You open a repository you spent three days building and realize you barely know what is inside it.

You know what the software does. You know the services it exposes. You remember why you built it and perhaps even the arguments that led you to its architecture. But the code itself has become strangely foreign. There are hundreds or thousands of lines somewhere underneath, along with tests, configuration files, dependencies, error handling, and implementation choices. You were involved in creating all of it. Yet you never really saw it.

The repository has become an object.

This may be one of the more consequential changes AI is bringing to knowledge work. Much of the discussion about artificial intelligence focuses on whether the systems are intelligent enough, whether they hallucinate, whether they will replace particular jobs, or how much productivity they create. A subtler transformation is happening at the level of human cognition.

AI allows us to move upward through layers of abstraction at remarkable speed. And every layer we ascend changes what it means to know what we are doing.

Consider programming. Traditionally, a programmer might start with an intention, translate it into an architecture, break the architecture into components, and eventually write the code. Working with an AI coding system changes that sequence. The programmer can remain at the level of intention for much longer.

“Build a service that does this.”

“Add authentication.”

“Write tests for these cases.”

“Find the bug.”

“Refactor this.”

Eventually, the code begins to look less like something the programmer wrote and more like something the programmer commissioned.

That can be enormously powerful. It also creates a new epistemic problem: How do you know what you have?

You can ask the AI.

Does the code correctly handle concurrent requests? Are these tests sufficient? Is there an unhandled edge case here? Could this architecture produce a race condition?

But now the same system that helped construct the object is helping you inspect the object. So you climb another level.

Instead of inspecting the code yourself, you inspect the AI’s account of the code.

Then another problem appears: How do you know whether you asked the right questions?

Perhaps you never thought to ask about an obscure failure mode. Perhaps a design assumption that seems harmless now becomes catastrophic when the system scales. Perhaps the AI found twelve weaknesses but missed the thirteenth, which happens to be the one you care about.

So you climb again.

Now the task becomes eliciting your own criteria. What properties actually matter to me? What am I assuming? What would make this system unacceptable? What questions would reveal whether those properties hold?

AI can help with this too. You can ask it to interview you, expose your assumptions, construct adversarial tests, or propose evaluation criteria.

The result is a strange cognitive escalation. Each time execution becomes easier, the human role moves upward into abstraction.

And abstraction is not free.

At higher levels, more of the system has to remain mentally available at once. You are thinking about architecture, constraints, goals, interactions, edge cases, and possible futures simultaneously. Individual implementation details disappear, but the number of relationships you must track can increase.

There is an abstraction tax.

It often manifests as concentration.

The stereotype of contemporary digital life is fractured attention: notifications, short videos, endless tabs, people supposedly unable to focus for longer than thirty seconds. AI-assisted work can produce almost the opposite experience.

You sit down in the morning with a problem. The AI generates something. You inspect the result. While it works on the next task, you think about the next conceptual problem. You revise the specification. Another result arrives. You discover a new issue. You move up a level and reconsider the architecture.

Lunch quietly disappears.

Hours pass.

The work has the phenomenology of deep focus. You are not switching among unrelated tasks. In fact, switching tasks becomes almost impossible because the working representation of the problem is so large. To answer an unrelated email would mean unloading part of the mental structure you have spent hours assembling.

The AI has made you intensely monotask.

Paradoxically, the delays in current AI systems can help. When a difficult operation takes several minutes, that latency creates thinking time. You reconsider a decision, imagine a failure case, or formulate the next instruction. A considerably faster system could create a new problem: the machine might begin producing decisions faster than the human can form judgments about them.

At that point, the bottleneck is no longer execution.

It is thought.

This arrangement can feel extraordinarily productive. By the end of the day, you may have done what previously would have required several people or several days.

Then something stranger happens.

You forget it.

Not immediately. While you are immersed in the task, the whole structure feels vividly present. You know why every decision exists. You understand how one component relates to another. The project seems almost physically present in working memory.

But a few days later, much of that understanding has vanished.

Returning to the project means reconstructing it. You read documents, interrogate the repository, ask the AI what was decided, inspect commit histories, and gradually reload the system into your head.

This creates a curious inversion of ordinary expertise.

Traditionally, effort and memory were often coupled. The tedious work of constructing something helped encode it. Writing the function meant encountering its constraints. Debugging it meant learning its failure modes. Rewriting it created familiarity with its structure.

AI can separate production from encoding.

You can produce more while personally retaining less of the production process.

The output survives. The cognitive residue does not necessarily survive with it.

This matters because expertise is partly the accumulation of residue. A programmer does not merely possess code. They develop intuitions about systems because thousands of earlier implementation details have left traces. A traveler who repeatedly plans complex journeys develops an internal model of routes, timetables, and geography. A researcher who repeatedly performs literature searches develops instincts about where evidence is likely to be found.

Delegate the execution often enough and some of those traces may never form.

This is where convenience turns into dependence.

Imagine planning a trip. Instead of learning the rail network, comparing timetables, and reasoning about connections, you ask an AI for the best route. It checks everything and gives you an answer.

This is obviously useful.

But after doing this repeatedly, the prospect of planning the trip manually can start to feel absurdly laborious. If the AI service is unavailable, you may delay the task rather than perform it yourself.

The same phenomenon can appear in programming, writing, analysis, administration, or research. The capability has technically not disappeared. You could still do the task manually. But its subjective cost has increased because your baseline has changed.

Once you become accustomed to cognitive machinery, unaided cognition begins to feel inefficient.

That is a different kind of dependency from simply forgetting how to perform a procedure. It is a dependency created by relative friction.

Walking feels slow after you have owned a bicycle.

Manual calculation feels tedious after you have used a spreadsheet.

And inspecting 20,000 lines of code feels increasingly irrational after you have become accustomed to asking an AI, “Tell me what matters here.”

The temptation is to conclude that the solution is simply to use AI less. But that misses something interesting about the new division of labor.

The higher level work is real work.

Formulating goals, selecting abstractions, deciding what matters, identifying hidden assumptions, and testing whether an artifact satisfies an intention are not inferior substitutes for implementation. In many cases they are exactly the activities experts have always tried to spend more time doing.

The difficulty is that we do not yet have mature practices for preserving understanding while operating at those levels.

The central question may therefore be less “How do we avoid becoming dependent on AI?” and more “What kinds of cognition should remain ours?”

Perhaps some implementation details can safely disappear. Perhaps others need periodic direct inspection. Perhaps AI-assisted work needs deliberate moments of reconstruction: explain the architecture without consulting the model; identify the three most dangerous assumptions; write down why the major decisions were made; predict what will break before asking the AI.

Such practices introduce friction deliberately.

That sounds inefficient. It may also be how learning survives.

Because the oddest possibility is that AI could create workers who are simultaneously more capable and less self-sufficient: able to produce systems of unprecedented complexity, yet increasingly unable to reproduce the chain of reasoning that produced them.

They may work harder cognitively, not less. They may concentrate for longer periods. They may operate at levels of abstraction previously reserved for senior teams.

And at the end of the day they may close the laptop, exhausted from eight hours of intense thought, having accomplished an extraordinary amount.

A week later, they may open the project and ask the machine:

Remind me what we built.

---
[[back]](README.md)
