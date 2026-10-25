![MAAI Project cover — multi-agent AI, volatile time-series charts and connected data networks](assets/maai-cover.webp)

<h1 align="center">MAAI Project</h1>

## Multi-Agent AI<br><small>for Time-Series Data Analytics, Decision-Making, Automation &amp; Execution</small>

**MAAI is an independent research and engineering project building adaptive, reliable multi-agent intelligence for complex time-series data, with brain and mind research as its ultimate long-term scientific goal.** Its first proving ground is the financial market: a changing, high-feedback environment in which agent coordination, analytical reasoning, decisions, risk boundaries, and controlled actions can be engineered and evaluated against measurable outcomes. The ambition is to evolve a reusable intelligence architecture that can later support specialized research on brain signals (EEG), neural dynamics, and cognition.

**Financial markets are the technical evolution environment, not the final destination.** Market-specific strategies, portfolios, and trading execution are the first domain implementation. The intended reusable core is time-series processing, multi-agent orchestration, evidence-based reasoning, evaluation, and governed improvement. Transfer into neuroscience will require new models, scientific expertise, datasets, and independent validation.

**Current status:** The defined architecture and engineering foundation workstreams have reached their foundation closeout milestones. End-to-end integration and operational validation are still in progress. **MVP-1 and MVP-2 are not accepted; a production-ready autonomous trading platform, proven profitability, and live-capital authorization have not been established.** No EEG or brain-research system is claimed to exist today.

This repository presents the public purpose, phased roadmap, and evidence-backed engineering status. The implementation remains private.

---

## 1. What MAAI Is Designed to Do

MAAI is designed to connect four capabilities as a reusable intelligence workflow, initially implemented and tested in the financial domain:

| Capability | What it means in practice |
| --- | --- |
| **Time-series analytics** | Convert timestamped observations and context into traceable patterns, features, anomalies, and estimates of uncertainty. Financial signals are the first implementation; neural signals are a future, separate research domain. |
| **Decision intelligence** | Compare candidate actions or interpretations against evidence, constraints, and uncertainty. Choosing **not to act** remains a legitimate result. |
| **Multi-agent automation** | Coordinate specialized analysis, research, validation, and operational workflows with monitoring and human oversight. |
| **Governed execution** | Perform only explicitly authorized domain-specific actions, preserve factual outcomes, and account for costs, delays, errors, and other real-world constraints. Research interpretations do not by themselves authorize consequential action. |

The intended feedback-and-improvement cycle is:

~~~text
Time-series observations + context
              ↓
Specialized agent analysis and competing hypotheses
              ↓
Evidence-based decision + constraints + authorization
              ↓
Bounded action or deliberate no-action
              ↓
Observed outcomes + independent evaluation
              ↓
Versioned, tested improvements → next evaluation cycle
~~~

The long-term design separates a **domain-extensible intelligence core** from **domain-specific adapters**. Financial-market strategies, portfolio accounting, risk rules, and order execution belong to the financial adapter; future EEG ingestion, preprocessing, and neuroscience research methods would require their own specialized adapter and validation.

**Why multi-agent AI?** Specialized agents may eventually cooperate, challenge one another's interpretations, and improve decision quality across the workflow. That is a **runtime architecture objective**, not a claim that an autonomous, self-improving team of agents operates today.

## 2. Financial Markets as the First Agent-Evolution Environment

Financial markets are MAAI's **initial real-world engineering laboratory**, not its ultimate research destination. They offer time-stamped data, changing conditions, uncertainty, consequential decisions, and outcomes that can be evaluated against explicit baselines.

The environment supports three linked engineering objectives:

1. **Stress-test the system:** challenge data pipelines, specialized agents, coordination, risk boundaries, and operational reliability under changing conditions.
2. **Collect measurable feedback:** distinguish forecasts and intended actions from observed data, simulated or permitted execution events, transaction costs, delays, failures, and actual results.
3. **Drive controlled evolution:** use evaluated evidence to propose changes, then replay, compare, validate, version, and approve improvements before deployment.

The financial implementation therefore includes market data, strategies, portfolio and risk logic, execution infrastructure, and evidence-based evaluation. Meaningful assessment must include **fees, slippage, liquidity, latency, failures, regime changes, and out-of-sample uncertainty**—not just encouraging backtest results.

**Feedback is not the same as autonomous learning.** Real-time observation is an intended capability; any change to models, policies, or agent behavior must be subject to independent tests and explicit governance. The initial path is historical data, replay, and authorized non-production workflows. Live-capital activity requires a separate permission and safety gate, and **is not currently authorized**.

