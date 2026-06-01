# NotebookLM synthesis: what connects the uploaded papers

Source: NotebookLM notebook `zabka-research` (`f43b8997-4f47-4b79-b14c-c5e8c74a076d`)

## Shared themes

- **Unstructured data → structured models**: papers converge on transforming qualitative/semi-structured inputs (interviews, textual problem descriptions, reports, operational data) into structured knowledge graphs, causal maps, simulation models, or mathematical optimisation formulations.
- **Knowledge management + decision support**: logistics/SCM optimisation depends on capturing dispersed operational knowledge and turning it into manager-usable decision support.
- **Human-AI collaboration**: emerging LLM/OR work frames AI as a copilot, not a replacement; managers clarify ambiguity, validate constraints, and refine outputs.

## Theoretical anchors

- **Problem Structuring Methods (PSM)**: foundational for messy/ill-defined managerial problems before formal optimisation.
- **Ontologies / conceptual modelling**: e.g. supply-chain entities, resources, events, agents; useful as bridge from natural language to machine-readable problem schemas.
- **Autonomic / adaptive systems**: Monitor–Analyze–Plan–Execute loops relevant for logistics networks.
- **Multi-Criteria Decision Making (MCDM)**: useful for conflicting objectives: cost, delivery time, carbon, service quality, risk.

## Methods connected across papers

- LLM/NLP extraction: entity extraction, relationship extraction, knowledge mapping.
- LLM-assisted OR formulation: draft objectives, variables, constraints, MILO-style structures.
- Fuzzy logic / metaheuristics: uncertainty + multi-objective logistics decisions.
- Simulation: discrete-event and agent-based simulation for testing logistics system behaviour.

## Gaps

- **LLM hallucination / semantic errors**: LLMs still struggle to generate execution-ready OR models from vague descriptions.
- **Trust + explainability**: managers need auditable links from source text → extracted entities/constraints → model formulation.
- **Fragmented pipeline**: literature lacks an integrated framework connecting messy managerial problem framing → structured optimisation specification → validation/refinement.

## Proposed research contribution

An interactive **Decision Optimisation CoPilot** framework:

1. accepts messy logistics documents/data;
2. extracts entities, objectives, constraints, parameters, assumptions;
3. classifies optimisation problem type;
4. drafts an auditable problem schema / MILO-style formulation;
5. asks targeted clarification questions;
6. lets managers validate/refine;
7. outputs manager-readable brief + solver-ready model skeleton.

Core positioning: **LLM-supported problem structuring before optimisation**, grounded in PSM + logistics DSS + OR model formulation + human-AI collaboration.
