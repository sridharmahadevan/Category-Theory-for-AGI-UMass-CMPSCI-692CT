# Sudoku Geometric Transformer + Diagrammatic Backprop (Colab)

This is a small, classroom-friendly example for the Category Theory for AGI course. It compares:
- A baseline Transformer
- A Geometric Transformer (GT-Lite) with an optional diagrammatic backprop (DB) penalty

The DB signal is implemented as a **triangle consistency** loss. For each triangle in the Sudoku constraint graph (row, column, block), we encourage the three embeddings to agree with their mean. This gives a simple, local proxy for “diagrammatic curvature,” without introducing heavier topology machinery.

## Files
- `colab/Sudoku_GT_DB_Colab.ipynb`: the Colab-ready notebook

## What Students Will See
- A tiny 4x4 Sudoku dataset generator
- A baseline Transformer vs. GT-Lite architecture
- Optional DB penalty (`lambda_db`) to bias local consistency
- A quick training run and an accuracy plot
- A single-puzzle inspection for intuition

## Suggested Classroom Flow
1. Run the notebook end-to-end with `lambda_db = 0.0`.
2. Re-run with `lambda_db = 0.05` and compare the curve.
3. Discuss how triangle consistency relates to “gluing” local information into a global solution.

## Notes
- The default settings are intentionally small for speed. For stronger results, increase `num_epochs` and `num_train` in the notebook.
- You can swap in `sudoku_gt_smoke_plot.py` if you want to run the full script outside Colab.
