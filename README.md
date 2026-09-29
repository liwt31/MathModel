# Mathematical Modeling

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/liwt31/MathModel/blob/2026/w01_numpy.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/liwt31/MathModel/2026?filepath=w01_numpy.ipynb)

Notebooks for **MAT3300 Mathematical Modeling** (Fall 2026, redesigned course). Launch the first notebook with the badges above, or pick any week below.

## Notebooks

- **Week 1 — Python and NumPy basics** — [w01_numpy.ipynb](w01_numpy.ipynb): Python and Jupyter from zero, NumPy arrays, broadcasting, and a first Monte Carlo exercise.
  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/liwt31/MathModel/blob/2026/w01_numpy.ipynb)
  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/liwt31/MathModel/2026?filepath=w01_numpy.ipynb)
- **Week 2 — Discrete dynamics** — [w02_discrete.ipynb](w02_discrete.ipynb): difference-equation models of change (savings, mortgage, yeast, drug dosage), equilibrium and stability, and the logistic map's route to chaos.
  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/liwt31/MathModel/blob/2026/w02_discrete.ipynb)
  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/liwt31/MathModel/2026?filepath=w02_discrete.ipynb)
- **Week 3 — Empirical modeling, fitting** — [w03_fitting.ipynb](w03_fitting.ipynb): the least-squares criterion, normal equations, transformed fitting, polynomial fitting vs interpolation, validation, and a hand-built mini-Prophet on the 2023 MCM C Wordle data.
  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/liwt31/MathModel/blob/2026/w03_fitting.ipynb)
  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/liwt31/MathModel/2026?filepath=w03_fitting.ipynb)
- **Week 4 — Simulation modeling** — [w04_simulation.ipynb](w04_simulation.ipynb): Monte Carlo for areas and probabilities, the inverse-CDF trick, queueing simulation, stochastic growth, a traffic cellular automaton with an animation, and the 2024 MCM B search for a lost submersible.
  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/liwt31/MathModel/blob/2026/w04_simulation.ipynb)
  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/liwt31/MathModel/2026?filepath=w04_simulation.ipynb)

## How to run

- **In the cloud**: click a Colab or Binder badge above (Binder takes a minute to start).
- **Locally**: install Python (e.g. via [Anaconda](https://www.anaconda.com/download)), then

  ```
  pip install -r requirements.txt
  jupyter lab
  ```

The notebooks are self-contained; `mm.mplstyle` (optional) makes the plots prettier. Previous course editions live on the `master` branch.
