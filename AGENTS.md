# AGENTS.md

## Project purpose

This repository contains a living handbook about AI and agents and their effective use at Galgo Medical. It is intended to help Galgo staff make sense of a fast-changing field and apply useful, well-supported practices to their work.

The handbook is a shared learning and practice resource. It is separate from the controlled documents, procedures, and records managed through Dot Compliance, and it should not contain project-specific software documentation that belongs in a product repository.

The handbook should reduce the need for each reader to sift through large amounts of web and video material that may be outdated, aimed at other organizations, inconsistent, or of unclear relevance to Galgo. Some content will change frequently, especially model and tool comparisons, prices, and provider capabilities.

## Project references

- Read `PROJECT_CONTEXT.md` for the handbook’s purpose, audiences, boundaries, and evidence conventions.
- Read `HANDBOOK_MAP.md` for the provisional topic map and reader paths.
- Treat both as working project guidance, not as approved Galgo policy.

## Galgo context

The project owner describes Galgo as a Barcelona-based medical software company working on visualization and surgical planning. Connect AI concepts to Galgo’s work when reliable information supports the connection.

Do not assume details about Galgo’s products, systems, policies, workflows, or decisions unless they are documented in the repository or supplied or confirmed by the project owner or an appropriate Galgo owner.

## Audience and writing

Write for:

- Company leaders who need to understand opportunities, costs, and risks.
- Documentation and quality staff who need practical workflow guidance.
- Developers and technical staff who need guidance on models, agents, tools, and code-development practices.
- Other Galgo staff who need a shared vocabulary and basic orientation.

Make a page’s intended audience clear. Use consistent text labels; icons may supplement them but should not be the only way to identify an audience. Some pages will serve several groups.

Explain specialist terms when they first matter. Keep writing clear and professional for readers with different levels of technical experience. Use simple diagrams or images when they improve understanding.

## Handbook objectives

Help readers understand:

- What AI models and agents do, and how they differ.
- How local, cloud, and hybrid use affect privacy, cost, access, and capability.
- Which models and tools may fit particular tasks, and what their limitations are.
- How to use agents in repeatable, shareable workflows.
- How to develop and review code with AI assistance.
- How to evaluate AI tools and update practices over time.
- The costs and tradeoffs of available tools.
- How to design effective, trustworthy agent harnesses.
- Where to find useful skills, tools, and further guidance.

## Scope and boundaries

- This handbook provides general AI learning and practice guidance for Galgo. It is not the Dot Compliance document-control system.
- Do not present suggestions or emerging practices as approved Galgo policy. Label their status clearly, for example: informational, proposed, being evaluated, tested by Galgo, or approved.
- Do not make clinical, regulatory, legal, privacy, or security determinations on Galgo’s behalf. Identify issues that need review by the appropriate person.
- Do not include confidential, personal, patient, or customer data unless the project owner confirms that the material is approved for the specific task and destination.
- Keep examples hypothetical or sanitized unless there is a confirmed reason and authorization to use real information.

## Working in this repository

Before drafting or substantially revising a page:

1. Read `PROJECT_CONTEXT.md` and `HANDBOOK_MAP.md`.
2. Check for existing pages that already cover the topic.
3. Identify the page’s audience, purpose, and Diátaxis type: explanation, tutorial, how-to guide, or reference.
4. Keep the page focused on a reader’s question or task, and link to related material rather than duplicating it.
5. If the topic does not fit the current map, propose a suitable location. Update the map for routine additions; discuss major structural changes with the project owner before applying them.

For claims that can change—such as model availability, prices, capabilities, provider terms, or regulations—use a reliable source and record the date checked. Distinguish vendor statements, independent evidence, project-owner information, and results Galgo has tested. Mark uncertainty and source conflicts instead of filling gaps with guesses. Follow the evidence conventions in `PROJECT_CONTEXT.md`.

Keep durable repository guidance in these project files. Do not add task-specific instructions to `AGENTS.md` unless they should apply to future work in this repository.


### Repository layout

- `docs/` contains edited handbook pages intended for publication.
- `working/` contains drafts, notes, open questions, and decision records.
  Do not publish these files or move them into `docs/` without the project
  owner’s direction.
- `site/` contains the HTML website generated from the Markdown handbook by Zensical.
- `.codex/skills/` contains reusable Codex skills. Keep general project
  instructions in this file; put repeatable workflows in skills.
- `PROJECT_CONTEXT.md` describes the project’s purpose and boundaries.
- `HANDBOOK_MAP.md` is the provisional guide to handbook topics.

When developing an idea, start in `working/`. Move it into `docs/` when it
has been reviewed and is ready for the handbook.

## Before finishing a task

Summarize the files changed, important sources used, assumptions made, and questions that need a human decision. Make proposed content and structural changes easy to review. Do not claim that a recommendation or practice is approved unless its owner has confirmed that status.

## Publication

Develop the handbook as linked Markdown files in Git, with a clear index and glossary. Use Zensical as the site builder, with `docs/` as the publication source and `site/` as the generated HTML output. Keep `working/` outside the publication source. Zensical is installed in the local `.venv/`; `zensical.toml` configures the build and `requirements.txt` pins the builder version. See `README.md` for setup, preview, and build commands. The generated website may be published on a Galgo-maintained server. Keep the Markdown source usable and organized even if the publishing setup changes.