MVP-2 retains a distinct **economic-validation gate** to test the financial-domain implementation against realistic risk-adjusted outcome evidence. This is an engineering acceptance criterion, not a declaration of profitable operation or the project's ultimate scientific purpose.

## 3. Phased Roadmap and Verified Status

The roadmap has **two connected horizons**: first, build and rigorously evaluate the intelligence core in a demanding financial-market environment; later, extend it through independent research toward brain and mind science. These are planned stages, **not percentages of total completion**. Long-term scientific goals do not imply an existing neuroscience implementation.

| Phase | Status | Objective and evidence boundary |
| --- | --- | --- |
| **Phase 1 — Architecture and engineering foundations** | **Foundation closeout reached** | Establish the five engineering foundation workstreams; this is not an integrated or accepted product. |
| **Phase 1.5 — System integration and operational evidence** | **Active** | Connect real data, analytical decisions, risk and permission checks, bounded execution, factual state, and evaluation. |
| **Phase 2 — Real-world feedback and reliability** | **Not entered** | Strengthen monitoring, reproducibility, resilience, data quality, and controlled feedback under increasingly realistic conditions, subject to acceptance gates. |
| **Phase 3 — Controlled agent evolution** | **Future roadmap** | Investigate versioned, measured, reversible improvements to agent coordination, analysis, and decision policies without uncontrolled self-modification. |
| **Phase 4 — Domain-extensible intelligence** | **Future roadmap** | Separate reusable time-series, orchestration, evidence, and learning infrastructure from financial-specific adapters; evaluate portability rather than assume it. |
| **Phase 5 — Neural-signal research foundation** | **Long-term research goal** | Develop and independently validate domain-specific EEG preprocessing, multichannel analysis, neural time-series models, and research workflows. |
| **Phase 6 — Brain and mind research** | **Ultimate research goal** | Explore scientifically grounded applications to neural dynamics and cognitive research, using appropriate datasets, expertise, ethics, and reproducible evaluation. |

**MVP acceptance gates remain separate from the phases:**

| Gate | Current status | What must be shown |
| --- | --- | --- |
| **MVP-1 — Operational integration** | **Not accepted** | A measured end-to-end workflow, including authorized non-production execution and factual outcome evaluation. |
| **MVP-2 — Financial-domain economic validation** | **Not accepted** | Robust risk-adjusted outcome evidence under realistic assumptions, after MVP-1. Neither paper results nor architecture closeout prove profitable live operation. |
| **Production / live-capital authorization** | **Not established** | Separate evidence, risk controls, approvals, and explicit permission; it is never inferred from MVP status alone. |

The five Phase 1 engineering workstreams are:

| Workstream | Foundation focus |
| --- | --- |
| **EPIC 1** | Market data and intelligence |
| **EPIC 2** | Strategies and decision systems |
| **EPIC 3** | Execution infrastructure |
| **EPIC 4** | Portfolio and risk management |
| **EPIC 5** | Execution orchestration, factual state, evaluation, safety, and permission controls (architecture closeout through 5.24) |

**These are engineering foundation milestones, not percentages of overall project completion.** They do not prove a complete runtime multi-agent system or readiness for clinical, production, or live-capital use.

### Project Progress — Visual Snapshot

The bars indicate **milestone state, not percentage completion**: filled bars denote defined foundation closeout; the partly shaded bar marks the active integration transition; empty bars represent work that has not entered its stated stage.

**Engineering and research phases**

~~~text
MAAI — Engineering & Research Roadmap

Phase 1   — Engineering Foundations .............. FOUNDATION CLOSED     ████████████████████
Phase 1.5 — Integration & Evidence ................ ACTIVE TRANSITION     ██████████████▒▒▒▒▒▒
Phase 2   — Real-World Feedback & Reliability .... NOT ENTERED           ░░░░░░░░░░░░░░░░░░░░
Phase 3   — Controlled Agent Evolution ........... FUTURE ROADMAP        ░░░░░░░░░░░░░░░░░░░░
Phase 4   — Domain-Extensible Intelligence ....... FUTURE ROADMAP        ░░░░░░░░░░░░░░░░░░░░
Phase 5   — Neural-Signal Research (EEG) ......... LONG-TERM GOAL        ░░░░░░░░░░░░░░░░░░░░
Phase 6   — Brain & Mind Research ................ ULTIMATE GOAL         ░░░░░░░░░░░░░░░░░░░░
~~~

**Phase 1 engineering foundations (EPICs)**

