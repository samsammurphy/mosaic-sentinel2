## Introduction

Mosaic of atmospherically corrected, cloud-free Sentinel 2 imagery.

Uses [Google Earth Engine](https://earthengine.google.com/) and the [6S emulator](https://github.com/samsammurphy/6S_emulator/edit/master/README.md).

## Installation

Install [Anaconda](https://www.continuum.io/downloads).

If necessary, create a python3 environment

`conda create -n my_python3_env`

To use this environment, activate it as follows:

`source activate my_python3_env`

.. if on Windows the command is a bit shorter:

`activate my_python3_env`

Install the Earth Engine API:

```
pip install google-api-python-client
pip install earthengine-api 
```

Authenticate the Earth Engine API.

`earthengine authenticate`

## Usage

clone this repository

`git clone https://github.com/samsammurphy/ee-atmcorr-timeseries.git`

run the jupyter notebook

`jupyter-notebook ./ee-atmcorr-timeseries/jupyter_notebooks/ee-atmcorr-timeseries.ipynb`
