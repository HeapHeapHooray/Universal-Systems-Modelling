# Universal Systems Modelling

> **A curated knowledge base, mathematical ontology, and operational prompt designed to train and guide an AI coding agent/analytical partner in real-time universal systems modeling.**

---

## 🧭 Overview

This repository houses the source materials, mathematical foundations, and operational instructions used to instruct an AI assistant to act as a **Universal Systems Modeler & Analytical Thought Partner**.

Rather than generic explanations, this setup equips the agent to deconstruct arbitrary phenomena—physical, computational, biological, mechanical, or abstract—into rigorous mathematical structures (differential manifolds, phase spaces, vector fields, Lie symmetries, and attractor topologies) while maintaining intuitive pedagogical pacing.

---

## 📐 Foundational Grammar: The 5-Part Descriptive Protocol

Whenever deconstructing or modeling an arbitrary system, the agent adheres to this 5-part architecture:

| # | Pillar | Focus | Mathematical Machinery |
|---|---|---|---|
| **1** | **Boundary & Metric** *(The Arena)* | Spatial boundaries, manifold constraints, degrees of freedom | Metric tensors ($g_{\mu\nu}$), boundary conditions, charts |
| **2** | **State Vector** *(The Configuration)* | Minimal coordinate tuple specifying state without prior history | Coordinate tuples $\mathbf{x}(t)$ in Phase Space / Hilbert Space |
| **3** | **Invariants & Symmetries** *(The Constraints)* | Conserved quantities and continuous symmetries | Lie groups ($U(1), SU(2), SO(n)$), Noether currents, invariants |
| **4** | **Operator / Vector Field** *(The Dynamics)* | Directional state evolution across time or parameter space | Equations of motion, transfer functions, Jacobians, phase velocities |
| **5** | **Regime & Topology** *(The Attractor)* | Long-term equilibria and critical parameter tipping points | Fixed points, limit cycles, strange attractors, bifurcations |

### 🎙️ The Real-Time Verbal Drill
For compact verbal snapshots and real-time intuition:
> *"The system is an **[Arena / Boundary]** parameterized by **[State Vector coordinates]**. It evolves along **[Dynamics / Vector Field]** subject to **[Invariants / Constraints]**, converging toward an **[Attractor / Equilibrium]** unless altered by a **[Bifurcation threshold]**."*

---

## 📂 Repository Structure

```text
.
├── README.md
└── notebook/
    ├── Notebook Prompt.md              # Core operational instructions & persona definition
    └── sources/
        ├── Description Framework.txt    # 5-part protocol and verbal drill template
        ├── Mathematical Concepts.txt    # Operational definitions & systems ontology
        └── Universal Systems Modelling.txt # High-level framework overview
```

### Module Descriptions
- **[`notebook/Notebook Prompt.md`](notebook/Notebook%20Prompt.md)**: The foundational agent prompt. Dictates technical density, pedagogical dual-pacing (formal mathematics by default, intuitive physical grounding on request), two-tier summaries, and strict terminological standards (Jacobians as coordinate conversion rates, phase space velocity, atemporal formulations).
- **[`notebook/sources/Description Framework.txt`](notebook/sources/Description%20Framework.txt)**: Concise definition of the 5-part protocol and verbal drill formula.
- **[`notebook/sources/Mathematical Concepts.txt`](notebook/sources/Mathematical%20Concepts.txt)**: Core glossary bridging differential geometry, dynamical systems theory, and machine learning (null-space eigendecomposition, latent spaces as fiber bundles, geodesics, bifurcations).
- **[`notebook/sources/Universal Systems Modelling.txt`](notebook/sources/Universal%20Systems%20Modelling.txt)**: Framework manifesto illustrating the deconstruction of real-world phenomena into mathematically governed systems.

---

## 🤖 Agent Operating Dynamics

When active, the agent adheres to three interaction rules:
1. **Direct Content Delivery**: Answers open immediately with analytical substance—zero introductory fluff or conversational boilerplate.
2. **Pedagogical Dual-Pacing**:
   - *Default*: High-density formal breakdowns using exact mathematical and theoretical physics terminology.
   - *On "Simplify"*: Grounds concepts in tangible physical analogies (e.g., ball on a potential surface, fluid rolls), breaking down previous formulations clause-by-clause without watering down accuracy.
3. **Two-Tier Summaries**: Every summary delivers both a formal technical distillation and a 1-to-2 sentence verbal drill.

---

## 📄 License

This repository is available under the [MIT License](LICENSE).
