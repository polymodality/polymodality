# Announcing Agentic Polymodality

I'm launching the **agentic-polymodality** project on GitHub:

https://github.com/polymodality/agentic-polymodality

## The problem nobody talks about

Three agents work on one customer request. Sales says the customer is *qualified*. Finance says *approved*. Security says *authorized*.

The fulfillment agent receives the word "approved" and acts. But approved for *what* — credit? A discount? Access to a restricted service? By whom, under which rules, for how long?

Every agent understood its own task. The handoff still lost the distinctions that made each conclusion meaningful.

We're building agent teams faster than we're building the infrastructure that lets them understand each other.

## The vision

Agentic polymodality is an architectural approach for multi-agent systems:

- **Give agents identity.** An agent is distinguishable from the person, department, or service it represents. Delegation has a source, scope, and lifecycle.
- **Keep meaning attached to context.** A claim carries what it means, where it applies, and what evidence supports it — not just a bare "approved."
- **Keep the dimensions separate.** Identity, semantics, context, governance, and cybersecurity answer different questions. Fuse them deliberately; never collapse them by accident.
- **Make translation explicit.** When two domains meet, the mapping between their concepts is written down, with its assumptions and limits.

One entity, many dimensions — fuse them without collapsing them.

## What's in the repo

**For humans:** a manifesto and a white paper laying out the motivation, the dimensions, and the design commitments.

**For the machines:** this is the part I'm most excited about. The repo ships an `ai-guidance` design pack — instructions you paste into a frontier AI, turning it into what I think of as an *Agent Builder*: an architect that generates agentic clusters for your use case.

Feed it your scenario, and it designs the agents — specs, modality bindings, handoff envelopes, bridges between domains, evaluation criteria — under eight explicit commitments, including "authority requires verification, not assertion."

No framework lock-in. No runtime. A design discipline that any capable AI can apply.

Try it: open `ai-guidance/START_HERE.md`, paste it with `VISION.md` and `GUIDING_AI.md` into your favorite model, and ask it to design the agents for a problem you actually have.

## Honest status

This is a proposal for public discussion, not a finished platform. The manifesto, white paper, and design pack exist today; a reference implementation and validated spec are the roadmap.

I intend to earn confidence the hard way: reproducible examples, measured comparisons against simpler approaches, and published counterexamples where this doesn't pay off.

If you have a handoff where meaning got lost, a use case where several perspectives share one entity, or a simpler architecture that solves the same problem — open an issue. Bring the counterexamples too.

Let identity endure. Let context travel. Let collaboration preserve meaning.

#AI #MultiAgentSystems #AgenticAI #SoftwareArchitecture #OpenSource
