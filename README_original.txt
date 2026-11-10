WEATHER PATTERN ANALYSIS AND CLASSIFICATION USING UNSUPERVISED CLUSTERING ALGORITHMS
Subject: Unsupervised Learning Algorithms (B.Tech AI and Data Science)

FILES
 Weather_Pattern_Analysis_Report.docx  Editable Word report (fill the [placeholders]: name, college, guide, etc.)
 Weather_Pattern_Clustering.ipynb      Complete notebook (already executed, outputs and graphs are saved inside)
 output_graphs/                        11 PNG graphs produced by the notebook
 results.json                          Numeric results written by the notebook (used to write the report)
 README.txt                            This file

DATASET
 Rain in Australia (weatherAUS) - daily observations of the Australian Bureau of Meteorology.
 Original source : http://www.bom.gov.au/climate/data
 Kaggle page     : https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package
 Direct download : https://raw.githubusercontent.com/tvdboom/ATOM/master/examples/datasets/weatherAUS.csv
 The notebook downloads it automatically (no login, no manual upload).
 dataset.csv is NOT bundled: the redistribution terms of the Bureau of Meteorology data are not clearly stated.
 The notebook saves a cleaned local copy (dataset_cleaned_features.csv) when you run it.

HOW TO RUN IN GOOGLE COLAB
 1. Open https://colab.research.google.com -> File -> Upload notebook -> choose Weather_Pattern_Clustering.ipynb
 2. Runtime -> Run all (takes about 1-2 minutes). No pip install is needed.
 3. Graphs are saved in the output_graphs folder of the Colab session (left Files panel). Download them if needed.

HOW TO RUN LOCALLY
 pip install pandas numpy matplotlib seaborn scikit-learn scipy jupyter
 jupyter notebook Weather_Pattern_Clustering.ipynb    (internet is required for the download)

NOTES
 - Only unsupervised algorithms are used: K-Means, Agglomerative (Ward), DBSCAN. No labels, no supervised models.
 - All three algorithms use the same random sample of 5,000 days (seed 42). Results are reproducible.
 - In the Word report right-click the Table of Contents -> Update Field to fill page numbers
   (Word may also offer to update fields when the file is opened - choose Yes).
