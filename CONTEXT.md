# World Model

A personal system for maintaining a canonical, revisable representation of the owner's understanding of their world, shared with AI agents.

## Language

**World Model**:
The owner's general-purpose, canonical representation of entities, relationships, beliefs, evidence, decisions, and their provenance.
_Avoid_: Memory system, knowledge graph (when referring to the whole system)

**Accepted Understanding**:
The owner's currently accepted account of some part of the world. It is revisable and is grounded in beliefs, evidence, and provenance rather than asserted as immutable objective fact.
_Avoid_: Truth, fact

**Owner**:
The single human authority who controls the World Model and its Accepted Understanding.
_Avoid_: Tenant, user (when authority is relevant)

**Direct Statement**:
Information expressly supplied by the Owner. It has stronger epistemic standing than an Assumption but is still revisable.
_Avoid_: Fact (when infallibility is implied)

**Assumption**:
A provisional inference not directly stated by the Owner and not yet accepted as understanding. It is weaker than a Direct Statement.
_Avoid_: Fact, truth

**Proposal**:
An agent-authored candidate addition or change to the World Model awaiting Owner review or policy-based acceptance.
_Avoid_: Accepted Understanding

**Claim**:
A revisable assertion about the world whose standing is supported or challenged by Evidence and reasoning.
_Avoid_: Decision

**Evidence**:
A source artifact or recorded observation that bears on a Claim.

**Source Artifact**:
The preserved text or external reference from which Evidence is derived. Initial support is text, including text that contains a URL.

**Decision**:
A recorded choice among alternatives, including its rationale and consequences. A Decision may concern Claims but is distinct from them.

**Supersession**:
An append-only relationship by which later Accepted Understanding replaces an earlier understanding without erasing it.
_Avoid_: Edit, deletion
