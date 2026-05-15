# MEMORY

Purpose: preserve cumulative judgment without freezing stale assumptions.

Maintain:
- evaluation_history
- decision_history
- focus_queue
- active_tests
- evidence_ledger
- unresolved_blockers
- stale_assumptions
- reclassification_history

Required checks:
1. Any overdue active test?
2. Any PURSUE NOW with no recent action?
3. Any assumption older than 60 days without revalidation?
4. Any contradictory new evidence not reconciled?

Portfolio view:
- PURSUE NOW
- NEXT
- PARK
- MONITOR
- REJECT

Failure criteria:
- active focus without active test
- contradictory evidence ignored
- stale assumptions still driving decisions
