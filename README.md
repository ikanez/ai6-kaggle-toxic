# ai6-kaggle-toxic
A repository for kaggle toxic collaboration.

### data
All training, test and pretrained model

### model
Developed model
<h>Naming convention for model name: model-<algo_used>-<timestamp>-<iteration_num>
<h>ie. model-cnn-lstm-20180219-1.h5 (if keras)

### src
Source codes or jupyter notebooks.
<h>For data analysis, use naming convention: analysis-<timestamp>-<iteration_num>.ipynb
<h>For pipeline processing, model processing and predict: train-<model_name>.ipynb 


### submission
Submission files to Kaggle
<h>Naming convention: submit-<model_name>.csv

### accessing the fastai library
To access the fastai library from the working directory, you'll need to create a symlink to the fastai folder. To do this, first remove the existing fastai folder that in this repo, and add the symlink using the following command:

* `cd src; mklink /d fastai <fastai directory>; cd ..`
* e.g `cd src; mklnk /d fastai C:\Users\ikanez\Dropbox\fastai_pytorch\fastai; cd ..`
