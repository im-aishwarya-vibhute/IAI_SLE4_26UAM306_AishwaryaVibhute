# IAI_SLE4_26UAM306_AishwaryaVibhute
# SLE-4: Final Viva & Architecture Decision Record (ADR) Defense

**Course:** 02AML204 – Introduction to AI  
**Name:** Aishwarya Sanjay Vibhute  
**PRN:** 26UAM306  
**Division:** SY-A  
**Semester:** VI

## Overview
This repository contains the SLE-4 documentation for the Introduction to AI course. The work connects the outcomes of SLE-1, SLE-2, and SLE-3 and presents a design decision in an Architecture Decision Record (ADR).

## SLE Work Summary

### SLE-1 – Rule-Based Agent
Developed a rule-based agent for student performance analysis. The agent uses defined rules to interpret student-related information and produce an outcome.

### SLE-2 – BFS vs DFS
Compared Breadth-First Search (BFS) and Depth-First Search (DFS) on a small graph. The experiment used Python timing measurements and node counts to compare their observed performance.

**Recorded average timings from the earlier report:**
- BFS: approximately 0.002957 ms
- DFS: approximately 0.003447 ms

These are experiment-specific measurements, not universal performance guarantees. Verify them against the original profiling output before submission.

### SLE-3 – Full C4 Model
Prepared an architectural design using the Full C4 Model to describe the system at multiple levels. The architecture helps show the system context, containers, components, and relevant implementation details.

## SLE-4 – Architecture Decision Record
The ADR documents a design choice connected to the search and architecture work. It should explain:
- **Context:** the problem or design need.
- **Decision:** the selected design approach.
- **Alternatives:** other options considered.
- **Rationale:** why the selected option is appropriate, using evidence from earlier SLE work where available.
- **Consequences:** benefits, limitations, and future considerations.

> **Important:** Keep the ADR consistent with the actual code and diagrams. If your final ADR uses a visited set or a modular search engine, make sure those elements are present in your implementation or clearly describe them as design decisions.

## Suggested Repository Structure

```text
SLE4_26UAM306_AishwaryaVibhute/
├── README.md
├── AI_Contribution_Log.md
├── SLE4_Report.docx
└── diagrams/
    └── c4_architecture.png
```

The structure above is a suggestion. Keep only files that actually exist in your repository, and update file names to match your submission.

## AI Contribution
AI was used to support explanation, organization, and wording. The student is responsible for checking the code, profiling values, diagrams, and report and for understanding the work presented in the viva. See [`AI_Contribution_Log.md`](AI_Contribution_Log.md).

## Before Submission
- [ ] Check the SLE-2 measurements against the original output file.
- [ ] Check that the SLE-3 C4 diagrams match the actual architecture.
- [ ] Ensure the ADR describes the project accurately.
- [ ] Add the final report and any required diagrams.
- [ ] Make sure every listed file exists in the repository.
- [ ] Practice explaining the design decision and its trade-offs in your own words.
