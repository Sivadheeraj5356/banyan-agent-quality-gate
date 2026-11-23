# Agent Quality Gate

Independent role-specific prototype for Banyan Intelligence's Applied AI/ML Intern role. Not affiliated with Banyan and not connected to its product.

A dependency-free browser demo for deterministic agent trace checks: allowed tools, required tools, confirmation-before-mutation, evidence-string consistency and latency budgets. Four synthetic baseline traces pass. Four intentionally broken candidate traces block release. Twelve built-in checks cover invalid traces, ordering, boundaries, immutability and the example regressions.

## Run

Open `index.html` in any modern browser. Select a fixture set, click Evaluate traces, and run self-tests. No install, network, model calls, credentials, telemetry or real customer data.

## Limits

Evidence string matching is a toy deterministic check, not a general hallucination detector. There is no model integration, statistical significance, production workload or claim of compatibility with Banyan systems. A real deployment would need schema validation, adversarial cases, versioned datasets, calibrated graders and real latency measurements. Fixture latency values are synthetic.

Built as a small work sample, not an interview assessment solution.
