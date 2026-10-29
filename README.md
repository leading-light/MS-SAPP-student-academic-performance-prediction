# MS-SAPP
Open-source implementation of MS-SAPP for multi-view student academic performance prediction

# MS-SAPP: Student Academic Performance Prediction

## Overview

MS-SAPP is a machine-learning framework for student academic performance prediction. This repository provides the research implementation in a Jupyter Notebook, together with supporting datasets and project resources.

The project aims to support the investigation and application of machine-learning methods for predicting student academic performance.

## Repository Structure

```text
MS-SAPP-student-academic-performance-prediction/
├── data/                  # Dataset files and related documentation
├── figures/               # Figures and visualizations
├── notebooks/             # Additional notebooks, if applicable
├── results/               # Experimental results and related documentation
├── src/                   # Main implementation
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
├── LICENSE                # License information
└── .gitignore             # Git ignore rules
```

## Implementation

The main implementation is provided in the Jupyter Notebook:

`src/St_Acd_Per_AutoML_Updated.ipynb`

The notebook contains the research workflow and associated machine-learning implementation.

## Requirements

Python is required to run the implementation. The required Python packages are listed in `requirements.txt`.

Install the dependencies using:

```bash
pip install -r requirements.txt
```

Using a dedicated virtual environment is recommended to avoid conflicts with packages installed for other projects.

## Getting Started

1. Clone or download this repository.
2. Install the required Python packages.
3. Open the main notebook in Jupyter Notebook or JupyterLab.
4. Ensure the dataset path in the notebook matches the location of the dataset files.
5. Execute the notebook cells in order.

**Note:** The notebook and dataset paths must be configured correctly for your local environment. The implementation should be tested in a clean environment before its reproducibility is claimed.

## Dataset

Dataset files and related documentation are provided in the `data/` directory.

Please consult the accompanying dataset documentation for information about the dataset source, variables, preprocessing, and permitted uses.

## Results and Figures

The `results/` and `figures/` directories are intended to organize experimental outputs and visualizations associated with the project.

Only verified experimental results should be reported or interpreted as findings of the research.

## Reproducibility

To support reproducibility, users should:

- Install the dependencies listed in `requirements.txt`.
- Use the appropriate dataset and verify its location.
- Execute the notebook cells in sequence.
- Record any differences in package versions, configuration, or execution environment.

## License

Please refer to the repository's `LICENSE` file for the applicable license terms.

## Citation

If you use this software in your research, please cite the associated research publication and the archived software release when available.

A permanent DOI will be added here after the repository has been archived through Zenodo.

## Contact

For questions about the implementation or research, please contact the corresponding author or repository maintainer.
