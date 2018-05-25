# OpenML
Machine Learning Analysis using OpenML

This code for this project is split into 4 jupyter notebooks. `OpenML_Download.ipynb` is where all the data for the anlysis is downloaded from OpenML. `dataset_features.ipynb` is where the features for all datasets used in the analysis were created. These features were then used to create dataset clusters using kmeans in `dataset_cluster_analysis.ipynb`. Clusters were used to identify how different `weka` primitives varied in classification accuracy for different types of datasets. In `primitive_analysis.ipynb`, sklearn and weka primitives were evaluated in terms of adjusted accuracy across all the data. The best and worst primitives for classification were identified. Some parts of the download and analysis were conducted using Brown CCV to handle the large amount of data and code for that is included in the notebooks. 

The data associated with this project can be downloaded [here][download-url]

[download-url]: https://brownbox.brown.edu/download.php?hash=de911e03

The file is 0.5 GB compressed and 5.7 GB once uncompressed