~~~text
EPIC 1 — Market Data & Intelligence .............. FOUNDATION CLOSED     ████████████████████
EPIC 2 — Strategy & Decision Layer ............... FOUNDATION CLOSED     ████████████████████
EPIC 3 — Execution Layer ......................... FOUNDATION CLOSED     ████████████████████
EPIC 4 — Risk & Portfolio Layer .................. FOUNDATION CLOSED     ████████████████████
EPIC 5 — Execution Plane, Evaluation & Live Gate . ARCH. CLOSEOUT 5.24   ████████████████████
~~~

**MVP and operational gates**

~~~text
MVP-1 — End-to-End Operational Integration ....... ACCEPTANCE NOT ESTABLISHED
MVP-2 — Financial Economic Validation ............ ACCEPTANCE NOT ESTABLISHED
Production / Live-Capital Authorization .......... NOT ESTABLISHED
EEG / Brain-Research Implementation .............. NOT STARTED / NOT CLAIMED
~~~

Phase progression depends on its own evidence and validation. **Market-domain progress does not establish neural-domain capability**: EEG and cognition research require fundamentally different data, methods, expertise, and scientific review.

## 4. What I'm Working on Now

The immediate priority is **integration before adding more features**. Work is concentrated on the financial-market implementation as the first evidence-producing environment:

1. **Connect** market inputs, time-series analytics, agent and decision interfaces, risk and permission checks, execution planning, and evaluation into a coherent workflow.
2. **Exercise and measure** that workflow using historical replay and authorized non-production conditions, including realistic failures, market changes, and trading costs.
3. **Verify the results** against factual records and explicit acceptance criteria before claiming MVP-1 completion.
4. **Prepare the feedback discipline** needed for later agent evolution: baselines, independent evaluation, recorded experiments, and governed changes.

MVP-2 is a **separate financial-domain economic-validation gate**, not proof that the core architecture is already ready for cross-domain transfer. Research phases involving EEG and cognition remain future objectives and do not displace present integration priorities.

## 5. Engineering Snapshot

<small>Measured **17 October 2026** from a fixed internal source snapshot, using **cloc 2.10** on Git-tracked files with documented exclusions. These are historical measurements, not a live repository counter.</small>

| Measure | Verified snapshot |
| --- | ---: |
| Physical lines (including comments and blank lines) | **1,278,820** |
| cloc-classified code lines | **1,088,258** |
| Git-tracked files | **7,726** |
| Files counted by cloc | **7,573** |
| Scoped PKR tests passing on Python 3.12 and 3.13 | **255 distinct tests** |

**How to read these numbers:** The cloc “code” category includes Python, JSON, Markdown, and other recognized content. It does **not** mean 1.09 million lines of executable software. The 255 tests are the same scoped tests passing in **both** Python environments; this does not establish a full-project test-suite pass or end-to-end operational readiness.

### Repository Content Mix

| Content type | Counted files | cloc code lines |
| --- | ---: | ---: |
| Python | 2,599 | 784,669 |
| JSON | 4,285 | 209,161 |
| Markdown | 681 | 93,718 |
| Other | 8 | 710 |
| **Total** | **7,573** | **1,088,258** |

~~~text
Python    72.10%  ██████████████████░░░░░░░
JSON      19.22%  █████░░░░░░░░░░░░░░░░░░░░
Markdown   8.61%  ██░░░░░░░░░░░░░░░░░░░░░░░
Other      0.07%  ▏
~~~

The full engineering records, measurement provenance, and detailed implementation remain private. The numbers describe the **scale of the engineering work**, not product maturity, test coverage, or financial performance.

## 6. How I Approach the Engineering

- **Evidence before claims:** A design, implementation, passing test, integrated workflow, validated outcome, and scientific finding are different milestones.
- **Safety and permissions:** AI suggestions do not automatically authorize market execution, clinical interpretation, or any other consequential action. Human oversight and the ability to stop operations remain central.
- **Continuous observation, controlled adaptation:** New feedback can trigger hypotheses and experiments; deployed behavior changes only after reproducible testing, review, and explicit approval.
- **Realistic domain evaluation:** Market decisions face trading costs and regime changes; future neural-signal analysis will face sensor artifacts, subject variability, and scientific reproducibility requirements.
- **Portability by design, not assumption:** Domain-specific data pipelines and actions must remain separable from reusable orchestration, analytics, evidence, and evaluation capabilities.

## 7. North Star — Brain and Mind Research

