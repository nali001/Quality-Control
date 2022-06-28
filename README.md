# Quality-Control
##Requirements
1.Basic libraries like numpy, pandas, seaborn, matplotlib, and scikit-learn
2.pyod 1.0.2 or higher
3.lightgbm 3.2.1 or higher
4.xgboost 1.6.0 or higher
5.sdv 0.14.0 or higher
6.ctgan 0.5.1
##Function of every notebook
1.Function-Copy2.ipynb contains all functions needed in our experiment. It performs unsupervised and supervised learning and can show the 
results.
2.Impute.ipynb is used to fill missing values and extract features.
3.Dataquality.ipynb is used to convert the raw data from software to the data we can use.
4.modelCompare.ipynb is used to compare our result with other methods. Please note that the TABNet used in this notebook has conflict with SDV, so you should make an environment to test it.
##Datasets
1.2010to2017nsWithoutNA.csv is the dataset that can be used directly with the function notebook.
2.letter.csv is used by another experiment in our research, it can also be used directly with the function notebook.
3.nsGAN.csv should be used in modelCompare notebook. Because TABNet has conflicts with SDV, we need to generate this data in advance.
