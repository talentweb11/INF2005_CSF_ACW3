# INF2005_CSF_ACW3

INF2005 CSF ACW3 coursework workspace for controlled vulnerability research, lab documentation, evidence, and the final report.

## Quick start

1. Read `INF2005-ACW3-Specification-AY2026-T1.v2.pdf`.
2. Record CVE verification, instructor guidance, and feasibility in [docs/decisions.md](docs/decisions.md).
3. Review the relevant lab README before adding setup assets or tests.
4. Follow [docs/demo-runbook.md](docs/demo-runbook.md) once the lab has been validated.
5. Save evidence under `evidence/` and write the report in `report/draft.md`.

The Python TLS lab at [demo/CVE-2026-19553-python-tls](demo/CVE-2026-19553-python-tls/README.md) contains a runnable local reproduction. The other lab folders remain scaffolds.

## Project layout

- `docs/`: decisions, timeline, demo instructions, report ownership, and AI disclosure.
- `demo/`: isolated lab setup and controlled tests.
- `evidence/`: captured outputs and observations.
- `report/`: collaborative draft and references.

## Team

| Member | Responsibilities |
| --- | --- |
| TBD | TBD |

## Safety scope

Run experiments only in authorized, isolated local environments using synthetic data. Document containment and cleanup before running tests. Do not target public systems or commit secrets or personal data.
