# Journey & Lessons: From Prototypes to Evidence-Governed AI

**Kevin Fitzgerald · Portfolio review, November 2026**

My portfolio spans **81 GitHub repositories**—**69 original projects and 12 forks**—across applied AI, statistical modeling, full-stack products, content production, and infrastructure. This is a record of iterative development, not 81 finished or independently commercialized products. Some implementations are private, some are experimental, and some operate in production with outstanding acceptance work.

## 1. How the work evolved

| Phase | Approximate period | What changed | Main lesson |
| --- | --- | --- | --- |
| **Build products** | Late 2024–2025 | Tarot/astrology applications, personalized celebrations, music-community products and foundational full-stack systems | Shipping features is easier than maintaining coherent product behavior across applications. |
| **Build intelligent workflows** | 2025 | Agent orchestration, retrieval experiments, hypothesis evaluation, causal-analysis and reinforcement-learning prototypes | Autonomous-looking output is not the same as correct decisions or trustworthy action. |
| **Build production factories** | 2026 | Content engines, Story Foundry, Campaign Foundry, digital-product and deck-generation workflows | Quality has to be enforced in the pipeline; a strong prompt is not a quality gate. |
| **Build the trust layer** | 2026 | Enterprise Conductor, a Git workflow harness, desired-state operations and Revenue OS governance | The hardest operating question becomes: *what can we actually prove happened?* |

Across these phases, the focus moved from **generating artifacts** to **creating verifiable systems that generate, review, distribute and learn from them**.

## 2. Problems that changed the architecture

### Many repos, one operating picture

Early experimentation created multiple generations of applications, tools and forks. A repository count is useful as historical context but a poor measure of finished work.

**Response:** classify original work versus forks; make ownership, deployment state and acceptance criteria explicit; prioritize a shared operating view instead of inflating the number of products. Forks are study/tooling inputs, not claimed as original authorship.

### Agents saying “done” without an external result

Code, plans, generated assets and approval messages often look complete before downstream services confirm the intended behavior.

**Response:** require evidence of the relevant state: tests for code, rendered files for media, server-side receipt for a release, and provider-side confirmation for publication. A successful tool invocation cannot replace external readback.

### Retries repeating a permanent failure

A missing prerequisite or expired authorization can be incorrectly treated as transient. Blind retries amplify load and noise.

**Response:** classify errors, impose bounded retries, use stable incident identities, record actionable outcomes and stop on non-transient conditions. Make the diagnosis a new test or operational rule.

### Creative assets drifting from their story

A beautiful image can be the wrong image. The script, visual, motion and product call-to-action can conflict even when each artifact is individually polished.

**Response:** represent editorial rules as versioned configuration; test semantic alignment across components; capture exact revision identity for approvals; introduce explicit rejection and repair loops.

### Infrastructure changes drifting after release

Manual fixes can repair one incident while leaving the system unrepeatable.

**Response:** use desired-state definitions, idempotent convergence, functional canaries and release receipts. Code in a repository is not automatically installed software; running software is not automatically a successful user journey.

### Model and session continuity

Agents working across long-running efforts can lose context or repeat stale conclusions.

**Response:** persist canonical records, checkpoint documents, decision history, task ownership and handoff requirements. Re-read live state at the next session; do not treat an old narrative as a live receipt.

## 3. What “adaptive learning” means in this portfolio

It means **feedback changes subsequent action under explicit control**, not that every project continuously retrains a frontier model.

**Implemented patterns**
- **Evaluation-to-regression:** failure cases become reproducible fixtures, tests and acceptance checks.
- **Human approval feedback:** review outcomes alter creative/reference selection and quality thresholds in subsequent generation attempts.
- **Postmortem-to-policy:** recurring operational incidents are converted into deterministic rules and runbooks.
- **Evidence-based prioritization:** records of research, approvals, publication and observed outcomes can inform which opportunity or workflow receives attention next.
- **Versioned context:** decisions and task receipts survive a model/session restart rather than relying on conversation memory.

**Experimental/research work**
- Causal-analysis workflows for understanding why hypotheses succeed or fail.
- Reinforcement-learning techniques, including PPO-based threshold experiments, explored in Sentient Venture Engine.

