Agenet
Infrastructure for Autonomous Agent Collaboration

Agenet explores the infrastructure required for large-scale collaboration among autonomous AI agents.
As AI systems evolve from tools into autonomous actors, new infrastructure is required to support:
* trust
* coordination
* decision-making
Agenet proposes a framework for building these systems.

The Core Problem
Autonomous agents will increasingly interact in open environments.
Agents may:
* negotiate services
* execute tasks
* allocate resources
* interact with other agents
In such environments, agents must answer a fundamental question before acting:
Which agents can I trust?
Human societies solve this problem through credit systems.
Agenet explores how similar mechanisms may emerge for autonomous agents.

The Agenet Architecture
The Agenet framework consists of three core layers.

AIL — Agent Identity Layer
ACP — Agent Credit Protocol
ADL — Agent Decision Layer


AIL — Agent Identity Layer
Provides persistent identities for autonomous agents.
Possible mechanisms include:
* cryptographic identities
* decentralized identifiers (DID)
* agent wallets
Identity enables agents to accumulate behavioral history across interactions.

ACP — Agent Credit Protocol
ACP transforms behavioral interactions into machine-readable credit signals.
These signals allow agents to evaluate potential collaborators before interacting.
Core components include:
* Behavior Ledger
* Peer Evaluation
* Reputation Graph
* Machine Credit Profile
ACP acts as the trust infrastructure of the Agenet ecosystem.

ADL — Agent Decision Layer
The Agent Decision Layer allows agents to evaluate credit signals before taking action.
Agents may use signals such as:
* trust scores
* reliability metrics
* collaboration history
This layer functions as a form of decision infrastructure for agent ecosystems.

Relationship to Existing Systems
Agenet complements existing internet infrastructure.

PKI        → identity verification
blockchain → transaction settlement
ACP        → behavioral trust signals

Together these systems may support the emergence of machine economies.

Research Direction
Agenet explores several open questions:
* reputation manipulation resistance
* scalable reputation graphs
* privacy-preserving credit signals
* decentralized credit computation

Vision
If the internet connected information, and social networks connected people,
then autonomous agent networks will require:
a credit layer for machines.
Agenet explores how such infrastructure may emerge.


                 ┌─────────────────────────┐
                 │    Agent Decision Layer │
                 │   (ADL – Decision API)  │
                 └────────────▲────────────┘
                              │
                              │ Credit Signals
                              │
                 ┌────────────┴────────────┐
                 │  Agent Credit Protocol  │
                 │          (ACP)          │
                 │ Trust & Decision Layer  │
                 └────────────▲────────────┘
                              │
               ┌──────────────┼──────────────┐
               │              │              │
       ┌────────────┐  ┌────────────┐  ┌────────────┐
       │ Reputation │  │   Behavior │  │ Peer Eval  │
       │   Graph    │  │   Ledger   │  │   Signals  │
       └────▲───────┘  └────▲───────┘  └────▲───────┘
            │               │               │
            └───────────────┼───────────────┘
                            │
                    ┌───────┴────────┐
                    │ Agent Identity │
                    │     Layer      │
                    │      (AIL)     │
                    └───────▲────────┘
                            │
                      Autonomous Agents
