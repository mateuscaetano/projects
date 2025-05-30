# Assessment Exercise 

This repo contains an analysis of the MovieLens 100k dataset, including code for a Recommender System and Anomaly Detection

The exploratory analysis is in the [Exploratory_Analysis.ipynb](Exploratory_Analysis.ipynb) file

The main recommender is in the [Cornac.ipynb](Cornac.ipynb) file

The anomaly detection  is in the [anomaly_detection.ipynb](anomaly_detection.ipynb) file

### Downloading the data

The data can be downloaded using the surprise library

```python
from surprise import Dataset
data = Dataset.load_builtin('ml-100k')
```

And then copying the .surprise_data folder to the project folder

### Setup

Requires Miniconda or Anaconda

### Conda Environment Commands 

conda env create -f environment.yml

conda activate .venv

conda env update -f environment.yml

conda env remove --name myenv