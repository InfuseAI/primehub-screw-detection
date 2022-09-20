# primehub-screw-detection

PrimeHub End-to-end tutorial: Use screw dataset to build up a MLOps pipeline.

## How to use?

### Step 1: Choose the Jupyter Notebook.

There are two notebook in this project. 
You need to choose the suitable version of notebook when you start the tutorial.
One is online version, which can download the data from kaggle and install the python package.
Another is airgapped version. You need to prepare the jupyter docker image and dataset by yourself.

### Step 2: Setting the variable and run the notebook. 

```
# Kaggle related variable
kaggle_username
kaggle_key

# The export file from label studio json-formatted output.
label_data_file
```

### Step 3: Run the jupyter notebook code.

You can get the result in Notebook and model in mlflow.