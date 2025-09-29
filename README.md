# data-science-template

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

An environment to develop multiple data projects

## Project Organization

```
├── LICENSE            <- MIT license
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
|   ├── global         <- Generic data folder
│   |   ├── external    <- Data from third party sources.
│   |   ├── interim     <- Intermediate data that has been transformed.
│   |   ├── processed   <- The final, canonical data sets for modeling.
│   |   └── raw         <- The original, immutable data dump.
|   |
|   └── {project}      <- Project specific data folder
│       ├── external    <- Project data from third party sources.
│       ├── interim     <- Project intermediate data that has been transformed.
│       ├── processed   <- Project final datasets.
│       └── raw         <- Project original files, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models
|   ├── global         <- Generic models trained and serialized models, model predictions, or model summaries
|   └── {project}      <- Project models trained and serialized models, model predictions, or model summaries
│
├── notebooks
|   ├── global         <- Generic jupyter notebooks. Naming convention is a number (for ordering)
|   └── {project}      <- Project jupyter notebooks. Naming convention is a number (for ordering)
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         common and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            
|   ├── global         <- Generic generated analysis as HTML, PDF, LaTeX, etc.
│   |   └── figures    <- Generic generated graphics and figures to be used in reporting
|   |
|   └── {project}      <- Project generated analysis as HTML, PDF, LaTeX, etc.
|       └── figures    <- Project generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── common   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes common a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations
```

--------

