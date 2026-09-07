# Feature status — Governance, privacy & compliance

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 220 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 0 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 1 | 0 | Native records/view |
| Deadlines & reminders | records | 2 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 0 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 0 | 0 | Native records/view |
| Reports & analytics | report | 2 | 0 | Native records/view |
| Activity & audit trail | audit | 4 | 0 | Native records/view |
| Provider connections | integration | 0 | 0 | Provider request records only |
| Agent governance control tower work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Board governance briefing assistant work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product compliance evidence vault work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Regulatory change impact mapper work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Governance | records | 1 | 0 | Native records/view |
| Regulations | records | 2 | 0 | Native records/view |
| Assessments | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Alerts | records | 2 | 0 | Native records/view |
| Analyze | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Gap | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Policy | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| History | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Chat | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Backlog tools | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Control attestation queue | records | 1 | 0 | Native records/view |
| Data contract monitor | records | 1 | 0 | Native records/view |
| Sanctioned entities | records | 1 | 0 | Native records/view |
| Denied parties | records | 1 | 0 | Native records/view |
| Restricted countries | records | 1 | 0 | Native records/view |
| Controlled items | records | 1 | 0 | Native records/view |
| Transactions | records | 1 | 0 | Native records/view |
| Export licenses | records | 1 | 0 | Native records/view |
| Compliance documents | records | 1 | 0 | Native records/view |
| Restricted end uses | records | 1 | 0 | Native records/view |
| Screening results | records | 1 | 0 | Native records/view |
| Screen entity | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Denied party search | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sanctions analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Screening review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Classify item | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dual use check | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Eccn lookup | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Assess transaction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transaction patterns | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Red flag detect | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Route analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Country risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Embargo impact | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| License recommendation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| License monitor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Review document | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| End use analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate report | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compliance gaps | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Penalty risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vsd advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Audit analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Regulatory updates | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Training generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bulk screen | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compliance alert dashboard | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transaction auto screen | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Beneficial ownership analyze | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supply chain trace | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Training simulate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Competitor benchmark | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| License exception audit | records | 1 | 0 | Native records/view |
| Missing features | records | 2 | 0 | Native records/view |
| Production readiness | records | 2 | 0 | Native records/view |
| Processing Activities (ROPA) | records | 1 | 0 | Native records/view |
| Data Subject Requests | records | 1 | 0 | Native records/view |
| Privacy Impact Assessments | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Consent Management | records | 1 | 0 | Native records/view |
| Data Breach Incidents | records | 1 | 0 | Native records/view |
| Third-Party Vendors | records | 2 | 0 | Native records/view |
| Retention Policies | records | 1 | 0 | Native records/view |
| Cookie Compliance | records | 1 | 0 | Native records/view |
| Cross-Border Transfers | records | 1 | 0 | Native records/view |
| Training Records | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Models | records | 1 | 0 | Native records/view |
| Datasets | records | 1 | 0 | Native records/view |
| Evaluations | records | 1 | 0 | Native records/view |
| Deployments | records | 1 | 0 | Native records/view |
| Policies | records | 3 | 0 | Native records/view |
| Incidents | records | 3 | 0 | Native records/view |
| Risk register | records | 2 | 0 | Native records/view |
| Model cards | records | 1 | 0 | Native records/view |
| Prompts | records | 1 | 0 | Native records/view |
| Ssp | records | 1 | 0 | Native records/view |
| Dpia records | records | 1 | 0 | Native records/view |
| Redteam findings | records | 1 | 0 | Native records/view |
| Third parties | records | 1 | 0 | Native records/view |
| Training runs | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fine tunes | records | 1 | 0 | Native records/view |
| Controls | records | 1 | 0 | Native records/view |
| Jurisdictions | records | 1 | 0 | Native records/view |
| Audit bias | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Detect drift | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Map compliance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Score risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft policy | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Triage incident | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Explain decision | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Prompt injection test | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fairness curve | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Data lineage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Model card generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Third party assess | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Jailbreak test | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Energy cost | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Control mapper | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Ssp drafter | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Redteam triage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Drift narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bias summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Disclosure pack | records | 1 | 0 | Native records/view |
| Approvals | records | 1 | 0 | Native records/view |
| Webhooks | integration | 1 | 0 | Provider request records only |
| Model exception waiver board | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Employees | records | 1 | 0 | Native records/view |
| Departments | records | 1 | 0 | Native records/view |
| Training Courses | records | 1 | 0 | Native records/view |
| BAAs | records | 1 | 0 | Native records/view |
| Sanctions | records | 1 | 0 | Native records/view |
| PHI Inventory | records | 1 | 0 | Native records/view |
| Access Control | records | 1 | 0 | Native records/view |
| Policy Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quiz Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Course Content | records | 1 | 0 | Native records/view |
| Assessment Builder | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Audit Report | records | 1 | 0 | Native records/view |
| Compliance Check | records | 1 | 0 | Native records/view |
| Risk Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Gap Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Security Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| PHI Risk Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Audit Log Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Incident Response | records | 1 | 0 | Native records/view |
| Incident Investigation | records | 1 | 0 | Native records/view |
| Training Recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Employee Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dept Compliance | records | 1 | 0 | Native records/view |
| Risk Mitigation | records | 1 | 0 | Native records/view |
| Sanction Advisor | records | 1 | 0 | Native records/view |
| Deadline Prioritizer | records | 1 | 0 | Native records/view |
| BAA Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| BAA Monitor | records | 1 | 0 | Native records/view |
| Policy Validator | records | 1 | 0 | Native records/view |
| Access Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Employee Deep Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Department Deep Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Auto-Enroll Training | records | 1 | 0 | Native records/view |
| Access Anomaly Detector | records | 1 | 0 | Native records/view |
| BAA Renewal Drafter | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quiz Remediation | records | 1 | 0 | Native records/view |
| Vendor Security Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Breach Tabletop Simulation | records | 1 | 0 | Native records/view |
| Governed Training | records | 1 | 0 | Native records/view |
| BAA Renewals | records | 1 | 0 | Native records/view |
| Quiz Analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Training Drift | records | 1 | 0 | Native records/view |
| agentic compliance auditor continuously | records | 1 | 0 | Native records/view |
| breach simulation gamified exercises sco | records | 1 | 0 | Native records/view |
| adaptive workforce training with role ba | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| real time access monitoring flagging bul | records | 1 | 0 | Native records/view |
| ocr policy automation extracting require | records | 1 | 0 | Native records/view |
| limited vendor security assessment depth | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| breach simulation tabletop endpoint | records | 1 | 0 | Native records/view |
| insider threat behavior baseline drif | records | 1 | 0 | Native records/view |
| user facing dashboard backend api | records | 1 | 0 | Native records/view |
| real time phi streaming monitor | records | 1 | 0 | Native records/view |
| ehr system integration | integration | 1 | 0 | Provider request records only |
| external regulator communication work | records | 1 | 0 | Native records/view |
| webhook surface for siem integration | integration | 1 | 0 | Provider request records only |
| multi tenant covered entity isolation | records | 1 | 0 | Native records/view |
| AI GDPR Scanner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Audit Scheduler | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Violation Predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Training Tracker | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Privacy Policy Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Compliance Checker | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compliance | records | 1 | 0 | Native records/view |
| Risks | records | 1 | 0 | Native records/view |
| Training | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Frameworks | records | 1 | 0 | Native records/view |
| Users | records | 1 | 0 | Native records/view |
| Assistant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compliance gap finder | records | 1 | 0 | Native records/view |
| Vendor risk scorer | records | 1 | 0 | Native records/view |
| Remediation planner | records | 1 | 0 | Native records/view |
| Policy conflict detector | records | 1 | 0 | Native records/view |
| Control effectiveness assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Board readiness report | records | 1 | 0 | Native records/view |
| Evidence exception tracker | records | 1 | 0 | Native records/view |
| continuous compliance monitoring | records | 1 | 0 | Native records/view |
| remediation workflow automation | records | 1 | 0 | Native records/view |
| aigenerated audit documentation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| policytocontrol mapping | records | 1 | 0 | Native records/view |
| thirdparty compliance exchange | records | 1 | 0 | Native records/view |
| boardready executive dashboards | records | 1 | 0 | Native records/view |
| compliancegapfinder against selected fram | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| vendorriskscorer thirdparty risk ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| policyconflictdetector crosspolicy contra | records | 1 | 0 | Native records/view |
| controleffectivenessassessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| remediationplanner ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| boardreadinessreport exec summary | records | 1 | 0 | Native records/view |
| limited workflow automation action assignmen | records | 1 | 0 | Native records/view |
| dlpcasb integrations | integration | 1 | 0 | Provider request records only |
| policy version control approval workflow | records | 1 | 0 | Native records/view |
| compliance calendar autotrack regulatory | records | 1 | 0 | Native records/view |
| incident response playbooks | records | 1 | 0 | Native records/view |
| public webhook for siem ingestion | integration | 1 | 0 | Provider request records only |
| esignature integration for attestations | integration | 1 | 0 | Provider request records only |
| Rules & Jobs | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 220 feature pages were visited in the browser; 218 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 102 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

102 original AI entries are now grouped into **7 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
