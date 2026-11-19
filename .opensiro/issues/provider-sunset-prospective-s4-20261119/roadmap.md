# github/gh-aw — independent provider-future S4 capability roadmap receipt (2026-11-19)

## Identity and pins

- Receipt contract: proposal-gate
- Original repository: github/gh-aw
- Original HEAD: 23cb3c212e3cf577717086194517fa1589eb53d3
- Observed at: 2026-11-19
- Accepted Index assessment: https://github.com/opensiro/vsm-harness-index/blob/c2e43bf4750841277b3e58d8ba80314121734764/assessments/gh/gh-aw.md
- Accepted assessment blob SHA: dbdd8ba4e0456c83d5f2c6acd7e2f1a2a8ec7ad1
- Accepted review ref: ff2eccd10a30d6a7bfaf0da449194e907a206555
- Accepted reviewed at: 2026-09-27
- Accepted Profile version: 0.2.4
- Accepted Skills methodology version: 0.3.6
- Accepted VSM vector: S1=A · S2=C · S3=C · S3*=A · S4=— · S5=P
- System in focus: Public first-party gh-aw compiler and installed repository-level GitHub Actions workflow organization, built-in agent jobs, threat detection, safe outputs, model routing, governance, concurrency, credit forecast and budget guardrails; external GitHub Actions and provider internals excluded
- Fork base commit: 1e0f35fda7eedec0ffc5299e2523885789d14fb0
- Repository-wide source map: README, compiler/model routing and modelsdev, ai-credits and forecast, auto-update workflow, work-queue, threat detection and safe outputs, policy/governance, docs/specs, automated tests, original Issues/PRs and contributor restrictions
- Priority rationale: Historical S1/S2/S3/S3*/S5 already have function owners; only S4 prospective provider transition is a plausible new C target, but present operator evidence and extra decision value beyond native router/fallback/owner upgrade are absent
- Accepted Index commit: c2e43bf4750841277b3e58d8ba80314121734764
- Target transition: NO_QUALIFIED_C_TARGET
- Proposed C construction: NONE selected; potential developer-composed S4 future provider retirement observer and authorized future-workflow migration/hold chooser remains an unqualified hypothesis
- C sufficiency falsifier: Show a dated source-verifiable future provider/model retirement or pricing-policy change that current router, alias fallback and owner upgrade cannot cover, then demonstrate a separately installed lawful chooser, protected apply to later workflow and observed later-run feedback
- Scenario basis: HYPOTHETICAL
- Proposal-stage decision: NO_GO
- Research disposition: NO_USEFUL_CHANGE
- Proposed validation: Compare ordinary alias fallback and router, operator-controlled upgrade/report issue, and a bounded future-retirement candidate on a frozen fixture with later provider turnoff; include no-actor, stale notice, unauthorized change and false retirement controls
- Validation state: NOT_RUN
- Proposal falsifier: Native router/alias or owner-mediated update maintains valid future execution with same cost/authority; proposed actor adds no different legitimate downstream decision
- Result: NO_USEFUL_CHANGE
- External issue: DRAFT — NOT PUBLISHED
- Cost status: NOT_MEASURED
- S1 disposition: Historical A; first-party compiled model-driven agent jobs own task action choices, no extra S1 C needed
- S2 disposition: Historical C; per-run/per-engine concurrency and native queue policies constrain collisions, no extra S2 C needed
- S3 disposition: Historical C; credit/admission limits and run/workqueue control already provided as constructor policy, no new S3 C decision justified
- S3* disposition: Historical A; distinct threat detection evaluates agent artifacts before safe-output writes, independent quality/security audit not regraded
- S4 disposition: Historical —; forecast estimates internal future credit consumption but is not separately empowered prospective environmental intelligence; no qualified new S4 C candidate yet
- S5 disposition: Historical P; repo owner controls purpose, authoritative Markdown body, permission and policy overrides; preserve legitimate parent authority
- P1 dependencies: Original owner-native #79288 model suffix/effort handling, source-backed #78239 provider unavailable model evidence (CLOSED, not adopted as future adaptation), current routing/alias paths, and any actual announced future retirement
- P2 optional: Re-open S4 only with an independently verified future environment change and lower-cost counterfactual test; Index-owned re-review if current function grade is requested

## Rights and authority

