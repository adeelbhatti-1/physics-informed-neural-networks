# Physics Informed Neural Networks

Exploratory TensorFlow notebooks connecting numerical differentiation, automatic differentiation, and physics-informed neural networks.

## Contents

| File | Original filename |
|---|---|
| [notebooks/01_differentiation_and_pinn_experiments.ipynb](notebooks/01_differentiation_and_pinn_experiments.ipynb) | PINNs Learn.ipynb |

## Run

For Python notebooks, install the inferred dependencies:

```bash
python -m pip install -r requirements.txt
python -m jupyterlab
```

Open a notebook and run cells from the beginning. Alternatively upload the notebook to Google Colab. Replace local or Google Drive paths with your own data locations before running. Notebooks are independent unless explicitly stated otherwise. For C++ files, compile and run each example separately with a compatible C++ compiler.

## Status and limitations

This notebook combines multiple experiments, including PDE residuals and a Navier–Stokes model. Run and document each experiment separately. Training may be computationally expensive; results and convergence have not been verified.

This collection was organised from existing files. Code-cell contents were preserved; saved outputs, execution counts, and transient notebook metadata were removed. The notebooks have not been executed as part of this preparation. Dependencies are inferred and unpinned, not a tested environment lockfile.

## Results

Run the examples to regenerate results. No accuracy, performance, or correctness claims are made here.

## Provenance

See [SOURCE_MAP.csv](SOURCE_MAP.csv) for the source archive and original filename. Preserve existing acknowledgements. No blanket open-source licence has been added because rights for adapted course material and datasets have not been established.
