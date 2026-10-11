# Polymodality

**Give agents identity. Preserve meaning across contexts.**

## The bigger idea

A person is a customer, a colleague, an account owner, a community member — all at once. A document is evidence, an obligation, a sensitive resource. Every perspective reveals something real, and every perspective is incomplete.

Polymodality is the discipline of holding those dimensions separately and fusing them on purpose: make each perspective explicit, name the translations between them, and never collapse differences that matter.

It's language-agnostic and environment-agnostic — a way of modeling the world before it's a way of building software.

## The problem

Three agents work one customer request. Sales says "qualified." Finance says "approved." Security says "authorized."

The fulfillment agent receives the word "approved" and acts. But approved for *what* — credit? A discount? Access to a restricted service? By whom, under which rules, for how long?

Every agent understood its own task. The handoff still lost the distinctions that made each conclusion meaningful.

## What this is

Polymodality is an architectural approach for multi-agent systems: give agents explicit identities, keep meaning attached to context, and make the translation between different perspectives visible and inspectable.

In practice that means:

- **Identity** — an agent is distinguishable from the person, department, or service it represents. Delegation has a source, scope, and lifecycle.
- **Context** — a claim carries what it means, where it applies, and what evidence supports it.
- **Governance** — who can decide what, and whose authority backs it, is explicit — and verified, not assumed.
- **Translation** — when two domains meet, the mapping between their concepts is written down, with its assumptions and limits.

## Try it now

No code yet — today's artifact is a design pack. Feed it to a frontier AI and it becomes an architect for your agent team, designing agents under eight explicit commitments.

1. Open [agentic-polymodality/ai-guidance](https://github.com/polymodality/agentic-polymodality/tree/main/ai-guidance)
2. Paste `START_HERE.md`, `VISION.md`, and `GUIDING_AI.md` into your AI
3. Ask it to design the agents for your use case

Includes agent spec templates, a handoff protocol, a worked customer-order example, and acceptance criteria.

## Repositories

- **polymodality** (this repo) — the general vision and framework.
- **[agentic-polymodality](https://github.com/polymodality/agentic-polymodality)** — the flagship application: the manifesto, the design pack, the worked examples.

## Status

A proposal for public discussion, not a finished platform. The manifesto and design methodology exist today; a reference implementation, validated specification, and runnable demonstration are the roadmap.

We intend to earn confidence the hard way: reproducible examples, measured comparisons against simpler approaches, and published counterexamples where this doesn't pay off.

## Participate

Open an issue with:

- A use case where several perspectives share one entity
- A handoff where meaning, scope, or authority went ambiguous
- A proposed schema, definition, or translation rule
- A counterexample, or a simpler architecture that solves the same problem

## License

Apache License-2.0. See [LICENSE](LICENSE).

---

*Let identity endure. Let context travel. Let collaboration preserve meaning.*