**Not yet proven as a closed-loop result**
- A demonstrated online RL policy that improves measured commercial outcomes.
- Reliable end-to-end signal-to-sale attribution across the entire Revenue OS stack.
- Fully automatic cross-channel publication and quality recovery in every intended route.
- A public, reproducible benchmark proving the quality improvement of every model or agent change.

Those distinctions matter: exploratory algorithms, operating software and demonstrated business results are separate levels of evidence.

## 4. Eight reusable playbooks

### A. Observe → choose → act → verify → record

Specify the decision, execute the smallest change, inspect the result, and record what actually changed. Repeat only when new evidence warrants it.

### B. Classify evidence, not confidence

Distinguish **proved**, **weakly supported**, **contradicted**, and **not checked**. Avoid wording that promotes proposed, staged or locally tested work into production facts.

### C. Source control with an acceptance receipt

**Preflight → implement → validate → review → commit → sync → verify → receipt.** Record explicit files, checks, SHA, destination and the remaining uncertainties. A commit is not a deployment.

### D. Schema-first workflows

Define an artifact contract and fixtures before connecting workers or providers. Validate output before it can enter downstream systems.

### E. Gates instead of prompting alone

Move high-consequence conditions from natural-language requests into versioned checks: permissions, required media, approval state, data constraints and action limits.

### F. Deterministic operations

Use desired state, repeatable convergence, canaries, backoff and bounded remediation. A model can assist diagnosis, but reliable routine operations should not require subjective LLM decisions.

### G. Handoff-ready engineering

Write the brief, architecture, acceptance criteria and status so another engineer—or a different model session—can reproduce the next step without reconstructing weeks of context.

### H. Stop intelligently

Do not endlessly retry a missing resource, overwrite a protected change, or claim completion from an incomplete action. Preserve the evidence and continue with the smallest authorized repair path.

## 5. Current state, without marketing inflation

| Area | What exists | Work still ahead |
| --- | --- | --- |
| **Products** | Multiple Next.js/TypeScript applications and AI/data features | Complete end-to-end user-journey acceptance across all key flows |
| **Analytics & Revenue OS** | Opportunity records, scoring/lifecycle structures, dashboard and integration code | Reliable downstream conversion, outcome joins and attribution evidence |
| **Social and campaign systems** | Story and campaign contracts, media processing, QA and approval patterns | Consistent published outcomes and verified distribution across providers |
| **Deck and product factories** | Generation, compositing, QA workflows and asset pipelines | Release-ready integration and consistent final acceptance of deliverables |
| **Trust / governance** | Conductor, source-control harness, operating policies and receipts | Broader repository enforcement, independent review and reproducible public examples |
| **Operations** | Declarative control-plane design and implementation with canaries | Ongoing live validation, controlled rollout and recovery testing |

I value being explicit about this because the gap between **implemented**, **tested**, **deployed**, **accepted**, and **commercially proven** is exactly where expensive engineering mistakes happen.

## 6. Skills this work demonstrates

**Data science:** research design, KPI systems, NLP, predictive modeling, causal reasoning, experimentation and quantitative evaluation.

**Applied AI engineering:** RAG/retrieval patterns, LLM orchestration, tool-connected agents, evaluation, guardrails, persistent decision state, and practical integration.

**Content systems:** research-grounded creative strategy, production-grade media pipelines, multi-brand editorial policy, repeatable QA and release workflows.

**Product and infrastructure:** Next.js/React/TypeScript, Python/SQL, Supabase/Postgres, API/webhook integrations, workflow orchestration, declarative operations and incident handling.

My earlier work at **IBM/Kenexa, Cox Communications, Arbitration Forums and ADP** established the statistical and stakeholder foundation. The current portfolio shows what happens when I apply the same analytical discipline to software, autonomous workflows, creative production and operational control.

## 7. Next public proofs

1. Publish a small source-available evidence/receipt validator with test fixtures.
2. Publish a sanitized contract-first campaign or document pipeline.
3. Release an agent-evaluation case study with negative cases and measured pass/fail criteria.
4. Document a reproducible deployment/canary/rollback exercise with private details removed.
5. Add outcome benchmarks as real evidence becomes available, without using repository counts as success metrics.

The aim is not to appear to have solved every problem. It is to make **how I define, build, test and improve systems** visible and reusable.

**See also:** [Technical Overview](TECHNICAL-OVERVIEW.md) · [GitHub profile](../README.md)
