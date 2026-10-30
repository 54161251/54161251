# Kaiwen Ji

Software engineering, AI agents, and workflow automation.

I am pursuing an **M.Eng. in Engineering Management at Cornell University (expected May 2027)**. I hold a **B.S. in Computer Science, Specialization in Artificial Intelligence, with a Minor in Data Science** from Indiana University Bloomington.

I am seeking new-graduate software engineering and AI tooling opportunities. My work focuses on Python services, retrieval-grounded applications, MCP integrations, and workflows that can be inspected and tested.

[LinkedIn](https://www.linkedin.com/in/kaiwen-ji-548b74253/)

## Start here

| Project | What to look at | Technologies |
|---|---|---|
| **[Agent Workflow Toolkit](https://github.com/54161251/agent-workflow-toolkit)** | Three independent projects: GitHub issue integration, revision-bound draft approvals, and offline agent regression evaluation | Python, MCP, SQLite, unittest/pytest, GitHub Actions |
| **[Local Task Tracker MCP](https://github.com/54161251/task-tracker-mcp)** | Persistent task tools, a planning prompt, parameterized SQL, validation, and a real MCP protocol demo | Python, SQLite, MCP |
| **[Indiana Insurance Assistant](https://github.com/54161251/indiana-insurance-assistant)** | Local-model chat with insurance retrieval, weather, ZIP lookup, and date tools; includes earlier project versions | Python, Streamlit, Ollama, LangChain, Chroma |

## Inside the toolkit

- **[GitHub Issue MCP](https://github.com/54161251/agent-workflow-toolkit/tree/main/github-issue-mcp):** repository-scoped issue search, issue previews/creation, validation, and safe upstream errors.
- **[Draft Approval Review Queue](https://github.com/54161251/agent-workflow-toolkit/tree/main/draft-approval-review-queue):** approvals bound to draft revisions and hashes, transactional state transitions, audit events, and local dry-runs.
- **[Agent Evaluation Lab](https://github.com/54161251/agent-workflow-toolkit/tree/main/agent-evaluation-lab):** policy checks on recorded traces, paired comparisons, and HTML/JSON reports. [View report preview](https://github.com/54161251/agent-workflow-toolkit/blob/main/agent-evaluation-lab/reports/demo-preview.png).

The older `github-issue-mcp` and `agent-review-queue` standalone repositories preserve previous links. Start with the toolkit for the combined portfolio. These projects are independently runnable; they are not a single integrated agent system.

## Technical background

- Python backend APIs, MySQL data workflows, React visualizations, and dependency debugging during a Microsoft internship.
- CodeQL source–sink dataflow analysis and Neo4j dependency mapping during an Institute of Computing Technology internship.
- Retrieval-grounded LLM research involving insurance clauses and evidence consistency checks.
- Recent Cornell coursework includes n8n scheduling, HTTP integration, branching, subworkflows, deduplication, and JavaScript validation. Sanitized workflow source is not yet published here.

## Project provenance

This portfolio includes coursework and personal prototypes prepared with OpenAI Codex assistance. Each repository documents scope, attribution, setup, and known limitations. Synthetic evaluation fixtures are labeled as synthetic; tests and demos are not claims of production deployment. Internship systems are summarized as experience and are not published in these repositories.

KI, a local personal-assistant prototype, is still being prepared for a separate public release; its source and installer are not currently linked here.
