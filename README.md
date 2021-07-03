# Human-Activity-Recognition
This project is to build a model that predicts the human activities such as Walking, Walking Upstairs, Walking Downstairs, Sitting, Standing or Laying.


If you want to have the dataset, download the zip file.

To load the dataset into jupyter notebook, follow the below code and extract the zip file.

import zipfile as zf
files = zf.ZipFile("ZippedFolder.zip", 'r')
files.extractall('directory to extract')
files.close()

Source: https://stackoverflow.com/questions/34734714/ipython-jupyter-uploading-folder

