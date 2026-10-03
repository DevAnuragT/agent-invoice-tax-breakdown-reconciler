# Invoice Tax Breakdown Reconciler

Reconcile invoice line, tax, and total evidence using decimal arithmetic.

## Run

    python3 agent.py examples/good-input.json
    python3 tools/review-invoice-tax-breakdown-reconciler.py examples/good-input.json

Input requirements and thresholds are listed in metadata.json. Output contains status, score, checked rules, and evidence-backed findings.

## Limits

Offline, deterministic review aid. Cannot establish facts beyond supplied evidence; a human must review before acting.
