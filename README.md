
![Mortalidad](https://github.com/Yansol23/Mortalidad_Segun_las_Principales_Causas_de_Muerte-Grupos_de_Edad_y_Sexo/blob/main/reports/figures/Mortalidad.png)






## Tecnicatura Superior en Ciencias de Datos e Inteligencia Artificial.

**Politécnico Superior Malvinas Argentinas.**

**Materia:** Aprendizaje Automático

**Docente:** Lic. Mirabete Martin
*****************************************************************************


**Nombre del Proyecto:** Mortalidad, según las principales causas de muerte, grupos de edad y sexo.


*****************************************************************************

Objetivo:

Utilizando técnicas de Aprendizaje Automático, desarrollar un modelo de clasificación que identifique las principales causas de mortalidad en la provincia de Tierra del Fuego basándose en variables demográficas, como edad, género y año.
******************************************************************************
Contexto y Relevancia del Problema

La información analizada proviene de datos sobre mortalidad en Tierra del Fuego, Argentina, durante los años 2005-2019. Este conjunto de datos incluye tasas de mortalidad, número de fallecimientos y principales causas de muerte, variando según edad, género y otros factores.

Este análisis es importante porque conocer las principales causas de muerte ayuda a planificar políticas de salud, asignar recursos y crear campañas de prevención y tratamiento más efectivas. En un contexto de recursos limitados, entender cómo varían estas causas en distintos grupos permite a las autoridades de salud actuar de manera más precisa.

Usar aprendizaje automático para clasificar estas causas puede automatizar y mejorar la comprensión de estos patrones, ayudando a crear políticas de salud más específicas y efectivas.
*****************************************************************************
Preguntas de Investigación o Hipótesis
Para llevar a cabo este análisis de clasificación mediante técnicas de aprendizaje automático, definimos las siguientes preguntas de investigación y posibles hipótesis que queremos explorar.
   1. ¿Qué factores determinan la causa de muerte de una persona joven (menor de 40 años) en comparación con una persona de la tercera edad (mayor de 65 años)?
   2. ¿Qué variables (como grupo de edad, género, y año) tienen un mayor impacto en la clasificación de la causa de muerte de una persona?
   3. ¿Es posible predecir la causa de muerte de un individuo con base en variables como edad, género, y tendencias históricas?

*****************************************************************************
**Autora:** Barrios, Yanina Soledad

![Perfil](https://github.com/Yansol23/Mortalidad_Segun_las_Principales_Causas_de_Muerte-Grupos_de_Edad_y_Sexo/blob/main/reports/figures/Autora.png)


<p align="center">
  <img src="https://komarev.com/ghpvc/?username=edfedo" alt="Vistas de perfil" />
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT" />
  </a>
</p>




Project Organization
------------

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
