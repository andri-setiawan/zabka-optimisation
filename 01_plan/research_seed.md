# Research seed: LLM-based logistics optimisation problem structuring

## Working title

LLM-based framework for helping managers structure logistics optimisation problems from unstructured and semi-structured data.

## Core idea

Managers often have messy operational inputs: emails, spreadsheets, SOPs, chat logs, reports, ERP exports, route notes, constraints, KPIs, exception narratives. The research will design/evaluate an LLM-based framework that converts these inputs into a structured optimisation problem representation.

## Intended contribution

- Problem-structuring layer before mathematical optimisation.
- Bridge managerial problem framing → formal logistics optimisation model.
- Handle unstructured/semi-structured data → objectives, decision variables, constraints, parameters, assumptions, missing data.
- Produce manager-readable and optimiser-ready outputs.

## Early research questions

1. How can LLMs extract and structure logistics optimisation problems from messy managerial data?
2. What representation/schema best captures objectives, constraints, decision variables, parameters, uncertainty, assumptions, and missing info?
3. How accurate/useful is the framework vs human analyst baselines?
4. How can managers validate, revise, and trust the structured problem specification?

## Candidate framework pipeline

1. Data ingestion: documents, spreadsheets, notes, emails, reports.
2. Context extraction: entities, facilities, SKUs, routes, vehicles, time windows, demand, capacity, costs.
3. Problem diagnosis: classify optimisation type, e.g. routing, inventory, facility location, scheduling, network design.
4. Formal structuring: objective(s), decision variables, constraints, parameters, assumptions.
5. Gap detection: missing/inconsistent/ambiguous data.
6. Interactive refinement: ask manager targeted clarification questions.
7. Output generation:
   - managerial problem brief
   - optimisation-model schema
   - solver-ready pseudo-model / Pyomo OR-Tools skeleton
   - audit trail linking claims to source snippets

## Initial keywords

LLM; logistics optimisation; problem structuring; decision support systems; operations research; mathematical programming; supply chain analytics; unstructured data; human-AI collaboration; model formulation.

## Next decisions

- Scope: logistics domain subset? routing/inventory/network design?
- Method: design science research? framework + prototype + case study?
- Evaluation: expert validation, synthetic benchmark, real company documents?
- Theory anchors: problem structuring methods, DSS, OR model formulation, human-AI decision support, knowledge extraction.
