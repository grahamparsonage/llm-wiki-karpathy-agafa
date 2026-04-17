# Wiki Log

Append-only chronological record of all activity: ingests, queries, and lint passes.

To view recent activity: `grep "^## \[" log.md | tail -10`

---

## [2026-04-07] init | Wiki created

Wiki initialized for a technical writer's personal knowledge base.

Structure created:
- `raw/` — source documents folder
- `wiki/` — LLM-maintained knowledge base
- `wiki/sources/` — per-source summary pages
- `CLAUDE.md` — schema and operating instructions

Core pages created:
- `wiki/index.md`
- `wiki/log.md`
- `wiki/overview.md`
- `wiki/glossary.md`

Next step: Drop your first source into `raw/` and say **"ingest [filename]"**.

## [2026-04-17] ingest | AGAFA

Pages created:
- `wiki/sources/agafa.md`
- `wiki/products/agafa-framework.md`
- `wiki/concepts/legal-constraints-in-digital-forensics.md`
- `wiki/concepts/neuro-symbolic-ai.md`
- `wiki/concepts/retrieval-augmented-generation-rag.md`
- `wiki/concepts/knowledge-augmented-generation-kag.md`
- `wiki/concepts/answer-set-programming-asp.md`

Pages updated:
- `wiki/index.md`
- `wiki/glossary.md`
- `wiki/overview.md`

Key additions:
- AGAFA captured as a product/framework (not just a feature)
- Dedicated concept page for legal constraints in digital forensics
- Core concept set for neuro-symbolic AI, RAG, KAG, and ASP
- High-level-only treatment of sensitive use-case material
- Terminology normalization for AGAFA/DF/MM-LLM/RAG/KAG/OWL/RDF/ASP

## [2026-04-17] ingest | ACPO Good Practice Guide for Digital Evidence (v5)

Pages created:
- `wiki/sources/acpo-good-practice-guide-digital-evidence-v5.md`
- `wiki/concepts/acpo-four-principles-of-digital-evidence.md`
- `wiki/concepts/digital-forensic-triage-and-proportionality.md`
- `wiki/concepts/audit-trail-and-reproducibility-in-df.md`
- `wiki/style/forensic-reporting-fact-vs-opinion.md`
- `wiki/analyses/agafa-alignment-with-acpo-principles.md`

Pages updated:
- `wiki/index.md`
- `wiki/glossary.md`
- `wiki/overview.md`
- `wiki/concepts/legal-constraints-in-digital-forensics.md`
- `wiki/products/agafa-framework.md`

Key additions:
- UK-focused ACPO principles integrated as a procedural baseline
- New concept pages for principles, triage/proportionality, and auditability
- Reporting style rule clarifying fact vs opinion language
- Analysis page mapping AGAFA alignment and dependencies against ACPO expectations

## [2026-04-17] query | AGAFA compliance with ACPO guidelines

Pages consulted:
- `wiki/analyses/agafa-alignment-with-acpo-principles.md`
- `wiki/concepts/acpo-four-principles-of-digital-evidence.md`
- `wiki/products/agafa-framework.md`

Output filed: yes — `wiki/analyses/acpo-compliance-checklist-for-agafa-deployments.md`

## [2026-04-17] ingest | WIREs AI in digital forensics (ontology engineering)

Pages created:
- `wiki/sources/wires-ai-in-digital-forensics-ontology-engineering.md`
- `wiki/concepts/ontology-engineering-in-digital-forensics.md`
- `wiki/concepts/semantic-web-standards-for-digital-forensics-automation.md`
- `wiki/concepts/digital-forensic-ontology-standardization.md`

Pages updated:
- `wiki/index.md`
- `wiki/glossary.md`
- `wiki/overview.md`
- `wiki/concepts/neuro-symbolic-ai.md`
- `wiki/concepts/knowledge-augmented-generation-kag.md`

Key additions:
- Ontology engineering framed as a core enabler for DF automation and evidence fusion
- Semantic Web standards coverage (RDF/RDFS/OWL/SWRL/SPARQL) added to concept graph
- Standardization/interoperability challenges captured as dedicated concept
- Cross-linking between AGAFA/KAG and ontology-driven DF automation strengthened

## [2026-04-17] ingest | Reasoning with Rules and Ontologies

Pages created:
- `wiki/sources/reasoning-with-rules-and-ontologies-reasoning-web-2006.md`
- `wiki/concepts/rules-and-ontologies-integration.md`
- `wiki/concepts/semantic-web-querying-and-inference-patterns.md`

Pages updated:
- `wiki/index.md`
- `wiki/glossary.md`
- `wiki/overview.md`
- `wiki/concepts/semantic-web-standards-for-digital-forensics-automation.md`
- `wiki/concepts/answer-set-programming-asp.md`

Key additions:
- Rules-and-ontologies integration captured as an explicit concept in the wiki graph
- Query/inference pattern families added to support reasoning design decisions
- Semantic Web reasoning material linked to existing DF automation concepts
- ASP concept contextualized within broader rule/ontology integration landscape

## [2026-04-17] ingest | What Is Answer Set Programming?

Pages created:
- `wiki/sources/what-is-answer-set-programming-lifschitz-2008.md`

Pages updated:
- `wiki/index.md`
- `wiki/glossary.md`
- `wiki/overview.md`
- `wiki/concepts/answer-set-programming-asp.md`

Key additions:
- Canonical ASP source added with stable model and solver framing
- Generate-define-test modeling workflow explicitly documented
- ASP concept strengthened with foundational terminology and links
