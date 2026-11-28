# CS3081 Artificial Intelligence

Coursework for **CS3081 Artificial Intelligence** at Effat University (Fall 2026, instructor Dr. Naila Marir):
assignments, labs and the AquaGent course project.

## Contents

| Folder | What is inside |
|---|---|
| [`Assignments/`](Assignments/) | Assignment 1 (search strategies) and Assignment 2 (Resolution Hackathon) |
| [`Labs/`](Labs/) | Lab 3 (propositional logic and model checking) and Lab 4 (Bayesian networks) |
| [`Projects/`](Projects/) | AquaGent: code, technical report, presentation and poster |
| [`Three-Reports/`](Three-Reports/) | AquaGent project overview, literature review and system flowchart |

## Structure

```
CS3081AI/
├── Assignments/
│   ├── Assignment1/          Search strategies (BFS, DFS, Greedy, A*)
│   └── Assignment2/          Resolution Hackathon: brief and solution slides
├── Labs/
│   ├── Lab3/                 Propositional logic: Python puzzles + report
│   └── Lab4/                 Bayesian network notebook (pgmpy) + report
├── Projects/
│   ├── AquaGent/                     Project code, tests and analysis
│   ├── AquaGent_ACL_Report/          Technical report (ACL format)
│   ├── AquaGent final AI/            Final presentation slides
│   └── AquaGent_Poster2_A1/          A1 poster
└── Three-Reports/            Overview, literature review, flowchart
```

## Course project: AquaGent

AquaGent is a decision-support agent that recommends a fog collector, a MOF-303 sorbent bed or no plan
for collecting water from air. It uses **Bayesian inference** to estimate fog from uncertain sensor
evidence and a **constraint satisfaction** search to keep only plans that respect safety, time and energy
limits. Built with Python and Streamlit, with 45 unit tests.

Code: [`Projects/AquaGent/`](Projects/AquaGent/) · Standalone repository: [Zalameri/aquagent](https://github.com/Zalameri/aquagent)

The Lab 1 market study for Software Engineering lives in the `Software-Engineering` repository.
