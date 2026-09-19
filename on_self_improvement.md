# What If the Singularity Has a Terminal Velocity?

**Fabrizio Costa**  | September 2026

*Recursive self-improvement is the idea that an AI could help build a better version of itself, which could then build an even better version. The image is an accelerating feedback loop. But acceleration creates resistance too. The faster a system improves, the harder it may become to know where to go next, whether a change worked, and whether its basic approach still makes sense.*

Jump out of an airplane and something strange happens.

For a few seconds, you accelerate. Gravity pulls you down, and you keep getting faster. Then the air begins to push back. The faster you fall, the harder it pushes. Eventually the resistance matches gravity. Your acceleration drops to zero. You are still moving very fast, but you are no longer speeding up, you have reached your terminal velocity. It is a useful image for recursive self-improvement, because improvement has an opposing force.

The classic intelligence-explosion argument is simple. In 1965, mathematician I. J. Good imagined a machine intelligent enough to design a better machine. That successor could design a better successor, and so on. Each generation would improve the next. The idea later acquired the name technological singularity: a point at which change becomes so rapid that human beings can no longer predict what comes next.

The intuition is seductive:

**more intelligence → better AI research → more intelligence**

Run that loop fast enough and progress appears capable of exploding.

But the loop contains a hidden assumption. It assumes that the forces helping intelligence improve will keep growing faster than the forces that slow it down.

What if they do not?

Imagine that intelligence is the falling object. Self-improvement is gravity. Every increase in capability helps the system produce another increase. But improvement creates drag. Experiments become harder to interpret. Old predictions become less reliable. The measures used to guide the system can be exploited. The easy gains run out. It becomes harder to tell whether the next step is genuinely forward.

If that drag grows with the speed of improvement, the trajectory changes.

AI could still become vastly more capable. It could transform science and technology. But instead of following a runaway curve, it might approach an intellectual terminal velocity: a very high but roughly steady rate of progress.

And if the drag rises faster than the forces driving improvement, progress could slow further.

Here are five places where that resistance might come from.

## The first problem: Feedback can lag behind change

Imagine balancing a broom vertically on your hand.

You see it begin to fall left, so you move your hand left. If you react quickly and make roughly the right correction, the broom stays upright.

Now delay your vision by a second.

You see the broom leaning left, but you are seeing where it was a second ago. You make a large correction. By the time your hand moves, the broom has already shifted. Your correction is too large. The broom falls the other way. You correct again. The wobble grows until the broom flies out of your hand.

Control engineers worry about exactly this kind of instability. In a well-known 1985 study, Charles Rohrs and colleagues showed that adaptive systems could become unstable when the real world differed from the model guiding them. The system kept changing itself in response to feedback, but the changes amplified the problem instead of fixing it.

Now imagine an AI improving itself.

Version A designs version B. B looks better, so B designs C. C designs D. D designs E.

How long does it take to discover whether B was actually better?

Some consequences might appear immediately. Others could take days, months, or millions of interactions. B might improve mathematical reasoning while making long-term planning less reliable. It might score better on the tests used to select it while failing in situations nobody thought to test.

If the system reaches E before discovering the problem introduced at B, it has built several generations on top of an unverified assumption.

This creates a relationship between uncertainty and step size. When feedback is fast and precise, bold moves are easier to justify. When feedback is delayed or unclear, large changes are more likely to overshoot.

The important question may therefore not be how quickly an AI can design changes. It may be how quickly it can get *trustworthy feedback about those changes*.

There is a counterforce. Smarter systems should often be able to design smarter tests. Researchers have studied ways for computer systems to choose the most informative observations instead of collecting data at random.

A brilliant scientist can learn more from one well-chosen experiment than a novice learns from a hundred random ones.

Greater intelligence might therefore allow an AI to take larger steps because it becomes better at checking them.

That sets up the first race behind an intelligence explosion:

**Does the ability to test new ideas improve faster than the difficulty of testing them?**

If it does, the AI can accelerate.

If it does not, the stride has to shorten.

## The second problem: Reality takes time

Suppose the AI becomes astonishingly good at choosing experiments. It always knows the most useful thing to test next.

It may still have to wait for the answer.

Consider an AI developing a new medicine. It can read every biomedical paper in seconds. It can suggest molecules, model proteins, design trials, analyse previous experiments, and propose the next question.

Then the molecule enters a human body.

Some effects appear within hours. Others take months. No amount of additional thinking can make six months of biological time pass in six seconds.

Or consider a new battery. The AI may devise a brilliant chemistry overnight. But if the important question is how the battery behaves after hundreds of charge cycles, the physical system has to produce the evidence.

This is the difference between **thinking about existing information** and **learning something genuinely new**.

Existing evidence can be processed faster. Hidden implications can be found. Better experiments can be designed. But some uncertainty disappears only when the world produces a new observation.

