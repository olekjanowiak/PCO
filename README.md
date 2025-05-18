welcome to my thesis project :construction_worker:
# the Protein Crystallization Oracle (PCO)
PCO is a deep learning framework for protein crystallization success prediction. Currently only the CLI is available, a server instance with a GUI is coming soon.

## Installation
If you just want to train the model and run predictions:
```
conda create -n pco python=...
conda activate pco
conda install ...
```

To reproduce the entire data processing pipeline, Snakemake and per-step software dependencies are required (managed by conda).
