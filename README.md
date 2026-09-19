<h1 align="center">Abiola Adedayo Adeshina</h1>

<p align="center">
  <strong>AI Agent Infrastructure Engineer</strong><br />
  Agent runtimes · Execution evidence · Evaluation
</p>

<p align="center">
  <a href="https://github.com/Abiorh001">GitHub</a> ·
  <a href="https://www.linkedin.com/in/abiolaadeshina/">LinkedIn</a> ·
  <a href="https://twitter.com/abiorhmangana">X</a> ·
  <a href="mailto:abiolaadeshinaadedayo@gmail.com">Email</a>
</p>

---

I’m a software engineer focused on **AI agent infrastructure and evaluation**. I build the systems around AI agents: how they execute tools, manage context and state, preserve evidence, and get evaluated.

Based in Nigeria, I’m the founder of **OmniRexflora Labs**, **Workstream Lead at Flow Research**, and an **AI Expert Contributor at Snorkel AI**. My work connects backend engineering, agent runtime design, and hands-on evaluation of coding agents across languages, toolchains, and execution environments.

## Current work

### [OmniCoreAgent](https://github.com/omnirexflora-labs/omnicoreagent) — Agent runtime and execution evidence

I build and maintain an open-source Python agent harness that brings tool execution, MCP integrations, memory, context management, workspaces, and background tasks into one runtime.

My current focus is **native tool calling, parallel tool execution, streaming, and execution telemetry**: connecting user requests, model interactions, tool calls, tool results, context changes, and final responses.

I’m developing the path from that evidence to **application-specific offline evaluation**—using production behavior to inform controlled tests, rather than treating a recorded trace as an experiment or proof of success.

### [Workstream](https://github.com/Flow-Research/workstream) — Governed contribution infrastructure

At Flow Research, I lead the engineering of infrastructure for coordinating, verifying, and recording work performed by humans, AI agents, or both.

The work spans **identity and authorization, project-scoped permissions, versioned policies, immutable submissions, check evidence, and review/revision workflows**. The lifecycle is designed to produce trustworthy contribution records that preserve who did what, under which rules, and with what accepted outcome.

**Currently under active v0.1 development.** A submission, a passing check, and an accepted contribution are different facts; the system must preserve those distinctions.

### Snorkel AI — Coding-agent evaluation and benchmarking

I create and review executable evaluation tasks covering terminal-based engineering, long-horizon coding, and research-reproduction workflows. I’ve completed **1,000+ task reviews** across projects, with authoring and review contributions spanning **Terminal-Bench** and other agent-evaluation programs.

This work takes me across languages and toolchains: understanding codebases, reviewing implementations, investigating failures, and checking whether tests establish the behavior required by the task contract.

My work includes task specifications, reproducible environments, reference solutions, executable verifiers, rubric-based assessment, and repeated-run failure analysis. It spans **multi-turn pairwise model evaluation**—comparing trajectories for correctness, agency, and alignment—and **verifier-backed tasks run through Harbor** for RLVR-oriented workflows.

## How I approach engineering

**A trace is evidence, not an experiment. A verifier is only useful when it checks the right contract.**

I care about explicit trust boundaries, reproducible tests, meaningful failure analysis, and preserving the evidence needed to explain what happened.

My standard for engineering ownership is straightforward: explain the architecture, justify the tradeoffs, and reason about failure modes—not just produce working code.

## Tools and environments

**Languages I’ve worked with:** C, C++, C#, Rust, Go, TypeScript, Python, Bash, Perl.  
**Backend and runtime:** FastAPI, asyncio, AnyIO, PostgreSQL, Redis.  
**Infrastructure and integration:** Docker, Linux, MCP, REST APIs, object storage.  
**Evaluation:** Harbor, executable verifiers, rubric design, trajectory analysis, reproducibility, and failure analysis.
