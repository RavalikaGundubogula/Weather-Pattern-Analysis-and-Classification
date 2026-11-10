# Weather Pattern Analysis and Classification Using Unsupervised Clustering Algorithms

B.Tech Artificial Intelligence and Data Science – Mini Project (Unsupervised Learning Algorithms)

Clusters real daily weather observations with **K-Means**, **Agglomerative Hierarchical Clustering** and **DBSCAN**, evaluated with Silhouette Score and Davies-Bouldin Index.

## Run in Google Colab
Upload `Weather_Pattern_Clustering.ipynb` to https://colab.research.google.com and choose *Runtime → Run all*. The dataset downloads automatically; no installs are needed.

## Contents
- `Weather_Pattern_Clustering.ipynb` – complete executed notebook
- `Weather_Pattern_Analysis_Report.docx` – full project report
- `output_graphs/` – generated graphs
- `results.json` – numeric results from the run

## Dataset
Rain in Australia (weatherAUS), source: Australian Bureau of Meteorology (http://www.bom.gov.au/climate/data).
Kaggle: https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package
Downloaded by the notebook from https://raw.githubusercontent.com/tvdboom/ATOM/master/examples/datasets/weatherAUS.csv
The data file is not redistributed in this repository.

## Results (5,000-day sample)
| Algorithm | Clusters | Noise | Silhouette | Davies-Bouldin |
|---|---|---|---|---|
| K-Means | 3 | 0 | 0.249 | 1.355 |
| Agglomerative (Ward) | 3 | 0 | 0.192 | 1.580 |
| DBSCAN | 2 | 85 | 0.310* | 0.796* |

*non-noise points only. See the report for interpretation.
