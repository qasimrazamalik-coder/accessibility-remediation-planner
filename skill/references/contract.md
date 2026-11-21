# Contract

## Capability
Prioritize WCAG remediation work from accessibility findings using severity, reach and fix confidence.

## Input root
`findings` with fields: id, severity, users_affected, confidence.

## Output
JSON containing `skill` and deterministic findings, ranking, mapping, plan or redaction results.

Reject malformed JSON. Do not infer authorization or fabricate evidence.
