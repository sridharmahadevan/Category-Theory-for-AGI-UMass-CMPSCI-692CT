# Category Theory for AGI — Colab Course Template

This bundle contains Colab-ready notebooks with a consistent **Environment** cell,
lightweight **micro-demos**, and **exercises**. Push this repo to GitHub and replace `sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT`
in each badge so students can launch directly in Colab.

## Structure
- `notebooks/week01_backprop_as_functor.ipynb`
- `notebooks/week01_sudoku_gt_db.ipynb` (Sudoku GT vs Transformer + Diagrammatic Backprop)
- `notebooks/week01_lm_gt_vs_transformer.ipynb` (PTB language modeling: GT vs Transformer)
- `notebooks/week02_yoneda_microdemo.ipynb`
- `notebooks/week02_yoneda_self_attention_demo1.ipynb` (Yoneda self-attention demo)
- `notebooks/week03_limits_colimits_microdemo.ipynb`
- `notebooks/week03_db_colimit_energy.ipynb` (DB as (co)limit energy minimization)
- `notebooks/week04_clustering_as_functor.ipynb`
- `notebooks/week07_sheaves_covers.ipynb` (Sheaves via covers and gluing)
- `notebooks/week08_topos_overlap_penalty.ipynb` (Topos overlap consistency penalty)
- `notebooks/week09_causal_discovery_toy.ipynb` (Toy causal discovery)
- `notebooks/week10_kan_do_rn.ipynb` (Kan-Do calculus with RN ratios)
- `notebooks/week11_subobject_classifier.ipynb` (Subobject classifier in Sets)
- `notebooks/week12_jstability_regimes.ipynb` (j-stability across regimes)
- `notebooks/week13_democritus_manifold.ipynb` (Democritus causal manifold demo)
- `data/democritus/manifold.npz` (small topic manifold snapshot)

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
- Week 2 — Yoneda Self-Attention Demo 1  
  https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week02_yoneda_self_attention_demo1.ipynb
- Week 3 — Limits & Colimits Micro-Demos  
  https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week03_limits_colimits_microdemo.ipynb
- Week 3 — DB as (Co)limit Energy  
  Minimize consistency/gluing energy to approximate limits and colimits.  
  https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week03_db_colimit_energy.ipynb
- Week 4 — Clustering as a Functor  
  https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week04_clustering_as_functor.ipynb
- Week 7 — Sheaves via Covers and Gluing  
  Local covers + overlap consistency on a toy interference example.  
  https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week07_sheaves_covers.ipynb
- Week 8 — Topos Overlap Penalty  
  Sheaf-style overlap penalty prefers the true causal graph.  
  https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week08_topos_overlap_penalty.ipynb
- Week 9 — Toy Causal Discovery  
  Recover edges from a linear SEM with simple regressions.  
  https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week09_causal_discovery_toy.ipynb
- Week 10 — Kan-Do Calculus with RN Ratios  
  Conditioning vs intervention via Radon–Nikodym reweighting.  
  https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week10_kan_do_rn.ipynb
- Week 11 — Subobject Classifier  
  Characteristic maps in Sets as a concrete subobject classifier.  
  https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week11_subobject_classifier.ipynb
- Week 12 — j-Stability Across Regimes  
  Stable edges across environments from synthetic SEMs.  
  https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week12_jstability_regimes.ipynb
- Week 13 — Democritus Causal Manifold  
  Visualize a topic manifold as a lightweight DB + GT example.  
  https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week13_democritus_manifold.ipynb

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
- Week 2 — Yoneda Self-Attention Demo 1  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week02_yoneda_self_attention_demo1.ipynb)
- Week 3 — Limits & Colimits Micro-Demos  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week03_limits_colimits_microdemo.ipynb)
- Week 3 — DB as (Co)limit Energy  
  Minimize consistency/gluing energy to approximate limits and colimits.  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week03_db_colimit_energy.ipynb)
- Week 4 — Clustering as a Functor  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week04_clustering_as_functor.ipynb)
- Week 7 — Sheaves via Covers and Gluing  
  Local covers + overlap consistency on a toy interference example.  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week07_sheaves_covers.ipynb)
- Week 8 — Topos Overlap Penalty  
  Sheaf-style overlap penalty prefers the true causal graph.  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week08_topos_overlap_penalty.ipynb)
- Week 9 — Toy Causal Discovery  
  Recover edges from a linear SEM with simple regressions.  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week09_causal_discovery_toy.ipynb)
- Week 10 — Kan-Do Calculus with RN Ratios  
  Conditioning vs intervention via Radon–Nikodym reweighting.  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week10_kan_do_rn.ipynb)
- Week 11 — Subobject Classifier  
  Characteristic maps in Sets as a concrete subobject classifier.  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week11_subobject_classifier.ipynb)
- Week 12 — j-Stability Across Regimes  
  Stable edges across environments from synthetic SEMs.  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week12_jstability_regimes.ipynb)
- Week 13 — Democritus Causal Manifold  
  Visualize a topic manifold as a lightweight DB + GT example.  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week13_democritus_manifold.ipynb)