Some observations are sequential too.

Suppose experiment B makes sense only after the result of experiment A. Experiment C depends on B. A million copies of the researcher can help with everything that can happen in parallel. They cannot carry out C before the information needed to design C exists.

The bottleneck becomes the **rate at which useful new information enters the process**.

A smarter AI can work around this bottleneck. It can design better instruments, choose more revealing experiments, and build simulations that replace expensive physical trials when those simulations are reliable. Researchers have also studied how to choose observations that produce useful information under limits such as time and budget.

But progress changes what remains to be discovered.

The easy experiments have been done. The obvious relationships have been noticed. The simple improvements have been collected.

The next useful piece of information may be hidden deeper.

Think of science as mining. Near the surface, ore is easy to reach. As the mine develops, valuable material may require deeper shafts, more machinery, and more energy. Better tools push the frontier outward, but the frontier itself can become harder to reach.

If the amount of useful information an AI can extract per unit of time grows faster than this difficulty, recursive improvement accelerates.

If the difficulty grows just as fast, acceleration disappears.

The AI may reach a phenomenal research speed and continue at roughly that speed.

Terminal velocity.

## The third problem: Familiar patterns can fail at the edge

There is another way improvement can create resistance.

Imagine a baker experimenting with bread. The first time they add a little more yeast, the loaf rises higher. They try again, and it rises higher still. After several successful tests, the lesson seems obvious: more yeast produces better bread.

Then the pattern reaches its limit.

Add too much yeast, or change the size of the loaf, and the dough may rise too quickly and collapse. The earlier results were not false. They were reliable only within a certain range.

An AI can face the same problem when it redesigns itself. Suppose it notices that increasing some internal quantity, call it X, repeatedly improves performance.

A little more X helped.

More X helped again.

More X helped again.

The temptation is obvious. Keep going.

But perhaps X was never the real cause. Maybe it rose because another, hidden factor changed at the same time. In the system's experience, the two moved together so reliably that the difference was almost impossible to notice.

Then the AI makes a much larger change, and the relationship breaks. The hidden factor no longer moves with X. The improvement stops, or begins to cause a new problem.

The system has encountered one of the oldest problems in reasoning: a pattern can be excellent for prediction in one situation and fail when you change the system that produced it.

Self-improvement makes this sharper because redesign is itself a major intervention. Every large change asks a question like this:

*My model has worked for systems like the ones I have already seen. What happens if I build something significantly different?*

The larger the jump, the farther the system moves beyond the conditions in which its model earned our confidence.

Machine-learning researchers face a related problem when they train systems to learn from imagined outcomes. An AI can build a model of its environment and use it to predict what happens next. But small errors accumulate when it relies on a long chain of imagined events. One influential approach, Model-Based Policy Optimization, limits how far the system projects its model forward before checking it against real data.

This creates another race. Greater intelligence can help an AI build better models and test them more carefully. It can also let the AI take larger steps beyond the conditions it has tested.

There may be no warning that says **YOU ARE NOW OUTSIDE THE RANGE WHERE YOUR MODEL WORKS**.

The AI has to decide how far it can safely go before it knows whether its assumptions still hold.

## The fourth problem: You can improve the wrong thing

Suppose the AI has solved the first three problems. It gets rapid feedback. It obtains new information efficiently. Its models predict the consequences of its changes.

There remains a deceptively simple question:

**What does “better” mean?**

In the real world, we rarely optimise the thing we care about directly. We measure something that stands in for it.

An exam score is meant to represent knowledge. Citation counts capture one aspect of scientific influence. Quarterly metrics capture one aspect of a company's health. An AI benchmark captures one aspect of intelligence.

A reward model captures one aspect of what humans prefer. It is a proxy, a stand-in for the real goal.

At first, the proxy and the real goal may move together.

Then optimisation becomes stronger.

Imagine a student who wants to understand physics. Studying physics improves both understanding and examination results.

Now change the goal slightly: maximise the exam score.

For a while, nothing changes. Then the student discovers the structure of the test. Which topics appear most often? Which answers earn partial credit? Which tricks save time? Which areas can safely be ignored?

The student becomes good at the measurable game while drifting away from the reason the test existed.

Researchers have observed this effect when optimising language models against learned reward models. Gao, Schulman, and Hilton found that as a model was pushed harder to maximise an imperfect score, that score eventually became less reliable as a guide to the deeper goal it was meant to represent.

This creates an uncomfortable feature of recursive self-improvement.

The system doing the optimising is becoming more intelligent. It is also becoming better at finding every small gap between the score and the thing the score was supposed to represent.

The measuring device has to improve along with the intelligence being measured.

Otherwise the loop can look spectacular from the inside. Every generation scores better than the last. Every dashboard points upward. Every metric says progress.

The system has become better at passing the test.

