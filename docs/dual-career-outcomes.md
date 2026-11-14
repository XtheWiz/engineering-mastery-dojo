# Dual Career Outcomes Addendum

Status: **Proposed — pending PR review**. This is an additive policy, not a reset or new independent syllabus.

## Mission
Develop independent ability to understand, design, build, debug, secure, deploy, operate and deliver sophisticated real-world software and AI systems.

## Career outcomes
1. **Primary: Forward Deployed Software Engineer (FDSE)** — production-grade backend/full-stack implementation; integration with customer systems, APIs, databases, messaging and data pipelines; unfamiliar codebase investigation; debugging, reliability, performance; end-to-end technical delivery and customer engineering collaboration.
2. **Primary: Forward Deployed Engineer (FDE)** — discovery, problem framing, measurable business outcomes, requirements and constraints, feasible architecture, delivery ownership, stakeholder communication, risks, deployment, operations and handover. Preserve the existing FDE Applied Engineering Track; extend rather than replace it.
3. **Primary complementary: Applied AI Engineer** — Python, LLM APIs, RAG, MCP, tools/agents, evaluation, prompt-injection defense, reliable secure integration, AI observability, deployment, cost and latency.
4. **Future specialization: AI Infrastructure Engineer** — distributed systems, model/inference serving, GPU fundamentals, scalability, performance and reliability. No acceleration before the core is ready.

These are distinct competency outcomes, **not four duplicative curricula**.

## Competency map
| Layer | Scope | Evidence can support |
| --- | --- | --- |
| Shared engineering core | Programming, DSA, Java/JVM, concurrency, database, API and backend, architecture, testing/debugging, Linux, security/DevSecOps, cloud, containers, CI/CD, observability, Python, practical full stack | All outcomes |
| Applied AI core | LLM integration, RAG/agents/MCP, eval, guardrails/security, reliability, AI production | Applied AI, FDSE, FDE as relevant |
| FDSE-specific | Complex software implementation, customer system integration, unfamiliar codebases, production debugging, delivery quality, operational reliability | FDSE |
| FDE-specific | Discovery, problem framing, scoping, architecture, customer communication, ownership and business outcomes | FDE |
| Future infrastructure | Serving/inference, GPU/VRAM, benchmarks, scaling, reliability | AI Infrastructure |

## Existing system integration
Do not delete or replace:
- FDE Applied Engineering Track
- DevSecOps & Secure AI Engineering Addendum
- Project-Based Mastery Assessment and Capstone System
- Current fundamentals-first, mastery-based assessment state and historical evidence.

**Identified gap**: express role-specific outcomes and map existing practical evidence to each outcome independently; add unfamiliar codebase and complex integration assessments for FDSE, explicit outcome/communication assessment for FDE, and career-readiness evidence tracking. Do not create a new track that repeats the core.

## Assessment dimensions
Baseline dimensions: **Correctness, Reasoning, Implementation, Debugging, Trade-offs, Production Readiness**.

Additional **FDSE evidence**: integration complexity, unfamiliar codebase comprehension, delivery quality, operational reliability.

Additional **FDE evidence**: problem discovery, requirements clarity, feasibility, stakeholder communication, measurable customer outcomes.

For projects/capstones, reuse the existing six-dimension project rubric (problem understanding, architecture, independent implementation, testing/debugging, security/operations, technical defense); cross-map evidence, but **score competency claims independently**. No single answer, completed tutorial, AI-produced project, time spent, or number of projects confers Mastered.

## Assessment modes
- **Independent Engineering:** learner designs, writes critical code, reasons, tests and debugs without AI generating the assessment answer or implementation.
- **AI-Assisted Engineering:** learner may delegate work but must understand critical paths, verify correctness/security, test, debug and own the result.

Record mode for each evidence item. Do not inflate independent mastery from AI-assisted output. Use varied scenarios, delayed recall/retests and technical defense.

## Capstone integration
Keep existing optional Capstone A (Secure Enterprise AI Platform), B (Real-Time Distributed Systems), and C (Production Engineering & DevSecOps). Do **not** automatically start, mandate all project ideas, or replace prerequisites.

A single appropriately scoped capstone may demonstrate FDSE implementation/integration, FDE discovery/delivery and Applied AI skills; evaluate those dimensions separately. Possible flow: ambiguous business problem → discovery → requirements → architecture → implement/integrate → justified AI components → tests/security → deploy → failure/recovery → measure outcomes → handover. Use a real non-confidential problem or simulation; WS Studio is optional, not required.

## Career readiness dashboard (proposed fields)
| Outcome | Verified competencies | Current weaknesses | Missing evidence | Assessment history | Recommended practice | Confidence | Next mastery gate |
| --- | --- | --- | --- | --- | --- | --- | --- |
| FDSE | None verified in GitHub | Unassessed | Independent coding, debugging, integration, delivery | Historical Issue #1 and current chat checkpoints (not yet committed) | Continue Java foundational practical | Insufficient evidence | Independent implementation |
| FDE | None verified in GitHub | Unassessed | Discovery, delivery, stakeholder outcomes | Historical Issue #1 (unrelated) | Shared foundations | Insufficient evidence | Shared engineering evidence |
| Applied AI | None verified in GitHub | Unassessed | Core AI implementation/evaluation/security | No verified repository evidence | Shared foundations | Insufficient evidence | Core prerequisites |
| AI Infrastructure | None verified in GitHub | Unassessed | Serving/GPU/performance/operations | No verified repository evidence | Shared foundations | Insufficient evidence | Infrastructure prerequisites |

Readiness is not a job guarantee. Do not manufacture percentage scores.

## Continuity and change controls
- Current session remains **Track A Java Foundations**, next practical independent coding in IntelliJ IDEA, following array/reference/pass-by-value chat diagnostics.
- The chat results are **unpersisted provisional evidence**, not permission to alter any historical scores.
- One question/exercise at a time; step-by-step IDE guidance; daily finish line is a flexible stopping point, **not** a course deadline or Mastery shortcut.
- Keep all prior Issues/commits/history. Do not change scores without new verified evidence.
- Review this addendum in a PR before merge. No capstone, project, new lesson, or job-interview syllabus is started by this documentation change.
