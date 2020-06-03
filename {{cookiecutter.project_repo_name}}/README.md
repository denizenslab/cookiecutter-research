{{cookiecutter.project_name}} in {{cookiecutter.project_repo_name}}
===================================================================

{{cookiecutter.project_description}}

Project Organization
------------


```
├── .gitignore
├── .travis.yml
├── AUTHORS.md
├── LICENSE
├── README.md                       <- Top-level readme file for this project
├── data/                           <- Big data information will be stored as json-metadata
│   ├── external/                   <- Third party data
│   ├── models/                     <- Trained models, model predictions, or model summaries
├── docs/                           <- Documentation with Sphinx
├── exploratory_results/            <- Exploratory results as notebooks, HTML, PDF, viewers, etc
│   ├── figures/
│   ├── notebooks/
│   └── static_viewers/
├── final_results/                  <- Final results as notebooks, HTML, PDF, viewers, etc
│   ├── figures/
│   ├── notebooks/
│   └── static_viewers/
├── logs/                           <- Log files (jobs, script outputs, etc.)
├── materials/                      <- Spreadsheets, articles, notes, manuals, and other materials
│   ├── meetings/                   <- Meeting minutes
│   ├── notes/                      <- Project notes
│   └── references/                 <- Papers and other references
├── requirements.txt                <- Requirements for reproducing the analysis environment
└── src/                            <- Code
    ├── analysis/                   <- Code to train models and make predictions
    ├── features/                   <- Code for extracting features from stimulus
    ├── lib/                        <- Library code to be imported by scripts, notebooks, or libraries
    │   └── {{ cookiecutter.python_package_name }}/      <- Library code specific to project
    │       ├── setup.py            <- Installs project python package
    │       └── {{ cookiecutter.python_package_name }}/  <- Actual package folder
    │           ├── tests/          <- Library Tests
    │           ├── __init__.py     <- Makes package a Python module
    ├── preprocessing/              <- Code to preprocess the data
    ├── stimulus_generation/        <- Code to download or generate stimulus 
    ├── stimulus_presentation/      <- Code to present stimulus to subject
    ├── tests/                      <- General Tests
    └── viz/                        <- Code to create exploratory and results oriented vizualisations
```
--------

<p><small>Project based on the <a target="_blank" href="https://fatmai.github.io/cookiecutter-fmri/">cookiecutter research project template</a></small></p>
