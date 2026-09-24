# Hi, I'm Abdul Samad

I finished my Computing Science degree at the University of Alberta in June 2026. Most of what I build now is backend services, data pipelines, and apps with an LLM somewhere inside.

What I enjoy most is making that stuff hold up. That means real tests, evals that run on every push, retries that never double-count anything, and a record you can follow to see why a decision was made.

My portfolio has longer write-ups: https://samad-zeeshan.github.io/abdul-samad-zeeshan-portfolio/

## Things I've built

| Project | What it does | Built with |
|---|---|---|
| [Tally](https://github.com/samad-zeeshan/Tally) | A small bank on a double-entry ledger. Each transfer is two postings that cancel out, a retried request is safe, and a reconciliation endpoint can rebuild every balance from scratch. | Java, PostgreSQL, React, Docker |
| [Docket](https://github.com/samad-zeeshan/Docket) | Drop a receipt PDF into S3 and get back JSON that passes a schema check. Lambda calls Claude to do the reading. Failures land in a dead-letter queue with alarms, and an accuracy eval runs on every push. | TypeScript, AWS CDK, Lambda, Claude |
| [Change-Gate](https://github.com/samad-zeeshan/Change-Gate) | An approval step for config changes and feature-flag flips, shared across tenants. It scores the risk, approves the safe ones itself, sends the rest to a person, and keeps a decision record nobody can quietly edit. | Python, LangGraph, MCP, Keycloak |
| [Tarn](https://github.com/samad-zeeshan/Tarn) | A lakehouse for identity-security data. A billion real login events go through PySpark into a star schema, with streaming rollups and Neo4j graphs of privilege paths, all queryable from the browser. | PySpark, Redpanda, Neo4j |
| [Fulcrum](https://github.com/samad-zeeshan/Fulcrum) | Builds degree plans term by term and checks that they're valid. It mixes RAG and CAG depending on the workload and gets scored by a calibrated eval harness. | Python, retrieval, LLM evals |
| [Triage-0.6B](https://github.com/samad-zeeshan/Triage-0.6B) | Qwen3-0.6B, fine-tuned to read a support email and return triage JSON. I distilled it from a DeepSeek teacher. Priority accuracy went from 38% to 87% on 1,200 held-out tickets, and it runs offline as a GGUF. | PyTorch, LoRA, GGUF |
| [Touchstone](https://github.com/samad-zeeshan/Touchstone) | Interactive lessons on ideas where gut feeling tends to be wrong. A tested Python oracle produces every number and every grade. The LLM only rewords the explanations. | FastAPI, React 19, TypeScript |
| [Kvasir](https://github.com/samad-zeeshan/Kvasir) | An in-memory key-value store behind a concurrent TCP server, checked with Go's race detector. Transport, protocol, and storage each live in their own layer. | Go |
| [pathfinder](https://github.com/samad-zeeshan/pathfinder) | A pathfinding visualizer compiled to WebAssembly. [Try it in your browser.](https://samad-zeeshan.github.io/pathfinder/) | C++17, raylib, Emscripten |

## Experience

I've done three summer internships covering web, data, and automation work. The details are on my portfolio.

## Say hi

- Email: samad.z@outlook.com
- Portfolio: https://samad-zeeshan.github.io/abdul-samad-zeeshan-portfolio/
