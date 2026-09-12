# SE-STGCN: Attention-Augmented Spatio-Temporal GCN for BSL Recognition

This repository contains the code, notebooks, figures, and project documentation for an attention-augmented spatio-temporal graph convolutional network (SE-STGCN) for British Sign Language (BSL) recognition, including few-shot extensibility experiments.

## Repository Contents

### `Code Work/`

Jupyter notebooks containing the main project workflow:

- `1.Model Building Code.ipynb` - Builds and trains the primary model.
- `2.Ablation Study.ipynb` - Evaluates model components through ablation experiments.
- `3.Databasebuilderusingattentionmodel.ipynb` - Prepares/builds the database using the attention-based model workflow.
- `4.Real Life Implementation Code.ipynb` - Demonstrates real-life or video-based inference and implementation.

### `Figures/`

Diagrams, result tables, prediction examples, and supporting visual material:

- `Dataset Examples/` - Examples related to the dataset.
- `Video Prediction Example/` - Examples of predictions from video input.
- The image files in this folder document the dataset topology, preprocessing, architectures, training, ablation results, classifications, and confusion matrices.

### `Project Details.docx`

Additional project documentation and details.

## Suggested Notebook Order

1. Start with `Code Work/1.Model Building Code.ipynb` to build the main model.
2. Run `Code Work/2.Ablation Study.ipynb` to examine the contribution of individual components.
3. Review `Code Work/3.Databasebuilderusingattentionmodel.ipynb` for the database-building workflow.
4. Use `Code Work/4.Real Life Implementation Code.ipynb` for practical inference or video-based evaluation.
5. Consult `Figures/` and `Project Details.docx` for visual results and project background.

## Requirements

The notebooks are the source of truth for the Python packages, data paths, model settings, and runtime configuration used by each experiment. Open the notebooks in Jupyter Notebook, JupyterLab, or Visual Studio Code and review their setup cells before running them.

The original dataset and any generated model checkpoints are not included in this initial repository snapshot unless they are added separately.

## Reproducibility Notes

- Run notebooks in the suggested order when reproducing the complete workflow.
- Update local dataset paths in notebook configuration cells as needed.
- Keep generated outputs and large checkpoints out of Git unless they are intentionally versioned.

## License

No license has been specified yet. Add a `LICENSE` file before redistributing this work.