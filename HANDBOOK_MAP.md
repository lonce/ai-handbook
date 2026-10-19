# Galgo AI Handbook — Working Map

**Status:** Working draft. This is a topic map, not an approved table of contents or a commitment to produce every page below.

**Purpose:** Give the handbook maintainer and contributing agents a shared picture of the material the handbook may cover, who needs it, and where new material might belong. Keep the map useful and revisable as the project develops.

## How to use this map

- Treat entries as proposed topics. Do not turn them into Galgo policy without an explicit decision by the appropriate people.
- Before adding a page, check whether an existing page already covers the question. Suggest a location and any related pages.
- Use the audience and page-type labels below as navigation aids; most topics will serve more than one audience.
- Write focused pages rather than one long, linear manual. Link shared explanations from the relevant reader paths.
- Use Diátaxis to choose a page form: **explanation** (build understanding), **tutorial** (learn by doing), **how-to** (complete a task), or **reference** (look up a fact or procedure).
- Keep frequently changing information—such as model availability and prices—in a dated, sourced catalog or register rather than embedding it in many pages.

## Reader paths

These are entry points into shared material, not separate duplicate handbooks.

### Leadership

For C-suite and other decision-makers:

- What AI may change about software businesses, customer value, work, and Galgo.
- Where AI may improve current work, and where it could create material risk.
- Local, cloud, and hybrid deployment choices; cost and infrastructure implications.
- How to fund, evaluate, govern, and expand a small number of useful pilots.
- Decisions and responsibilities that need an accountable human owner.

### Documentation and quality teams

For compliance users and technical documentation staff:

- How to identify suitable document-related tasks and define a useful output.
- How to work with approved source material, versions, and citations.
- How to review AI-generated summaries, comparisons, and draft text.
- How AI use may interact with controlled workflows, including Dot Compliance, without making this handbook a repository for controlled documents or procedures.
- How to distinguish a draft suggestion from an approved record or decision.

### Developers and technical staff

For software developers and technical contributors:

- How to use coding agents through planning, implementation, testing, and review.
- How to share repository instructions and reusable workflows.
- How to protect code, secrets, data, and system access.
- How to evaluate coding assistance on Galgo-relevant tasks.
- How to connect agents to tools and services safely and maintainably.

### Shared orientation

For everyone:

- What models, agents, tools, workflows, and “local versus cloud” mean.
- How to use this handbook and interpret its status labels.
- Basic privacy, security, verification, and human-review principles.

## Proposed sections and topics

### 1. Start here: purpose and orientation

- Why Galgo is assembling an AI handbook.
- What the handbook covers and what it does not cover.
- How to use the leadership, documentation/quality, developer, and shared paths.
- How to read status labels, dates, sources, and model-catalog entries.
- Glossary and “where should I start?” guide.

**Likely page types:** explanation, reference.

### 2. AI and agents: core concepts

- AI, machine learning, foundation models, and large language models in plain language.
- Model versus agent versus agentic workflow; a chat interface may front an agent.
- The agent loop: receive a goal, gather context, use tools, inspect results, and continue or stop.
- Agent components: model, instructions, context, tools, state, memory, evaluation, permissions, and execution environment.
- Harnesses, skills, MCP/tool connections, hooks, scripts, and subagents.
- What “context” includes: task objective, source evidence, instructions, tools, history, and relevant organizational knowledge.
- What agents can and cannot reliably do; why fluent output is not proof of correctness.

**Likely page types:** explanation, tutorial, reference.

### 3. What AI may mean for Galgo

- Galgo’s context as a medical-software company working in visualization and surgical planning, as described in company-approved sources.
- Potential sources of value beyond code generation: trusted workflows, clinical evidence, integration, service, relationships, data, know-how, and ecosystem.
- Where AI may help across product development and company operations.
- High-consequence failure examples to assess, such as privacy exposure, image misidentification, or unsafe planning support; keep examples hypothetical unless Galgo verifies them.
- Questions about economics, software replication, defensibility, organizational change, and the future value customers receive.
- How to identify a good pilot: repeated task, clear input, reviewable output, measurable benefit, and an appropriate owner.

**Likely page types:** explanation, how-to.

### 4. Where models and agents run

- Cloud inference, local inference, local agent execution with cloud inference, and hybrid architectures.
- Separate the location of the files/tools/agent environment from the location where model inference happens.
- Data classification and what may be sent to which service; patient, customer, confidential, and public information.
- Privacy, security, access control, retention, data residency, and provider terms to verify.
- Hardware, latency, connectivity, operating cost, model capability, maintenance, and support tradeoffs.
- Reliability, recovery, continuity, vendor dependence, and who can safely operate the setup.
- Patterns for connecting agents to company systems, including questions to resolve before any Dot Compliance integration.

**Likely page types:** explanation, how-to, reference.

### 5. Models, agents, and tools catalog

A maintained, source-backed catalog rather than a fixed “top ten” ranking.

