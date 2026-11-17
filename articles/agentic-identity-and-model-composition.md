# Agentic Identity and Model Composition

Sales, finance, and service access can each reach a valid conclusion about the same order. Sales finds that the customer qualifies for the offer. Finance approves up to $5,000 in credit. The service access team authorizes a particular account to use a restricted service. Each conclusion belongs to a model of the order with its own terms, evidence, and rules. Fulfillment needs a model that brings those conclusions into relation so it can determine whether the order can proceed.

That is the sense in which agent collaboration is model composition. Each participant brings a model of part of the situation. Collaboration builds a united model by connecting those parts and deriving conclusions about the situation as a whole.

## Agentic identity and model identity

**Agentic identity** identifies the actor that contributes a claim or takes an action. It lets collaborators establish which agent acted, whom it represented at the time, and what responsibilities or delegated authority applied. An agent representing finance might continue under the same identity after its underlying language model changes. A change in its delegation might alter which decisions it can issue while leaving earlier decisions attributable to the same actor.

**Model identity** identifies the representation the agent used to interpret the situation. Here, a model is an explicit account of a domain, including its concepts, relationships, evidence, assumptions, and rules. A finance model might define credit approval in terms of a customer, order, amount, currency, policy, and expiration. The model's identity and version tell a collaborator which definition was in force when a claim was made.

The underlying language model is a third identity that can matter when reproducing a result. Two agents can use the same language model while applying different domain models. Two agents can also use different language models while sharing the same domain model. A trace of their work can record the contributing agent, the version of the domain model that gave the claim its meaning, and the language model that helped produce it.

## How collaboration composes models

Composition starts by establishing which parts of the domain models refer to the same thing. The finance record and the service access record may use different identifiers. To combine them, fulfillment needs a supported relationship between the customer, the account, and the order. It also needs to know what each claim contributes to the decision.

A bridge between the finance and fulfillment models might say that a valid credit approval satisfies the credit prerequisite when it covers the same customer and order, in the right currency, for at least the amount required. A separate bridge connects service authorization to the access prerequisite. Each bridge carries its conditions into the composed model, along with references to the claims that support it.

Suppose the order requires $4,800 and finance has approved $5,000, but the service access decision is missing. The united model can express a new conclusion: the order meets the credit prerequisite and is waiting on access authorization. That conclusion follows from the finance claim, the fulfillment model's prerequisites, and the absence of a matching access authorization in the available record. If the order rises to $5,200, the credit prerequisite must be evaluated again. If the access record names an account that cannot be tied to the customer, that relationship remains unresolved in the united model.

## What fusion preserves

The fusion is scoped to a question. For this order, the united model includes the parts of sales, finance, and service access that bear on readiness, together with their relationships and the conclusions they support. Another question about the same customer could compose a different model from the same sources.

The source models retain their identities within the composition. A reviewer can follow a conclusion back to the original claim, the model version that defined it, the agent that contributed it, and the bridge that made it relevant. If a source claim changes, that trace shows which conclusions need to be reconsidered. If agents disagree about a shared fact, the united model can represent the disagreement and identify which conclusions depend on resolving it.

A composed model can establish that the prerequisites for an action are satisfied under stated conditions. Execution still depends on verifying the relevant delegation and checking what the runtime permits. Carrying those distinctions through the fusion lets collaborators share a model of the situation while keeping responsibility for its claims and decisions visible.
