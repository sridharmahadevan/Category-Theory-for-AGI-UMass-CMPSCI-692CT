# Category Theory for AGI — Colab Course Template

This bundle contains Colab-ready notebooks with a consistent **Environment** cell,
lightweight **micro-demos**, and **exercises**. Push this repo to GitHub and replace `sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT`
in each badge so students can launch directly in Colab.

## Structure
- `notebooks/week01_backprop_as_functor.ipynb`
- `notebooks/week01_sudoku_gt_db.ipynb` (Sudoku GT vs Transformer + Diagrammatic Backprop)
- `notebooks/week01_lm_gt_vs_transformer.ipynb` (PTB language modeling: GT vs Transformer)
- `notebooks/week02_yoneda_microdemo.ipynb`
- `notebooks/week03_limits_colimits_microdemo.ipynb`
- `notebooks/week04_clustering_as_functor.ipynb`

## Usage
1. Open the notebook link (or upload to Colab), run the **Environment** cell first.
2. GPU is optional. All examples run on CPU in < 5 minutes.
3. For local use, create a conda env via `environment.yml` and run JupyterLab.

## Colab Badge Template
```
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week01_backprop_as_functor.ipynb)
```
Replace `sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT` once you publish the repo.

## Local environment (optional)
```
conda env create -f environment.yml
conda activate ct4agi
jupyter lab
```

## Direct Colab Links

- Week 1 — Backprop as a Functor  
  Functorial view of backprop with a small, runnable micro-demo.  
  https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week01_backprop_as_functor.ipynb
- Week 1 — Sudoku GT + Diagrammatic Backprop  
  Compare **Geometric Transformer vs. baseline Transformer** on 4x4 Sudoku; optional DB curvature penalty.  
  https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week01_sudoku_gt_db.ipynb
- Week 1 — Language Modeling (PTB): GT vs Transformer  
  Compare **Geometric Transformer vs. baseline Transformer** on a tiny PTB language model.  
  https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week01_lm_gt_vs_transformer.ipynb
- Week 2 — Yoneda Micro-Demo  
  https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week02_yoneda_microdemo.ipynb
- Week 3 — Limits & Colimits Micro-Demos  
  https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week03_limits_colimits_microdemo.ipynb
- Week 4 — Clustering as a Functor  
  https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week04_clustering_as_functor.ipynb

## Colab Badges

- Week 1 — Backprop as a Functor  
  Functorial view of backprop with a small, runnable micro-demo.  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week01_backprop_as_functor.ipynb)
- Week 1 — Sudoku GT + Diagrammatic Backprop  
  Compare **Geometric Transformer vs. baseline Transformer** on 4x4 Sudoku; optional DB curvature penalty.  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week01_sudoku_gt_db.ipynb)
- Week 1 — Language Modeling (PTB): GT vs Transformer  
  Compare **Geometric Transformer vs. baseline Transformer** on a tiny PTB language model.  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week01_lm_gt_vs_transformer.ipynb)
- Week 2 — Yoneda Micro-Demo  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week02_yoneda_microdemo.ipynb)
- Week 3 — Limits & Colimits Micro-Demos  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week03_limits_colimits_microdemo.ipynb)
- Week 4 — Clustering as a Functor  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week04_clustering_as_functor.ipynb)
