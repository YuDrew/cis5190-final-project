# Improving Amazon Recommendations with Sparse Data

**Authors**: Hassan Hammoud, Andrew Yu, Venugopal Chillal

## Main Code
- `baseline.ipynb` - has baseline results
- `ALS.ipynb` - has ALS code and results
- `SAR.ipynb` - has SAR code and results
- `lightgcn/lightgcn.ipynb` - has LightGCN code, results are listed in different results CSVs
- `ratings_Electronics.csv.bz2` - has the original data zipped via bz2

## Replicating Our Code

### Setting up your python environment
If necessary, spin up a new virtual env and seed it with our `requirements.txt`.

### Baseline
You should be able to run the baseline notebook directly, given that your virtual environment has all necessary packages. 

### SAR
You should be able to run the SAR notebook directly, given that your virtual environment has all necessary packages. 

### ALS
To run ALS properly, you should set it up in Sagemaker or another Pyspark compatible environment. 

### LightGCN
You should be able to run the SAR notebook directly, given that your virtual environment has all necessary packages. 
Note that the notebook will create three folders: `yamls` to store .yaml files of hyperparameter combinations, `embeddings` to store embeddings from models run, and `models`, which stores models.