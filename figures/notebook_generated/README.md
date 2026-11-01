# Notebook-Generated Figures

This directory is intended to contain the visualizations generated during the execution of the MS-SAPP (Student Academic Performance Prediction) research implementation.

## Experimental Scope

The experimental evaluation covers:

- **6 datasets**
- **21 classifiers**
- **126 dataset–classifier experiments**
- **126 confusion matrices**

## Confusion Matrices

The confusion matrices are computed and displayed by **Module 7** of the main research notebook.

Each confusion matrix represents the classification performance of one classifier on one dataset. Collectively, these visualizations provide a detailed view of the classification outcomes across all evaluated dataset–classifier combinations.

The complete set of 126 confusion matrices can be inspected by executing Module 7 in the following notebook:

`src/St_Acd_Per_AutoML_Updated_Final.ipynb`

## Output Files

The `confusion_matrices/` subdirectory is reserved for the individual confusion matrix images, if they are exported and saved separately by the implementation.

**Note:** The notebook displays the confusion matrices during execution. Displaying a figure does not necessarily save it as an image file in this directory.

## Reproducibility

Researchers can reproduce and inspect these visualizations by running the corresponding experimental module in the main notebook, using the required datasets and Python dependencies.

For the complete implementation and experimental outputs, refer to the main repository README and the `src/`, `data/`, and `results/` directories.