The source [MIT license](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/LICENSE) is publicly inspectable. [CONTRIBUTING](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/CONTRIBUTING.md) prohibits traditional external PRs from non-core contributors; community plans belong in original Issues after separate exact current-conversation consent. **No original external Issue/comment/PR is published**, no source, generated workflow or product branch is changed. Correctly parented verified `opensiro-contributions/gh-aw` exists but lacked `opensiro/meta` at intake. This is a NEW case beyond the fixed 23 originals in [Upstream #58](https://github.com/opensiro/upstream/issues/58), not a 24th member of the original denominator. For this new case the #58 owner ACTIVE grant is NOT inherited: bootstrap fork metadata is `attention=DORMANT` and `owner_control=PAUSE` (no inferred RESUME). Only the first permitted metadata bootstrap is made; subsequent fork effects require fresh owner decision. Current original `main@23cb3c212e3cf577717086194517fa1589eb53d3` differs from fork product `main@1e0f35fda7eedec0ffc5299e2523885789d14fb0`; assessment is of original, not stale product fork. No product/default branch edits.

## Existing work / overlap

**Track A — shipped/current original:** [README](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/README.md) describes compiled repo-level AI jobs, with read-only agent and protected safe outputs. [Concurrency](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/docs/src/content/docs/reference/concurrency.md) maps work by issue/PR/ref and engine groups; [native work-queue](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/docs/src/content/docs/reference/work-queue.md) supplies authorized assignments, reservations and completion. [Threat detection](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/docs/src/content/docs/reference/threat-detection.md) runs an independent inspection before privileged outputs; [safe outputs](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/docs/src/content/docs/reference/safe-outputs.md) enforce limited writes. [Model routing](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/docs/src/content/docs/reference/model-routing.md) offers `router/economy|balanced|robust`, shortlists, policy-limited available models and fail-loud if no model qualifies. [Model alias spec](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/docs/src/content/docs/specs/model-alias-specification.md) defines deterministic fallbacks and portability. [Forecast spec](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/docs/src/content/docs/specs/forecast-specification.md) states the stable `gh aw forecast` projects *internal* AI-credit needs, not external model-retirement dates or authority to rewrite workflows. [AI Credits spec](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/docs/src/content/docs/specs/ai-credits-specification.md) defines daily/per-run budget guardrails. [Governance](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/docs/src/content/docs/reference/governance.md) keeps model/credit defaults under parent-controlled repo/org/enterprise configuration. [Auto-upgrade generator](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/pkg/workflow/auto_update_workflow.go) produces opt-in weekly upgrade issue/report behavior, not autonomous strategic authority. [Forecast implementation](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/pkg/cli/forecast_compute.go) and [related tests](https://github.com/github/gh-aw/blob/23cb3c212e3cf577717086194517fa1589eb53d3/pkg/cli/forecast_montecarlo_test.go) exist; NOT_RUN.

**Original-native Issues/PRs:** [#78239](https://github.com/github/gh-aw/issues/78239) CLOSED documents a provider-unavailable configured model; it explicitly notes a local catalog does not prove live Copilot integration availability, and asks operator to choose supported model. [#79288](https://github.com/github/gh-aw/issues/79288) OPEN reports Copilot model `?effort=` suffix passed raw, 502, and wrong transient error attribution — concrete native model/driver correctness. [#78928](https://github.com/github/gh-aw/issues/78928) CLOSED requests top-level router shortlists; [PR #79106](https://github.com/github/gh-aw/pull/79106) and [PR #79117](https://github.com/github/gh-aw/pull/79117) are MERGED, include routing shortlist migration and top-level opt-out. [Model pin inventory #71961](https://github.com/github/gh-aw/issues/71961) CLOSED records one dated provider model-pinning snapshot, not a live autonomous future chooser. [PR #78658](https://github.com/github/gh-aw/pull/78658) MERGED provides delivery/adoption reporting, not a prospective external strategy owner. Shipped, merged, issue-only and prospective are separated; no assumed native EOL detector.

**Track B (independently considered):** (B0) Native model alias/router and operator-controlled `gh aw env update`/workflow update remain the cheapest response to actual current unavailability; no new C. (B1) A repository-authored, scheduled model-retirement notice monitor could use supported GitHub tool reads and safe-output Issue/PR draft, but such an agentic workflow is already composable through the generic framework and issuing a warning or a parent-approved draft does **not** create an additional first-party S4 C constructor. (B2) A new function-specific S4 provider-sunset chooser could, in principle, consume authenticated dated external retirement/price-policy evidence, select `retain/migrate/hold` for not-yet-run work, apply through a bounded existing authorized safe-output/owner route, and use future-run results to correct its environmental model. Current source provides model routing and safe outputs but not a demonstrated need, installed decisive owner, or lawful automatic strategy transition that a cheaper current router/fallback/owner update cannot supply. (B3) Budget forecast from internal usage plus parent-configured limits may be a useful advisory, but absent an external future-environment signal and authority/feedback it is not S4 closure. Neither mere S4 absence nor #79288 current-driver bug qualifies B2.

## Function ownership

| Function | Accepted historical | Current supported source role | Target |
| --- | --- | --- | --- |
| S1 | A | Model-driven agent executes workflows and reacts to tool observations | No C |
| S2 | C | Compile-time concurrency grouping and work-queue collision controls | Existing C |
| S3 | C | Current AI Credits, work admission, runtime limits and delegated safe-output policy | Existing C |
| S3* | A | Separate AI threat detector before scoped writes | Existing A |
| S4 | — | Forecast internal credits, model routing current selection, upgrade advice; no proved external-future closed loop | NO_QUALIFIED_C_TARGET |
| S5 | P | Repository owner holds policy/purpose authority and subsequent run instructions | Legitimate parent |

**Historical** included assessment vector only: `S1=A · S2=C · S3=C · S3*=A · S4=— · S5=P` at https://github.com/opensiro/vsm-harness-index/blob/c2e43bf4750841277b3e58d8ba80314121734764/assessments/gh/gh-aw.md. No new Index grade and no assertion missing S4 is intentional absent source evidence.

## Parallel contribution-on-top review

- Evaluation object: Future provider/model retirement could invalidate a currently configured workflow before its next scheduled run; is a new first-party S4 C constructor warranted over built-in model availability fallback, router and parent workflow edits?
- Existing-work overlap: Native routing, alias/spec fallback, model governance, weekly upgrade report and safe output mechanism; issue #78239 (CLOSED provider unavailability), #79288 (OPEN driver parsing) and merged routing PRs
- Our on-top contribution: None qualified. Candidate B2 is a possible future-retirement monitor plus authorized `retain/migrate/hold` and later feedback, but the operational user delta and independent lawful actor are HYPOTHETICAL
- Incremental benefit: NOT_EVIDENCED versus B0/B1. No proven external future retirement input, prevented failed run, lower cost, novel authority or distinct return
- Decision scope: NO_GO to adding a new first-party S4 C construction now. Native model bug resolution and owner-managed upgrades remain separate

| Functional link | Track A native capability | Track B minimal possible addition | Concrete disproof |
| --- | --- | --- | --- |
| Model unavailable **now** | Router/alias validation and fallback; config override; native #79288 driver correction | NONE new S4 | Existing route selects a permitted model |
| Verified **future** provider retirement | No proven standard proactive feed; owner reviews upgrade reports | Read dated notice, predeclare lawful future choice, protect later-run activation and return status | No dated notice or equal success by owner/native fallback |
| Future credits exceeding budget | Forecast estimates internal usage; daily/per-run guard | Optional planning advice or parent-allowed update | No externally informed alternative nor distinct decision owner |
| Independent write/security review | Agent threat detection and safe-output permissions already exist | Reuse those protections, do not weaken parent | Candidate bypasses protected writes or redefines S5 |

## Capability priority

**P0:** `NO_QUALIFIED_C_TARGET`, scoped `NO_GO / NO_USEFUL_CHANGE`; no new first-party S4 construction qualified at this source. **P1:** owner-native #79288 model suffix/driver correction and model availability workflows; source-pinned compare at the same moment before any future proposal. **P2:** only after a dated prospective external model change and measurable incremental outcome against native router/manual path, revisit smallest function-specific construction; update Index only through Index-owned procedure.

## Implementation options

The cheapest defensible native response is router/fallback plus explicit workflow-author model-policy changes and necessary driver parsing correction. A true additional S4 constructor, were a future positive case demonstrated, would need an opt-in future-environment source reader with provenance and freshness, an autonomous decisive option over lawful future workflow plans, safe-output authority-separated apply or parent-authorized hold, versioned policies and later-run outcome feedback; no predetermined port count. A notice-only bot or forecast-only report is insufficient. Existing parent authority remains untouched.

## Specification and domain alternatives

Profile owns S1-S5 semantics and S4 forward/environmental closure; Skills methodology and Index assessment stay historical. Generic agentic workflow composition may support a domain-specific future-retirement experiment without a new framework constructor; do not turn a hypothetical wrapper into an S4 grade. No normative error in Profile or Skills established. Different recursion (enterprise-wide provider planning) is outside this repo-level boundary.

## Cost experiment

`NOT_MEASURED`. Paired deterministic replay at a frozen source for (a) native router/aliases plus owner upgrade, (b) generic scheduled Issue/PR proposal, (c) hypothetical protected S4 chooser under dated provider-retirement fixture. Compare prior-to-retirement valid successful runs, failed/blocked runs, price/cost, extra model/tool invocations, parent review count, safety negatives, engineering/integration/testing/maintenance. No benchmark execution, native tests or user-outcome measurements claimed.

## Delivery and publication

This first-ever gh-aw Upstream roadmap case is an **additional accepted-Index candidate outside issue #58's fixed cohort of 23 originals** and is explicitly not counted in #58's denominator. Independent source-first six-function and Track A/B verdict was made before any historical case lookup (none found). Owner control for a newly bootstrapped fork remains `PAUSE/DORMANT`, since #58 owner `ACTIVE/ALLOW` covers only the named 23. One-time initial metadata bootstrap is allowed by the new-case provision; no follow-on writes after PAUSE without RESUME. Store Human [issue.md](issue.md) / AI [constructor-sufficiency.md](constructor-sufficiency.md) / canonical receipt [roadmap.md](roadmap.md) on `opensiro/meta` ONLY; no product/default modifications, fork public GitHub Issue, external original Issue/comment/PR, code change or Index regrade. Actual native tests `NOT_RUN`, cost `NOT_MEASURED`; optional Upstream internal status PR may link this case as an extension, not a cohort completion claim.
