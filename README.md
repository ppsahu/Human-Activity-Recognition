# Human-Activity-Recognition
This project is to build a model that predicts the human activities such as Walking, Walking Upstairs, Walking Downstairs, Sitting, Standing or Laying.

Original Source of dataset: https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones

If you want to have the zip file, download from here:
https://drive.google.com/file/d/118toouH8ifByKJHmmowyjOjGyir-YAvi/view

To load the dataset into jupyter notebook, follow the below code and extract the zip file.

(Source: https://stackoverflow.com/questions/34734714/ipython-jupyter-uploading-folder)

import zipfile as zf

files = zf.ZipFile("ZippedFolder.zip", 'r')

files.extractall('directory to extract')

files.close()
