# Mathematical Modeling

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/liwt31/MathModel/2026)
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/liwt31/MathModel/2026)

Notebooks for **MAT3300 Mathematical Modeling** (Fall 2026, redesigned course).

## Notebooks

- **Week 1 — Python and NumPy basics** — [w01_numpy.ipynb](w01_numpy.ipynb): Python and Jupyter from zero, NumPy arrays, broadcasting, vectorization, and a first Monte Carlo exercise.
  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/liwt31/MathModel/2026/w01_numpy.ipynb)
  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/liwt31/MathModel/2026?filepath=w01_numpy.ipynb)
- **Week 2 — Discrete dynamics and the modeling process** — [w02_discrete.ipynb](w02_discrete.ipynb): the six-step modeling process on the yeast data, equilibria and stability, least-squares fitting, the car-rental system, the competitive hunter model, and the logistic map's route to chaos.
  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/liwt31/MathModel/2026/w02_discrete.ipynb)
  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/liwt31/MathModel/2026?filepath=w02_discrete.ipynb)

## How to run

- **In the cloud**: click the Colab or Binder button above (Binder takes a minute to start).
- **Locally**: install Python (e.g. via [Anaconda](https://www.anaconda.com/download)), then
  ```
  pip install -r requirements.txt
  jupyter lab
  ```
  The Week 1 notebook is self-contained; `mm.mplstyle` (optional) makes the plots prettier.

Previous course editions live on the `master` branch.
