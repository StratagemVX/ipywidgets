# Jupyter Interactive Widgets (ipywidgets) — Fork

> Upstream fork of Project Jupyter's official interactive HTML widgets library for Jupyter Notebooks and JupyterLab.

[![Jupyter](https://img.shields.io/badge/Jupyter-Project-F37626.svg)](https://jupyter.org/)
[![Upstream](https://img.shields.io/badge/Upstream-jupyter--widgets%2Fipywidgets-blue.svg)](https://github.com/jupyter-widgets/ipywidgets)

---

## Repository Context

This repository is an authentic upstream fork of the official [jupyter-widgets/ipywidgets](https://github.com/jupyter-widgets/ipywidgets) open-source project. All original copyrights, licensing terms (BSD 3-Clause), and contributor attributions belong to Project Jupyter.

---

## Upstream Documentation & Reference

For primary documentation, release notes, and contribution guidelines, visit the official upstream repository:
- **Upstream Repository:** [https://github.com/jupyter-widgets/ipywidgets](https://github.com/jupyter-widgets/ipywidgets)
- **Official Documentation:** [https://ipywidgets.readthedocs.io/](https://ipywidgets.readthedocs.io/)

## Verification and maintenance

This repository's README is the starting point for understanding the project. Before proposing changes, inspect the current default branch and the dependency manifest, then verify the affected workflow locally.

### Available package scripts

- `npm run build` — `lerna run build --stream --ignore "@jupyter-widgets/example-*"`
- `npm run lint` — `yarn && yarn prettier && yarn eslint`

Run only the scripts relevant to the change; a script being listed does not mean it has been executed or passed.

### Contribution and security notes

- Keep examples, screenshots, feature claims, and architecture descriptions synchronized with the implementation.
- Never commit real credentials, private keys, production data, or local environment files. Use a placeholder-only environment example and configure secrets in the deployment platform.
- Include reproduction steps and expected versus actual behavior when reporting a defect.
- Record any required environment variables and external services without publishing their secret values.
- Confirm tests and build checks on the proposed change before merging.
