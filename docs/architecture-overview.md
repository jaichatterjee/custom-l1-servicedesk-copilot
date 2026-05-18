# Architecture Overview

## Operational Flow

```text
L1 Analyst
      ↓
Structured Intake
      ↓
Issue Normalization
      ↓
Deterministic Topic Routing
      ↓
Human Validation
      ↓
ServiceNow Execution
```

---

## Major Components

### Intake Layer

Responsible for:

- symptom capture
- issue normalization
- context gathering

### Diagnostic Layer

Responsible for:

- topic routing
- troubleshooting logic
- decision guidance

### Governance Layer

Responsible for:

- topic restrictions
- scope boundaries
- validation checkpoints

### Execution Layer

Responsible for:

- validated ServiceNow workflow actions
```
