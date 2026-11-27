# AquaGent (CS3081 course project)

> **The main, up-to-date repository is [Zalameri/aquagent](https://github.com/Zalameri/aquagent).**
> It has the full README, the analysis scripts, the technical report (ACL format) and its LaTeX source.

AquaGent is an explainable decision-support agent that chooses between a fog collector, a MOF-303 sorbent bed, or no plan, using a Bayesian sensor model and a backtracking constraint satisfaction problem (CSP).

- Interactive demo: <https://zalameri.github.io/aquagent/>
- Case study: <https://zalameri.github.io/project.html?p=aquagent>

This folder keeps a copy of the source code for the course archive:

```bash
python -m pip install -r requirements.txt
python -m unittest discover -s tests -v    # 45 tests
python -m streamlit run app.py
```

Team: Zainab Alameri and Abubaker Baobaid (equal, joint work). Instructor: Dr. Naila Marir, Effat University, Fall 2026.
