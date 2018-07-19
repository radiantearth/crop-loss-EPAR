# Crop loss estimation using multispectral satellite imagery


## Installation
Create a conda environment (or virtual environment) using `environment.yml`. 

Activate the environment:

```$ source activate [NameOfEnv]```

Enable Jupyter notebook wihtin the environment:

```
$ conda install ipykernel --name [NameOfEnv]
$ python -m ipykernel install
```

Install [npm](https://www.npmjs.com/get-npm).

Then, enable widgets and leaflet in in Jupyter notebooks:

```
$ jupyter nbextension install --py --symlink --sys-prefix widgetsnbextension
$ jupyter nbextension enable --py --sys-prefix widgetsnbextension
$ jupyter nbextension install --py --symlink --sys-prefix ipyleaflet
$ jupyter nbextension enable --py --sys-prefix ipyleaflet
```