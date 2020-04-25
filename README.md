# Common Genes Between Different Cancer Types

This project aims to identify the common genes between five different types of cancer: Breast Invasive Carcinoma (BRCA), Kidney Renal Clear Cell Carcinoma (KIRC), Colon Adenocarcinoma (COAD), Lung Adenocarcinoma (LUAD), and Prostate Adenocarcinoma (PRAD).

# # Dataset Source 
The dataset is obtained from UCI reprasatory form the following link:
https://archive.ics.uci.edu/ml/datasets/gene+expression+cancer+RNA-Seq

# #Data Preprocessing 
1. Data Labeling by combining the data file and the label file based on the sample id. 
2. Splitting the dataset into 5 different files where each file represents all the samples related to spcific cancer.
3. Balancing the data by random undersamplling. 

# # Identifying the Common Genes
In order to identify the common genes between the different cancer types we need to identify the genes that are highly correlted with each cancer type since we have 20,000 genes some of them are not expressed or slightly expressed. After identifying those genes we found the common genes between these cancer types. 
