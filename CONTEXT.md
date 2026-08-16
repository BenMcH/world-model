# World Model

A personal system for maintaining a canonical, revisable representation of the owner's understanding of their world, shared with AI agents.

## Language

**World Model**:
The owner's general-purpose, canonical representation of entities, relationships, beliefs, evidence, decisions, and their provenance.
_Avoid_: Memory system, knowledge graph (when referring to the whole system)

**Accepted Understanding**:
The Owner's currently accepted account of some part of the world, represented by explicit versioned Acceptance Records. It is revisable and grounded in Claims, Evidence, Decisions, and provenance rather than asserted as immutable objective fact.
_Avoid_: Truth, fact

**Acceptance Record**:
An explicit, versioned Owner acceptance of an account of the world, pointing to the Claims and Decisions that support it.
_Avoid_: Implicit current view, fact

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
A revisable assertion about the world with required canonical text and optional structured subject, predicate, object, and qualifiers. Its standing is supported or challenged by Evidence and reasoning. A relationship is expressed as a structured Claim.
_Avoid_: Decision

**Canonical Entity**:
A permanently identified, individually referable subject in the World Model: a real-world thing, abstract concept, event, plan, account, or document. It may carry zero or more revisable, provenance-bearing classifications.
_Avoid_: Mutable identity, merged entity

**Alias**:
A human-oriented search or reference name whose append-only bindings resolve to a Canonical Entity. An Alias may be reassigned over time (for example, “my car”); a recorded reference resolves to the target canonical identifier, while the Alias and its binding history remain available as provenance.
_Avoid_: Canonical identifier

**Evidence**:
A citable recorded extraction or observation, optionally locating a precise span in an immutable Source Artifact, that bears on a Claim.

**Source Artifact**:
The preserved text or external reference from which Evidence is derived. Initial support is text, including text that contains a URL.

**Decision**:
A recorded choice among alternatives, including its rationale and consequences. A Decision may concern Claims but is distinct from them.

**Supersession**:
An append-only relationship by which a later record replaces an earlier record without erasing it. It is distinct from a challenge, which records competing epistemic standing. It also records changes to an Alias binding rather than changing prior references.
_Avoid_: Edit, deletion

**Same-as Link**:
An append-only, discoverable relationship recording that two permanently identified Canonical Entities are understood to refer to the same subject. It does not merge or delete either entity or rewrite their histories.
_Avoid_: Merge

**Derivation**:
A typed, reviewable relationship from a Proposal or other derived record to its input Claims, Evidence, Assumptions, and Decisions, accompanied by concise rationale.
_Avoid_: Chain-of-thought
