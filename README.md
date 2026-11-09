# INSIDEA COO Playbook

The operating playbook for the COO office at INSIDEA. One place for brand guardrails, SOPs, templates, operating cadence and decisions, so every update, document and process starts from the same standard.

## How it is organized

| Folder | What lives here |
|---|---|
| `brand/` | Approved facts, voice rules, retired claims, paste-ready copy blocks |
| `sops/` | Standard Operating Procedures, plus the INSIDEA SOP template |
| `templates/` | Recurring COO documents: CEO updates, status reports, escalation briefs, change requests, vendor reviews, 1:1s |
| `cadence/` | The COO operating rhythm: daily, weekly, monthly, quarterly |
| `projects/` | Standing workstreams and their owners |
| `decisions/` | Decision log, one entry per material decision |
| `skills/` | Index of the Claude skills that pair with this playbook |

`CLAUDE.md` loads this context into every Claude session automatically.

## Working rules

1. **Brand first.** Anything carrying the INSIDEA name is checked against `brand/` before it leaves the building.
2. **Draft only.** Nothing is sent, posted or published without a person approving it.
3. **Version everything.** SOPs start at v0.1. Change them through a commit, not a side copy.
4. **Confidential by default.** No client data in this repo beyond what a template needs. Never carry one client's details into another client's work.

## Adding to the playbook

- New SOP: copy `sops/_template-sop.md`, name it `sops/<department>-<topic>.md`, add it to `sops/README.md`.
- New template: add it to `templates/` and list it in the table in `templates/README.md`.
- New decision: add an entry to `decisions/decision-log.md`.
