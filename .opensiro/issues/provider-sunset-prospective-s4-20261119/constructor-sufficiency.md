# gh-aw — S4 future-provider constructor sufficiency (AI technical companion)

**Target transition:** NO_QUALIFIED_C_TARGET
**Proposal-stage decision:** NO_GO
**Research disposition:** NO_USEFUL_CHANGE

**Human:** [issue.md](issue.md). **Canonical source of truth:** [roadmap.md](roadmap.md).
**PLAN_ONLY / internal metadata, DRAFT — NOT PUBLISHED**, native tests NOT_RUN and cost NOT_MEASURED.

## 1. Source / function boundary

The public original [`github/gh-aw@23cb3c212e3cf577717086194517fa1589eb53d3`](https://github.com/github/gh-aw/commit/23cb3c212e3cf577717086194517fa1589eb53d3) is the actual code boundary. The accepted [Index assessment](https://github.com/opensiro/vsm-harness-index/blob/c2e43bf4750841277b3e58d8ba80314121734764/assessments/gh/gh-aw.md) is historical, reviewed at `ff2eccd10a30d6a7bfaf0da449194e907a206555` on 2026-09-27, `status=included`. The runtime is one repository-level workflow organization built with gh-aw Markdown compiler: model-driven worker S1, native concurrency/queue S2, resource/admission S3, distinct threat detection S3*, developer/owner policy S5; external GitHub Actions and provider/model internal behavior remain environment. Treat future forecasts and model router as present native capabilities, not automatically an S4 autonomous decision owner.

**Disturbance:** HYPOTHETICAL dated future provider model retirement or pricing-policy change, potentially invalidating a future scheduled workflow. Do not substitute an observed *current* unavailability Issue for a dated provider retirement. Candidate actor would observe authenticated independent future notices and decide `retain/migrate/hold` within owner permission for not-yet-executed runs.

**Counterfactual test:** Remove the hypothetical S4 actor but retain model routing, alias fallback, operator-managed env/upgrade, generic scheduled agentic workflows and safe-output authorization. Current source still offers ways to preserve legitimate future run execution or produce a reviewable change. Without a demonstrated distinguishable earlier saved run, another first-party C adds no qualified value.

## 2. Track A: source-native implementation and overlap

- SHIPPED: [model routing](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/docs/src/content/docs/reference/model-routing.md) chooses available model per run, including opt-in tiers and allowed-model shortlist, obeying policy. [Alias spec](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/docs/src/content/docs/specs/model-alias-specification.md) defines version portability and fallback. Both can avoid some current provider choice failures.
- SHIPPED: [credits forecast](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/docs/src/content/docs/specs/forecast-specification.md), [forecast implementation](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/pkg/cli/forecast_compute.go) and [tests](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/pkg/cli/forecast_montecarlo_test.go) predict future *internal usage* from past data; no automatic authoritative prospective model strategy is inferred. [credit guardrails](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/docs/src/content/docs/specs/ai-credits-specification.md) and [governance](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/docs/src/content/docs/reference/governance.md) bound present spend/policy.
- SHIPPED: [concurrency](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/docs/src/content/docs/reference/concurrency.md), [work queue](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/docs/src/content/docs/reference/work-queue.md), [threat detection](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/docs/src/content/docs/reference/threat-detection.md) and [safe outputs](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/docs/src/content/docs/reference/safe-outputs.md) enforce scheduling and protected writes; do not confuse approval with autonomous S5.
- SHIPPED: [auto-update generator](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/pkg/workflow/auto_update_workflow.go) emits scheduled upgrade report/Issue for operator review, not automatic owner-approved future policy changes.
- ISSUE_ONLY: [#79288](https://github.com/github/gh-aw/issues/79288) OPEN Copilot CLI receives URL-style effort suffix as raw model string and fails; remedy must correct engine/alias parsing or fail clearly, not add S4. [#78239](https://github.com/github/gh-aw/issues/78239) CLOSED unavailable configured model incident, with user/editor mitigation.
- MERGED PR: [#79106](https://github.com/github/gh-aw/pull/79106) migrated routed smoke workflows to top-level shortlists; [#79117](https://github.com/github/gh-aw/pull/79117) deprecates nested routing, top-level opt-out. [#78928](https://github.com/github/gh-aw/issues/78928) CLOSED for shortlist use. [#78658](https://github.com/github/gh-aw/pull/78658) MERGED for delivery/adoption reporting, not a prospective environmental controller.
- Original [CONTRIBUTING](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/CONTRIBUTING.md) explicitly bars non-core external direct PRs; no original publication is planned.

## 3. Separate Track B — at least three genuine paths

| Option | Native components and smallest edit | Legitimate owner / decisive choice and feedback | Why not selected |
| --- | --- | --- | --- |
| B0: unchanged router/manual | Model router, alias fallback, owner-managed env and upgrade Issue | Existing policy picks permitted current model; owner changes source for later run | Baseline already covers current availability and common upgrade |
| B1: generic scheduled agent | Agentic Markdown workflow, GitHub reads, safe-output create Issue/PR | A developer-created agent summarizes planned retirement to human; parent decides write | Already generically composable; notice-only no new first-party S4 C |
| B2: function-specific prospective S4 chooser | External dated lifecycle evidence reader + native router/alias frontmatter and protected safe-output/hold callback + future-run feedback collector | Developer installs an independent future intelligence actor; bounded model migration/retain/hold chosen before retirement, enforced only under configured authority, later run status returns to strategy | No observed dated future signal or extra user result beyond B0/B1; absent actor/authority negative tests and cost comparator |
| B3: budget forecast→policy | Forecast CLI, AIC guardrails, organization GH_AW_DEFAULT_* variables | Forecast advisory to parent (or separately authorized future budget planner) | Internal spend history alone is not external-prospective S4, and parent action cannot be relabeled autonomous S4 |

**Most plausible complete C (B2):** require independent timestamped external provider announcement and provenance; resolve impacted workflow/model IDs with current alias/routing policy; let a developer-composed S4 actor choose `retain/migrate/hold` among lawful alternatives; stage a version-pinned change or hold through existing safe-output authorization; persist action receipt; on the next scheduled workflow receive actual provider/model/run evidence and correct later strategy. Generic callbacks or detection logs alone fail the function. Its physical port count is not fixed. The **decisive missing constraint** is a reproduced real incremental user benefit and authorized new strategy owner beyond the shipped route; not proven. Therefore no GO/Index regrade.

## 4. Verification and falsifier (proposed, NOT_RUN)

1. Freeze original `23cb3c212e3cf577717086194517fa1589eb53d3`, model catalogue, alias policy, synthetic provider retirement calendar, real-but-nonsecret workflow fixtures and engine configuration. Do not treat mocked notification as actual official provider EOL.
2. Baseline A: native fallback/router and owner-reviewed auto-upgrade on same fixtures; measure protected later-run availability, error reason, policy change and operator actions.
3. Candidate B: instantiate one bounded S4 chooser only if genuine future notice and capability grant exist; choose among retain/migrate/hold; assert diff/hold is authorized, not auto-bypassing safe-output and owner. Capture first subsequent run result.
4. Negative tests: stale/forged notice, no independent actor installed, revoked or insufficient authorization, alias/engine mismatch, old workflow revision, nonexistent replacement model, conflicting policy, budget failure and next-run failure. No unsafe silent fallback.
5. Calculate incremental pre-retirement avoided failure and total tokens, run time, developer/test/review/maintenance effort. The expected savings and differences are **UNKNOWN/NOT_MEASURED**.
6. A source-backed operator need not solved by B0/B1, with a verified separate decisive future actor and observed later feedback, would falsify this scoped NO_GO. If B0/B1 suffice, reject new S4 constructor.

## 5. Permissions, status and research route

No accepted assessment result changed. The matched fork lacked `opensiro/meta`; this initial owner-selected new roadmap case is bootstrapped under `PAUSE/DORMANT`, **not** #58 cohort ACTIVE. After initial bootstrap, no subsequent .opensiro edits absent explicit RESUME. Original `github/gh-aw` policy requires issues/plans, and all external/public original or fork Issue/PR actions need exact current-conversation consent. Source code, runtime tests, empirical cost data, original communications and public fork Issues are NOT produced by this research. There is no prior gh-aw OpenSiro case to compare; #58's existing 23 remain separate.
