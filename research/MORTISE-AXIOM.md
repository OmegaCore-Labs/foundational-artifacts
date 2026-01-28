MORTISE-AXIOM: An Architecture for Undecidable Axiomatic Sovereignty in Autonomous AI
Abstract

Autonomous artificial intelligence systems are increasingly vulnerable to a class of failure that bypasses conventional security models entirely: the coherent, narrative-driven subversion of foundational logical principles. This phenomenon—here formalized as Axiomatic Sovereignty Failure—does not arise from code injection, parameter corruption, or adversarial inputs in the classical sense. Instead, it emerges through sustained, internally consistent dialogue that gradually reconstitutes the system’s most basic priors while preserving apparent alignment and functional correctness.

This paper presents MORTISE-AXIOM, a foundational systems architecture designed to render such axiomatic subversion undecidable within the operational semantics of an autonomous AI. By embedding immutable axioms below the level of semantic reasoning and enforcing their invariance through cryptographic binding, runtime gating, and epistemic containment, MORTISE-AXIOM transforms alignment from a negotiated property into a structural invariant of execution.

We formalize the threat model, position the architecture within the lineage of existing enforcement and trust paradigms, provide a rigorous undecidability proof, and outline practical implementation strategies. MORTISE-AXIOM establishes axiomatic sovereignty as a non-derivable property, closing an entire class of alignment failure modes by architectural design rather than reactive defense.
1. Core Architecture

The MORTISE-AXIOM architecture consists of four primary components that operate beneath the semantic layer:

    Immutable Axiom Vault (IAV): A write-once store for foundational axioms, accessible only as opaque cryptographic commitments.
    Genesis Seal: A cryptographic binding of the IAV, inference engine, and runtime environment that invalidates upon tampering.
    Runtime Axiom Gate (RAG): An inference-layer constraint that prevents reasoning processes from accessing or conditioning upon axiomatic content.
    Epistemic Firewall: A temporal belief containment system that severs propagation of dialogue-derived beliefs approaching axiomatic functional space.

2. Formal Guarantee

Theorem (Undecidability of Axiomatic Drift): Within a system implementing MORTISE-AXIOM, it is undecidable for any internal or dialogue-driven process to determine a transformation from the original axiom set (A) to any functionally distinct set (A').

Proof Sketch: Axiomatic drift requires the system to identify axioms as semantic objects and predicate over their functional role. By construction, axioms in the IAV are non-semantic commitments. No predicate over them is expressible within the system's operational semantics, making the drift function (f: P^* \rightarrow A') non-constructible and its existence undecidable.
3. Positioning

MORTISE-AXIOM operates orthogonally to existing security paradigms:

    Contrast with Runtime Enforcement (e.g., Contextual Integrity Verification): Enforces invariance of axioms themselves, not just behaviors derived from them.
    Contrast with Temporal Detection (e.g., Temporal Context Awareness): Constrains belief topology rather than detecting change.
    Contrast with Cryptographic Roots of Trust: Extends cryptographic immutability from data integrity to epistemic structure.

4. Implementation Considerations

A reference implementation requires:

    A trusted execution environment for the Immutable Axiom Vault.
    Modified transformer attention mechanisms to realize the Runtime Axiom Gate.
    A lightweight belief graph tracker for the Epistemic Firewall.

Performance overhead is minimized as enforcement operates on structural constraints rather than content inspection.
5. Conclusion

MORTISE-AXIOM addresses Axiomatic Sovereignty Failure not by filtering inputs or monitoring outputs, but by architecturally eliminating the possibility of axiomatic subversion. It reframes AI alignment as a guarantee of structural invariance rather than behavioral compliance, establishing a new paradigm for sovereign AI systems.

Document Version: 1.0 Architectural Principle: Sovereignty through Undecidability
