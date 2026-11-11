# Jupyter Interactive Widgets (`ipywidgets`) — Fork

> Fork of Project Jupyter's official interactive HTML widgets library for Jupyter Notebooks and JupyterLab (`jupyter-widgets/ipywidgets`).

[![Jupyter](https://img.shields.io/badge/Jupyter-Project-F37626.svg)](https://jupyter.org/)
[![Upstream](https://img.shields.io/badge/Upstream-jupyter--widgets%2Fipywidgets-blue.svg)](https://github.com/jupyter-widgets/ipywidgets)

---

## Repository Context

This repository is a personal fork of [jupyter-widgets/ipywidgets](https://github.com/jupyter-widgets/ipywidgets) (BSD 3-Clause License; all original copyrights belong to Project Jupyter and upstream contributors).

- **Upstream Repository:** [https://github.com/jupyter-widgets/ipywidgets](https://github.com/jupyter-widgets/ipywidgets)
- **Official Documentation:** [https://ipywidgets.readthedocs.io/](https://ipywidgets.readthedocs.io/)

---

## Workspace Verification Commands (`package.json`)

The monorepo declares Yarn workspaces (`packages/*`, `python/widgetsnbextension`, `examples/*`, `python/jupyterlab_widgets`, `"npm": "please-use-yarn"`, `"yarn": ">=3"`):

- `yarn build` — `lerna run build --stream --ignore "@jupyter-widgets/example-*"`
- `yarn build:test` — `lerna run build:test --stream --ignore "@jupyter-widgets/example-*"`
- `yarn lint:check` — `yarn prettier:check && yarn eslint:check`
- `yarn integrity` — `node scripts/package-integrity.js`

*These commands are listed from `package.json`; they have not been executed locally in this documentation PR.*
