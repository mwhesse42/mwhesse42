# Mike Hesse

**Principal Engineer · Agentic AI for Enterprise & Regulated Industries · Engineer + Business (BSc CS, BComm)**
Calgary, Alberta

I've spent 20+ years building software where mistakes are expensive: pipelines, mining, energy, clinical trials, banking and education. I trained in both computer science and commerce, so I start with the business problem and work back to the architecture.

My focus now is bringing agentic AI into that kind of environment responsibly. That means building with Claude Code and Codex inside multi-agent workflows, and setting the guardrails teams need to ship that way safely: architecture, review, automated testing and deployment risk analysis.

Most of my client work lives in private repositories, so this profile is where I'm starting to share the patterns and tooling behind it.

## What I'm doing now

**Provision** · Senior Developer — Agentic AI Engineering · Sept 2026 – Present

I designed and run a 13-step agentic delivery pipeline that takes a ticket to a reviewed, human-approved change:

- **Spec and intake gate.** The ticket's asks are quoted word for word, conflicts are listed, and bug-vs-feature is decided before any code is written.
- **Baseline vs change.** Each story runs on isolated Git worktrees beside a baseline stack pinned to its branch point, with its own ports and databases, so several stories can run in parallel.
- **Evidence-gated tests.** A new test only counts if it fails on the unfixed code for the right reason.
- **Fresh-context agents.** Separate review, refactor, QA and exploratory-browser agents, each scoped to the tools and model the task needs. Reviewers start from the ticket, not the diff.
- **Human hand-back.** Nothing is committed until a person has clicked through the change.
- **Process change control.** Every failure is logged against the stage that should have caught it, process versions are frozen until proven, and a scheduled retro recommends changes. Each rule in the process traces back to a real incident.

Stack: React · C# / .NET · Azure · Kubernetes · Docker · Playwright

## Projects

- **[scoped-google-drive-mcp](https://github.com/mwhesse42/scoped-google-drive-mcp)** · C# / .NET MCP server that gives an AI agent access only to the Google Drive files and folders you share with it. The standard Drive connectors ask for your whole Drive; this one signs in as a Google service account, so access is granted and revoked through Drive sharing. It has a read-only mode, unit tests against a mocked Drive client, and CI.

## How I work

- **Treat the AI workflow as a system.** Measure where it fails, fix the stage that should have caught it, and only change the process when the evidence says so.
- **Lead the adoption, not just the tooling.** I help teams change how they build with AI: workflows, review standards, and the trust model between people and agents.
- **Architecture first, AI for throughput.** Agents write code quickly, so the system design has to be clear enough to keep them on track.
- **Tests are the contract.** TDD with 80–90%+ backend coverage on most of my projects, and now AI-generated test suites with a human reviewing them.
- **Talk to the business.** I translate operational problems into working software through iterative delivery.

## Core technologies

- **AI engineering:** Claude Code, Codex, Anthropic API, multi-agent workflows
- **Application:** C# / .NET, TypeScript, React, Node.js, PostgreSQL
- **Cloud & infra:** AWS (Lambda, CDK, Cognito, Aurora), Azure, Kubernetes, Docker
- **Quality:** Playwright, TDD, CI/CD

AWS Solutions Architect – Associate · AWS Developer – Associate · AWS Cloud Practitioner

## Selected work

- **CovarsaDx: TrialPath.** Led the architecture of a cloud clinical trial management platform and brought Claude Code into the team's daily delivery.
- **Nutrien: Minesight.** Backend lead for an offline-capable mine-operations app running across multiple potash mines.
- **TC Energy: Feature Assessment simulator.** Serverless HPC design that fans pipeline integrity simulations out across AWS.
- **Shaw Communications: shaw.ca.** Architected the microservices foundation for Shaw's digital eCommerce experience.
- **Calgary Board of Education: Iris.** Teaching and learning platform reaching 120,000 students and 23,000 teachers.

## Connect

[LinkedIn](https://linkedin.com/in/mwhesse)
