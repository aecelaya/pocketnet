### PocketNet: A Smaller Neural Network For Medical Image Analysis

**This is old code. Updated code is at <https://github.com/aecelaya/MIST>.** 

Please cite the following if you use this code for your work:

> A. Celaya et al., "PocketNet: A Smaller Neural Network For Medical Image Analysis," in IEEE Transactions on Medical Imaging, doi: 10.1109/TMI.2022.3224873.

#### Data
---
MICCAI Liver and Tumor Segmentation Challenge 2017 dataset (LiTS) - <https://competitions.codalab.org/competitions/17094#learn_the_details-overview>

Neurofeedback Skull-stripped repository (NFBS) - <http://preprocessed-connectomes-project.org/NFB_skullstripped/>

MICCAI Brain Tumor Segmentation Challenge 2020 dataset (BraTS) - <https://www.med.upenn.edu/cbica/brats2020/registration.html>

COVIDx8B dataset - <https://github.com/lindawangg/COVID-Net/blob/master/docs/COVIDx.md>

#### Usage instructions
---
1) Download each dataset and save to a directory of your choice.
2) Preprocess the data with ```preprocess.ipynb```
3) Train models using ```train_pocketnet.ipynb```
4) Train for model saturation using ```saturation.ipynb```
4) Run performance profiling with ```performance_profile.ipynb```

A generic implementation of each architecture (pocket and non-pocket versions) is available in ```pocketnet.ipynb```. 
