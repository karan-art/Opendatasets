# Opendatasets

Opendatasets is a python library which is used for downloading the online sources datasets like Kaggle and GoogleDrive


Install the Library
!pip install opendatasets

Download the Dataset
import opendatasets as od
dataset = 'https://www.kaggle.com/datasets/sumansid/facemask-dataset'
od.download(dataset)