- Models by task and capability: writing, summarization, document extraction, coding, vision, tool use, and other relevant tasks.
- Agent products and coding/document workflows, with the model(s) they expose when verified.
- Local/cloud requirements, hardware needs, context limits, supported modalities, access and licensing assumptions.
- Price snapshots and representative task-cost estimates, with assumptions and “checked on” date.
- Privacy and data-handling details to verify before use.
- Known strengths, limitations, uncertainty, and Galgo-specific test results when available.
- Benchmark research and charts; explain what a benchmark measures and whether it predicts Galgo task performance.
- Distinguish vendor-described claims, independent evidence, and results observed by Galgo.

**Possible data format:** Markdown pages for interpretation plus a structured YAML/CSV register if the comparison becomes large enough to maintain that way.

**Likely page types:** reference, explanation.

### 6. Designing and operating agent workflows

- Turn a vague request into a bounded task brief: objective, inputs, constraints, output, quality criteria, and stop condition.
- Make “good” and “done” observable; state what evidence supports each finding.
- Break complex work into stages with clear handoffs and artifacts.
- Use one agent or multiple agents appropriately; multi-agent review is an option, not a default requirement or proof of correctness.
- Give an agent only the context and permissions needed for its task.
- Set human review and approval points, especially for consequential decisions or external changes.
- Verify sources, versions, calculations, code, and generated artifacts independently where appropriate.
- Common failure modes: goal drift, missing context, stale sources, overconfident unsupported claims, weak self-review, and excessive cost.
- Reusable workflows, skills, templates, hooks, tools, and evaluation datasets.
- Record successful patterns so the team can reuse and improve them.

**Likely page types:** tutorial, how-to, explanation, reference.

### 7. Shared AI practices for software development

- Repository guidance: purpose of `AGENTS.md`, project maps, coding instructions, and scoped instructions.
- Shared Markdown conventions and where to keep durable guidance versus task-specific plans.
- Coding-agent workflow: understand the request, inspect the code, plan, implement a small change, run tests, review the diff, and report evidence.
- Human ownership of requirements, architecture, code review, and release decisions.
- Testing AI-generated code, including edge cases, regressions, security, and failure handling.
- Safe handling of credentials, proprietary source code, training data, and external services.
- How teams share prompts, skills, tools, and agent configurations while keeping them portable where practical.
- Examples and guidance for Galgo software projects only after the relevant projects, owners, and constraints are confirmed.

**Likely page types:** tutorial, how-to, reference.

### 8. AI practices for documentation and quality work

- Choosing appropriate support tasks: search, summarize, compare versions, extract information, draft, and flag possible gaps.
- Use current, approved source documents and preserve exact source references.
- Separate AI assistance from controlled document ownership, review, approval, and retention.
- Keep this handbook distinct from the documents and records managed in Dot Compliance.
- Discuss AI/QMS integration only as general architecture and governance guidance unless Galgo verifies a specific configuration or capability.
- Review checklists for accuracy, provenance, omissions, privacy, and handling of uncertainty.

**Likely page types:** tutorial, how-to, reference.

### 9. Evaluation, costs, and governance

- Evaluate a tool against representative Galgo tasks, not only public leaderboards.
- Define a small test set, expected outputs, error categories, reviewers, and acceptance criteria.
- Measure usefulness, accuracy, citation quality, edge cases, time saved, reviewer effort, and total task cost.
- Assign owners for the workflow, data, tool configuration, model changes, review, and ongoing monitoring.
- Consider liability and risk ownership as questions for Galgo leadership and relevant specialists—not as conclusions supplied by the handbook.
- Establish a proportionate process for pilots, approval, staff training, incident handling, and retirement of tools.

**Likely page types:** explanation, how-to, reference.

### 10. Technical background and further study

- Tokens and context windows; retrieval and embeddings; prompt/context management.
- Fine-tuning, LoRA, quantization, distillation, and when these approaches may or may not be useful.
- Evaluation methods and benchmark interpretation.
- Agent frameworks and skill repositories worth considering.
- Further reading, carefully selected videos, papers, official documentation, and practical examples.

Keep this section optional or advanced so it does not obstruct the practical reader paths.

## Appendices and reusable material

- Glossary.
- Model and agent comparison register.
- Templates: task brief, evaluation record, model entry, agent/workflow description, source note.
- Examples of successful workflows and lessons learned.
- Source directory and review log.
- Change history for the handbook itself.

## Open questions for the project owner

These are planning questions, not requirements for the first draft:

- Which Galgo software projects should eventually receive project-specific examples?
- How much of the model catalog should be global market monitoring versus tools Galgo is actively considering or testing?
- What task types should a first Galgo model evaluation cover?
- Who can confirm internal practices, approved tools, data classifications, and product-specific facts?
- What is the appropriate cadence for reviewing volatile catalog entries?
- Should the handbook use reader labels, icons, or another navigation aid?
- What publishing setup and access controls will Galgo choose?

