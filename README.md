# gruenstattgrau
This is a NLP data science project that scans a set of text web sources and tries to answer business questions such as:

- What social motivations are the main drivers in the context the implementation of greening projects are called? (Reasons pro / contra building greening)
- Which attitudes are there in the public / different Target groups for building greening? ... to photovoltaic in combination with Green roof?
- Which greening projects / lighthouse projects are in the past Years in Europe?
- Which key persons / influencers / politicians / companies can work for the greening industry are identified and how are these among themselves networked?
- What are the objectives of municipalities, cities, countries in the context the building greening?
- What problems / obstacles is the industry struggling with?
- Future significance of building greening
- Awareness of building greening among different stakeholders?
- Survey of potential areas for green roofs
- Funding opportunities for greening projects
- Qualification programs in the green building sector
- Which purchase price increase for buildings arise Green roof installations?

# Data sources:
- [Purchase price collection for Vienna real estate (CSV)](https://www.data.gv.at/katalog/dataset/5fc523d5-c299-4d97-889f-01ed247b10fa)
- [Number and performance of photovoltaic systems Vienna / Lower Austria / Styria](https://www.data.gv.at/suche/?search-term=photovoltaik&searchIn=catalog)
- https://owncloud.zinco.de/owncloud/index.php/s/yxd3iD1KU7UJqir
- [Optigrün - Downloads -  Presseberichte, Mitteilungen, Fachbeiträge](https://www.optigruen.at/aktuelles/download-presse-at/)
- [Optigrün - Prospekte - Magazin: "Der Dachbegrüner" - Das Magazin für Dach-, Fassaden- und Innenraumbegrünung](https://www.optigruen.at/downloads/prospekte/)
- [BUGG - Downloads - Fachinfos, Symposien, Vorträge](https://www.gebaeudegruen.info/service/downloads/)
- [DEGA Galabau - Magazin für Garten und Landschaftsbau - Gratis Archiv bis 2006](https://www.dega-galabau.de/Magazin/Archiv)
- [Schweizerische Fachvereinigung Gebäudebegrünung - Downloads - Fachartikel](http://www.sfg-gruen.ch/index.php?page=398)
- [Galabau Journal - Freies Onlinearchiv bis 2010](https://www.galabau-verband.at/index.php/journal/artikel-pdf-downloads)
- [Gründachpotentialkataster Wien](https://www.data.gv.at/katalog/dataset/44bc24a1-b7e2-484f-b1e3-6884ff9b90d7)
- [Bauder - Referenzliste - Online Projektbeschreibungen mit Standort, m², Jahr,…](https://www.bauder.at/at/dachbegruenung/referenzen.html)
- [Optigrün - Referenzliste - Online Projektbeschreibungen mit Standort, m², Jahr,…](https://www.optigruen.at/referenzen/)
- [BUGG - News - Online News](https://www.gebaeudegruen.info/aktuelles/news/)
- [BUGG - Blog - Online Blog](https://www.gebaeudegruen.info/aktuelles/blog/)


# Offline resources:
- Magazin Dach Grün
- Jahrbücher Bauwerksbegrünung FBB 2014-2017
- 

## Usage
We're using [pipenv](https://docs.pipenv.org) to generate the environment.
Please install it and run
```bash
pipenv install
```

and then
```bash
pipenv shell
```

to have the environment with all the dependencies.

For linting, please use [black](https://github.com/ambv/black) through the Visual studio code or by running
```bash
black .
```


Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │    ├── external   <- Data from third party sources.
    │    ├── interim    <- Intermediate data that has been transformed.
    │    ├── processed  <- The final, canonical data sets for modeling.
    │    └── raw        <- The original, immutable data dump.
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
    │   │
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.testrun.org


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
