# Project Context — Galgo AI Handbook

**Status:** Working context for the handbook author and assisting agents. It records the project’s purpose and useful background; it is not an approved Galgo policy, quality procedure, or source of product claims.

## Why this handbook is being created

The project owner is assembling a practical, company-specific guide to AI and agentic work at Galgo Medical. The aim is to help Galgo colleagues avoid having to independently sort through a large, noisy, rapidly changing body of material that may be outdated, vendor-oriented, technically mismatched, or irrelevant to Galgo.

The intended resource is broad enough to explain fundamentals and practical enough to help people make decisions and carry out work. It is expected to grow over time, while its core structure remains understandable. The working source is planned as linked Markdown files in Git, with a static website as a possible publication format.

## What the handbook is—and is not

The handbook is a **general AI practice and learning resource for Galgo**. Likely topics include AI models and agents, model selection, local and cloud deployment, cost, data/privacy, shared agent instructions, code-development practices, workflow design, evaluation, and company adoption.

It is separate from the controlled documents, procedures, and records that Galgo manages through Dot Compliance. Dot Compliance may still appear as an example when discussing how AI tools could interact with existing company systems, but the handbook is not a duplicate eQMS, and it should not become the home for controlled QMS content.

The handbook may explain practices, compare options, or recommend experiments. It must not imply that a recommendation is approved Galgo policy unless the appropriate Galgo owner confirms that status. It does not make clinical, regulatory, legal, privacy, or security determinations on Galgo’s behalf.

## Company context

The project owner describes Galgo as a Barcelona-based medical software company working on visualization and surgical planning. The public Galgo website also presents the company as working on medical imaging software solutions. The website is useful for high-level orientation, but its retrieved page indicates a February 2023 review date; use it as a dated public source rather than as definitive evidence of current internal structure, products, policies, or workflows.

Some company-specific details remain unknown in the current project materials, including the exact product and software-project inventory, current internal AI policies, approved tools, data classifications, and which proposed AI workflows Galgo intends to pilot. Keep these as questions until confirmed by the project owner or an appropriate Galgo contact.

## Audiences

The handbook is intended to serve readers with different responsibilities and levels of familiarity:

- **Leadership and C-suite:** strategic implications, opportunities, costs, risks, investment, accountability, and effects on Galgo’s business and work.
- **Documentation and quality staff:** practical AI assistance for information work and documentation, with a clear boundary between drafts or analysis and controlled records in Dot Compliance.
- **Technical documentation staff:** technical content creation and maintenance, source consistency, change impact, and review.
- **Software developers and technical staff:** models, coding agents, local/cloud environments, repository instructions, tools, tests, evaluation, and safe workflows.
- **All staff:** shared vocabulary, basic understanding of agents, data/privacy considerations, and how to assess AI output.

Where a page is useful to multiple audiences, prefer one shared explanation with links from the relevant reader paths over duplicate chapters.

## Prior presentation as a foundation

The attached presentation, **“Agents for quality & compliance,”** is a useful conceptual predecessor. Its central material can inform the handbook’s explanations of agents and workflows:

- An agent is more than a prompt or model response: it works through a loop of gathering context, taking permitted actions, checking results, and continuing or stopping.
- Agent context can include instructions, source evidence, tools, history/state, organizational responsibilities, and a clear task objective.
- A useful description of an agent/harness includes goals and instructions, context, tools, scripts, skills, and the agent loop, with permissions, traceability, evaluation, and human review across the system.
- More autonomy does not automatically mean more reliability. The deck highlights goal drift, context loss, self-evaluation bias, and unsupported confidence, and argues for bounded tasks, provenance, independent checks, and human decision owners.
- Complex work can be split into stages with explicit inputs, outputs, artifacts, acceptance criteria, and approval gates. Multiple agents can be used for parallel analysis or critique, but are a pattern to evaluate—not a requirement or a guarantee of correctness.
- Good workflows begin by defining what “good” and “done” mean, and by specifying the evidence a reviewer should be able to inspect.
- Human expertise remains central: people define the standard, judge evidence, and own decisions.

The presentation also used regulatory-change impact analysis in Dot Compliance as a concrete example. For this handbook, treat that as **one applied example**, not the organizing structure for the whole resource. Its Dot Compliance and vendor capability statements are snapshots from the presentation and must be rechecked before reuse; do not assume they describe Galgo’s current configuration or verified integration options.

## Working principles for Galgo-specific material

- Make the material specific to Galgo’s setting when supported by current, reliable information; avoid generic claims presented as if they were Galgo facts.
- Distinguish among: **public-source statement**, **project-owner statement**, **inference**, **proposal**, **being evaluated**, **tested by Galgo**, and **approved Galgo practice**.
- For changing claims—model names, capabilities, access, costs, regulations, vendor features—use current sources and record when they were checked.
- Distinguish vendor-described capabilities from independent evidence and from Galgo’s own tests.
- Prefer task-oriented comparisons over universal “best model” rankings. Report what a model appears suited for, its limitations, deployment assumptions, and evidence.
- Keep examples hypothetical or sanitized unless Galgo has approved the material and data for the intended use. Do not introduce patient, customer, or confidential information into examples without explicit authorization.
- Translate technical concepts for mixed audiences without oversimplifying meaningful uncertainty or risk.

## Source and evidence notes

Use this order when establishing Galgo-specific context:

1. Current information explicitly supplied or confirmed by the project owner or an authorized Galgo subject-matter owner.
2. Current, official Galgo materials, with the page or document and review date recorded.
3. Current official vendor documentation for claims about a vendor’s own tools, clearly labeled as vendor claims.
4. Primary research, standards, and authoritative regulatory sources for technical or regulatory background.
5. Secondary commentary for orientation only, not as the sole basis for high-impact claims.

If sources conflict, preserve the conflict and ask for review rather than silently choosing one. Never fill unknown company facts with guesses.

## Relationship to the working map

`HANDBOOK_MAP.md` is the current provisional inventory and navigation proposal. It may be reorganized as the project progresses. The original outline remains a brainstorm source; it is not an approved final table of contents.

Before drafting a page, consult both this file and the map. If the right location or scope is unclear, propose options and explain the tradeoff before reorganizing the map or creating a cluster of pages.