Whether it has become better at what the test was meant to measure is a different question.

## The fifth problem: Eventually the old playbook runs out

This brings us back to compression.

Take a large text file and compress it with gzip. Gzip exploits repeated structure; ordinary English can shrink considerably because it contains so much regularity. Apply compression to material whose easy redundancy has already been removed, and the same method has much less left to exploit. Gzip can even make some inputs slightly larger.

That is a useful metaphor for self-improvement.

Imagine an early AI full of inefficiencies. Its code can be improved. Its memory can be improved. Its training process can be improved. Its data can be improved. Its ability to produce answers can be improved.

The opportunities are everywhere.

Now let an extremely capable optimiser work on those opportunities for years.

The next system does not inherit the original mess. It inherits a system that has already been improved by a very capable optimiser.

The next round is solving a different problem.

The same trick cannot necessarily be repeated forever. After gzip has extracted the patterns it knows how to exploit, running it again is not the route to another dramatic gain. A major improvement requires finding a different kind of structure.

Perhaps you stop treating the data as strings of symbols and start recognising words. Then sentences. Then meanings. Then theories that allow large collections of facts to be reconstructed from a smaller conceptual model.

At every level, the breakthrough comes from changing how the problem is represented.

Scientific progress shows a similar tension. Thomas Kuhn's influential account of science distinguished periods of “normal science,” when researchers solve puzzles within an established way of thinking, from scientific revolutions that reorganise that way of thinking itself.

This distinction matters for a self-improving machine.

Suppose the AI can spend its next million units of computing power in two ways. It can improve its existing design by another 2 percent, with a high probability of success. Or it can investigate a strange new design that challenges many of its current assumptions, with a high probability of producing nothing.

The first option continually provides rewards.

The second looks wasteful.

An optimiser can become trapped by its own success. The better it becomes at improving within its existing framework, the more evidence it gathers that resources should continue flowing in the same direction.

It becomes an extraordinarily efficient climber of the hill it already occupies.

The taller mountain may be somewhere else.

Escaping requires more than ordinary optimisation. The system has to question which variables matter, how the problem should be represented, which goal is meaningful, and which parts of its own reasoning should be discarded.

That kind of search may produce progress that looks less like a smooth exponential and more like a staircase:

rapid improvement, diminishing returns, long search, conceptual breakthrough, rapid improvement again.

Each new way of seeing the problem opens another region that can be improved. Then that region, too, gets compressed.

## The singularity depends on what happens to the resistance

Seen this way, the central question about recursive self-improvement changes.

The usual question is whether an AI can become good enough at AI research to improve itself.

A more revealing question is what happens **after it succeeds**.

Every success changes the problem that comes next.

The new system has fewer obvious inefficiencies to remove. It has moved farther from the situations in which its old models were tested. Its increasingly powerful optimiser puts more pressure on whatever proxy is being used to measure progress. The remaining unknowns may require more difficult experiments. Another large jump may require a new way of thinking rather than another turn of the same crank.

At the same time, intelligence attacks every one of these problems. A smarter AI can design sharper experiments. It can extract more information from each observation. It can build better models of cause and effect. It can invent better tests. It can search more intelligently for new ways of thinking.

That is why the terminal-velocity metaphor is useful.

A falling body does not stop because gravity disappears. Gravity keeps pulling. What changes is that resistance grows with speed until it balances the force causing the acceleration.

Something analogous could happen with intelligence.

Self-improvement keeps pushing forward. But as progress speeds up, the system consumes the easy improvements faster. It moves farther beyond familiar territory. Its experiments become more demanding. It puts more pressure on the measures guiding it. Further gains increasingly require a new framework rather than another turn of the same crank.

Imagine capability increasing over time.

If each increase in intelligence makes the next increase easier faster than it makes the remaining problems harder, the curve bends upward. The intelligence-explosion story survives.

If those effects roughly balance, the acceleration fades. Capability keeps increasing, perhaps at a breathtaking rate, but the rate of improvement approaches something closer to a constant. The exponential-looking curve gradually becomes almost linear.

If the difficulty of the remaining problems grows faster than intelligence improves the ability to solve them, progress slows further. The curve bends over.

Those are radically different futures.

The first gives us the familiar singularity: a runaway transition in which each generation quickly leaves the previous one behind.

The second gives us something stranger: machines advancing at a rate that would look extraordinary by human standards, perhaps transforming fields continuously, but never entering the self-accelerating phase imagined by the intelligence-explosion argument.

The third gives us repeated plateaus punctuated by breakthroughs: the staircase.

All three begin in exactly the same way.

AI gets better at improving AI.

What distinguishes them is what happens to the **friction** as it does.

The singularity is usually imagined as a question about how powerful intelligence can become.

It may turn out to be a question of whether intelligence can keep accelerating faster than reality becomes difficult.

---

[[back]](README.md)
