# Documents

Course deliverables for the project. Each folder holds the LaTeX source
(`report.tex`), the generated report (`report.pdf`) and any assets it needs.

| Folder | Deliverable | Status |
| --- | --- | --- |
| `task1-proposal/` | Task 1 — Project proposal (problem diagnosis, proposed treatment, plan of work) | Submitted 2026-10-08 |
| `task2-urs/` | Task 2 — User requirements specification, plus the elicitation material it is based on (`elicitation/`: interview outline, minutes template, questionnaires R1/R2) | Submitted 2026-10-20 |
| `task3-ra/` | Task 3 — Requirements analysis (context, use-case, class, object, sequence and state diagrams; PlantUML sources in `figures/`) | Draft complete, due 2026-11-12 |

Rebuild a report with:

```bash
cd docs/taskN-*/
xelatex report.tex && xelatex report.tex
```