**The ultimate research direction of MAAI is brain and mind science.** The intent is to develop a sufficiently reliable, adaptable multi-agent intelligence architecture that can eventually support research on EEG, neural dynamics, and cognitive processes. This is a defined **long-term objective**, not an exploratory footnote or a claim of scientific results achieved today.

Financial markets provide the first technical setting in which to develop and scrutinize the underlying system. The planned progression is:

1. **Build and integrate an evidence-driven intelligence system** in the financial domain (Phases 1 and 1.5, with distinct MVP gates).
2. **Strengthen reliability and improve agents through governed feedback** from measurable, changing market conditions (Phases 2 and 3).
3. **Make the core genuinely reusable** by testing what transfers across domains and what requires redesign (Phase 4).
4. **Establish a specialized neural-signal research capability** with multichannel EEG data, artifact handling, signal processing, and subject-aware evaluation (Phase 5).
5. **Pursue brain and mind research questions** through collaborations, neuroscience methods, transparent hypotheses, and reproducible study designs (Phase 6).

The underlying **time-series and multi-agent infrastructure may be reusable**; trained market models, trading strategies, portfolio rules, and order-execution logic are **not EEG models** and will not be treated as such.

Future EEG and cognitive research must address sampling and channel structure, recording artifacts, inter-person variability, dataset consent and privacy, experimental validity, and specialist scientific oversight. Any potential diagnostic or clinical application would require separate medical evidence, appropriate regulation, and authorization. **MAAI does not claim to diagnose conditions, infer thoughts, or analyze brain data today.**

This research horizon gives the current engineering program a larger purpose while keeping the financial-market implementation measurable, concrete, and honestly described.

## 8. Multi-Agent Architecture and Responsibilities

MAAI is designed around **cooperating specialist functions**, not one model making every decision. The intended runtime system should allow agents to examine evidence, challenge conclusions, and recommend actions while factual records, risk controls, and permissions remain explicit and independently verifiable.

| Specialist function | Intended responsibility |
| --- | --- |
| **Time-series and data integrity** | Check source, timing, completeness, channel or series consistency, and provenance of inputs. |
| **Analysis and contextual reasoning** | Compare temporal patterns, changes, anomalies, uncertainty, and competing explanations. |
| **Domain-specific decision support** | Apply relevant objectives and constraints: currently strategies, portfolios, and market risks; future research domains would require different scientific methods. |
| **Safety, policy, and authorization** | Distinguish recommendations, evidence, and permissions; identify unsafe or unsupported actions. |
| **Bounded execution and observation** | Plan and record actions only where separately authorized; measure observed outcomes rather than assumed outcomes. |
| **Critique, evaluation, and research** | Challenge assumptions, reproduce experiments, compare baselines, investigate failures, and propose testable improvements. |

An essential rule is that **an agent's suggestion is neither a verified fact nor authorization to act**. State, evidence, approvals, and operator control need separate accountable boundaries. In neural research, the primary outcome may be a validated interpretation or experiment—not an executable market action.

**Maturity distinction:** The development process already uses structured human–AI collaboration with separated responsibilities. This differs from a fully integrated autonomous team of **runtime** agents; that remains an architectural objective.

## 9. Time-Series Data, Analytics, and Contextual Intelligence

MAAI's intended shared analytical foundation connects **time-stamped observations** with the context needed to interpret them. Decisions and scientific interpretations depend on source, timing, completeness, consistency, and uncertainty—not on model sophistication alone.

The **current financial-market engineering and research scope** includes:

- **Market data foundations:** historical, representative, and eventually appropriate live inputs; validation, normalization, timestamps, and provenance.
- **Technical and quantitative analysis:** price action, volume, trends, volatility, momentum, patterns, statistics, and multi-timeframe or cross-asset comparisons.
- **Condition-aware research:** market regimes, anomalies, uncertainty, and testing when an indicator or strategy works and when it breaks down.
- **Fundamental and macro context:** possible integration of financial, economic, news, and other external evidence where data quality and research justify it.
- **Reliable knowledge and feedback:** traceable features, experimental history, baselines, and outcome records that support controlled improvement.

The **future shared-core research direction** includes domain-independent temporal features, agent coordination, experiment lineage, uncertainty representation, and independent evaluation. A neural-signal adapter would additionally require EEG-specific acquisition or datasets, sampling rates, channels and electrode layout, filtering, artifact management, and specialist interpretation.

These are **research and architecture directions**, not a claim that all market inputs or any EEG analytical pipeline already operate as an integrated system.

## 10. Financial-Domain Strategy, Portfolio, and Decision Intelligence

