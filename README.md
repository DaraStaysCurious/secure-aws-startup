# secure-aws-startup

**OccuSafe: a secure-by-default AWS foundation**

A hands-on cloud security project built alongside AWS Cloud Practitioner study. A fictional occupational health and safety SaaS company needs a first AWS environment. This repo builds it with preventive controls, monitoring and detection, tests each control against a deliberate misconfiguration, and rebuilds part of it as code.

> **Thesis:** Unsafe behavior is a system design failure, not a human failure. The environment should make the safe path the easy one.

## Status

| Workstream | Label | Status |
|---|---|---|
| 1. Account security and IAM | | Not started |
| 2. Storage and compute | | Not started |
| 3. Network | | Not started |
| 4. Logging and detection | | Not started |
| 5. Data protection | | Not started |
| 6. Infrastructure as code and assessment | | Not started |

Labels: **Implemented** (built and tested), **Designed** (documented, not built), **Simulated** (scenario run to show a detection or response).

## Repo layout

```
secure-aws-startup/
├── README.md
├── 01-project-brief.md
├── learning-tracker.md
├── architecture/        # diagram + short decision log
├── 01-account-iam/      # note, evidence, test
├── 02-storage-compute/
├── 03-network/
├── 04-logging-detection/
├── 05-data-protection/
├── 06-iac/              # CloudFormation templates
├── threat-model.md
├── nist-csf-mapping.md
└── .gitignore           # keep secrets, keys and account IDs out
```

Each workstream folder holds the same four things: the configuration, the security test, redacted evidence and a short decision note.

## Rules for this repo

- Synthetic data only.
- No account IDs, access keys or unredacted screenshots committed.
- Every control has a test that tries to break it.

## Related repos

`paved-road-iam` · `cloud-control-translator` · `cloud-incident-postmortem`
