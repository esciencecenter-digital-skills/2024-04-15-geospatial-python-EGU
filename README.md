# Introduction to Geospatial Raster and Vector Data with Python

Material for the [EGU24 Short Course 6.4](https://meetingorganizer.copernicus.org/EGU24/session/49444)

## Links

* Introductory slides TODO: upload slides and link them here
* [Jupyter notebook](./geospatial-python.ipynb)  
* [Presentation (notebook)](https://esciencecenter-digital-skills.github.io/2024-04-15-geospatial-python-EGU)

## Run the tutorial

Click on one of the following badges in order to run the tutotial on Mybinder.org or Google Colab (a Google account is required for the latter):

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/esciencecenter-digital-skills/2024-04-15-geospatial-python-EGU/HEAD?labpath=geospatial-python.ipynb) 
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/esciencecenter-digital-skills/2024-04-15-geospatial-python-EGU/blob/main/geospatial-python.ipynb)

## Run the tutorial locally

Clone and access this repository:

```shell
git clone https://github.com/esciencecenter-digital-skills/2024-04-15-geospatial-python-EGU.git
cd 2024-04-15-geospatial-python-EGU
```

In order to run the tutorial, some Python dependencies need to be installed. Python>=3.X is required (it can be downloaded from [here](https://www.python.org/downloads/)).

It is best to install dependencies in an isolated environment, which can be created in the following way:

```shell
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Note that every time a new shell is started, one needs to run `source venv/bin/activate` to activate the environment. 

Start JupyterLab by running:

```shell
jupyter-lab
```

JupyterLab should start in a new broweser window, if this does not happen navigate to this address: http://localhost:8888/lab 

Open the notebook `geospatial-python.ipynb` using the file browser in the left tab.