Within the financial test environment, the goal is to move beyond isolated trading signals toward **inspectable decisions**. This is one domain-specific application of MAAI, not the definition of its long-term scientific purpose. A proposed action needs more than a model prediction: it needs assumptions, supporting evidence, confidence or uncertainty, and an explanation of the relevant constraints.

The intended decision layer supports strategy comparison and selection, combinations of approaches, and responses to changing market regimes. Portfolio reasoning brings in position sizing, capital allocation, risk budgets, diversification, concentration, and correlation.

A proposed decision can lead to different outcomes:

1. **Proceed to review:** the idea has enough evidence to be evaluated against risk and policy constraints.
2. **Revise or investigate:** uncertainty, conflicting information, or portfolio effects require more work.
3. **Do nothing:** choosing **no trade** is a deliberate outcome when conditions do not justify action.

**Decision, risk clearance, approval, and execution are separate steps.** A strong backtest or an AI recommendation alone does not establish permission to place a real order.

## 11. Financial-Domain Execution, Safety, and Operational Truth

In the financial-domain implementation, execution means more than sending an order. The target execution plane connects approved intent to observable results through planning, orchestration, permissions, runtime behavior, and reconciliation. These trading mechanics are domain-specific; the reusable principle is bounded action with independently observable outcomes.

A controlled execution flow must distinguish:

- **Requested action** from policy checks, approval, and actual authorization.
- **Execution intent and order state** from fills, partial fills, rejection, cancellation, and failure handling.
- **Expected performance** from realized costs such as spreads, fees, slippage, liquidity, and latency.
- **Internal assumptions** from factual events, records, and measured outcomes.

The architecture includes risk and authority boundaries, revocation, observability, recovery, and auditability. Its purpose is to make consequential actions **bounded, traceable, and interruptible**, with human oversight where required.

The project's fifth engineering workstream covers execution planning, orchestration, canonical state and evidence, evaluation, and controlled-live gate models, with architecture closeout through Sub-Epic 5.24. **That foundation does not prove end-to-end operational acceptance, production readiness, or authorization for live-capital trading.**

## 12. Evaluation, Reliability, and Controlled Agent Evolution

**Continuous feedback is the input to research, not permission for automatic self-modification.** MAAI must distinguish what actually happened from what an agent, model, or simulation expected. The financial environment is intended to provide measurable evidence for debugging, comparison, and—after independent verification—controlled improvements to the intelligence core.

| Evidence area | What needs to be established |
| --- | --- |
| **Testing and replay** | Reproducible behavior, correct state transitions, and realistic failure handling. |
| **Simulation and backtesting** | Disclosed assumptions, costs, limitations, uncertainty, and appropriate baselines. |
| **Non-production operation** | Connected data-to-action-to-evaluation workflows with factual outcomes, without implying live-capital permission. |
| **Economic evaluation (MVP-2)** | Robust out-of-sample and risk-adjusted financial-domain results under realistic assumptions; no inference of guaranteed income. |
| **Feedback quality** | Evidence that outcomes are correctly attributed, measurable, and not merely noise, leakage, or changing evaluation criteria. |
| **Governed change control** | Explainable, versioned, reviewable, reproducible, and reversible model, agent, and policy changes; detection of drift or degradation. |
| **Future scientific transfer** | New-domain baselines, independent datasets, validated measurements, research ethics, and scientific reproducibility before claiming EEG or cognitive findings. |

Reliability includes recovery, reconciliation, idempotent processing, least-privilege access, operator control, and the ability to explain **which data, decision, configuration, constraint, and event** contributed to an outcome.

The financial acceptance gates remain distinct: **MVP-1** requires verified operational integration; **MVP-2** requires separate economic validation. Neither is accepted in the public engineering snapshot. **No level of market-domain validation alone establishes successful neuroscience transfer.**

## 13. About This Repository and the Author

This is the **public overview of MAAI Project (Multi-Agent AI)**. It documents the project's long-term brain-and-mind research objective, its financial-market engineering test environment, its phased roadmap, and verified progress—not the private core source code or operational infrastructure.

**Majid Askary** — software engineering, systems architecture, applied AI research, and data-driven automation.

[LinkedIn](https://www.linkedin.com/in/majidaskary) · [Contact](mailto:m.askary84@yahoo.com)

## Disclaimer

MAAI is an ongoing research and engineering project, **not** an investment advisory service, clinical product, or medical diagnostic system. Its goals and architecture are not claims of guaranteed returns, production deployment, autonomous trading readiness, authorization for live-capital execution, or validated EEG, cognitive, or medical findings.
