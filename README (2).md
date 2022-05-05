
# Opendataset


Opendatasets is a python library which is used for downloading the online sources datasets like Kaggle and GoogleDrive


## Installation



```bash
!pip Install opendatasets

```
    
## Download the Dataset

To download this dataset use this library

```bash
  import opendatasets as od
  datasets = 'https://www.kaggle.com/datasets/sumansid/facemask-dataset'
  od.download(datasets)
```



## Kaggle Credentials

1. sign in to https://www.kaggle.com/
After that click to your profile picture on the top right and select my Account from the menu

2. Scroll down to 'API' section and click 'Create New API Token'. This is will download the kaggle.json
 with the following contents:

 {"username":"karan55","key":"b50d51f2d89cef64c0885c6e21346010"}

After that enter the details in jupyter notebook and continue.
