# Category Theory for AGI — Colab Course Template

This bundle contains three Colab-ready notebooks (Weeks 1–3) with a consistent **Environment** cell,
lightweight **micro-demos**, and **exercises**. Push this repo to GitHub and replace `sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT`
in each badge so students can launch directly in Colab.

## Structure
- `notebooks/week01_backprop_as_functor.ipynb`
- `notebooks/week02_yoneda_microdemo.ipynb`
- `notebooks/week03_limits_colimits_microdemo.ipynb`

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
  https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week01_backprop_as_functor.ipynb
- Week 2 — Yoneda Micro-Demo  
  https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week02_yoneda_microdemo.ipynb
- Week 3 — Limits & Colimits Micro-Demos  
  https://colab.research.google.com/github/sridharmahadevan/Category-Theory-for-AGI-UMass-CMPSCI-692CT/blob/main/notebooks/week03_limits_colimits_microdemo.ipynb
