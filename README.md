![energy_image](https://795d665f9fc7b1053e24-4d632937b8453c17306cf8bcb974f77f.ssl.cf3.rackcdn.com/x/1330cm500/images/Sectors/Sustainable_energy/sector-banner_sustainable-energy-banner-fisher-german.jpg)

Energy Analysis Project
==============================

**Python 3.8**

A project analysing energy data from EU countries. This project will take you through the full data science process. It is an ongoing project that has started in June 2020. The aim of the project is to look at the power generation from various European countries and understand the parameters it is affected by. 

During this process we get to explore all the common steps of a data science project. From data collection, cleanning, exploratory data analysis to modelling. The hope is to also get to a stage where we can deploy an web app. 

This project was inspired by a workshop I attended in DSGO virtual. More information can be found on [this page](https://github.com/Samreay/DSGoPipeline).

Installation
------------
To run this project please clone this repo and run the following command to install all dependencies. 

```
 pip install -r requirements.txt
```
You will also need to install the built-in functions by running the following command

```
pip install --editable .
```

Project Material
------------

Most of this project is built in Jupyter Notebook. All notebooks have been created in a logical order that let's you follow the project. Any functions created in the notebooks will be stored in the "src" folder.



Project Organization
------------

This project was created using Cookiecutter. For more information you can checkout [this article](https://medium.com/@rrfd/cookiecutter-data-science-organize-your-projects-atom-and-jupyter-2be7862f487e).

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
