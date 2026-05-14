\# BM-08 – Cost Aggregation by Course



\## Purpose

Aggregate all costs (TK 621, 622, 627) incurred in the period by course and license category.



\## Key Variables

\- Course ID: identifies training batch

\- License type: B, C1, C2...

\- Direct materials (TK 621)

\- Direct labor (TK 622)

\- Manufacturing overhead (TK 627)

\- Total cost per course



\## Business Rules

\- All costs must be classified into:

&#x20; - Group A: Direct materials

&#x20; - Group B: Direct labor

&#x20; - Group C: Overhead

\- Total must match detailed accounting ledger (TK 154)

\- Difference between ledger and BM-08 must be zero before approval

\- If difference exists → must explain before proceeding



\## System Integration

\- P3: Cost aggregation

\- P5: Input for cost calculation (BM-10)

\- P7: Cost control and reconciliation



\## Notes

This is a mandatory input for cost calculation and work-in-progress tracking.

