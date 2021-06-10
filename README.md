### PocketNet: A Smaller Neural Network For Medical Image Analysis

Code and materials for:

Celaya, A., Actor, J. A., Muthusivarajan, R., Gates, E., Chung, C., Schellingerhout, D., Riviere, B., Fuentes, D. PocketNet: A Smaller Neural Network for 3D Medical Image Segmentation. In Medical Image Computing and Computer Assisted Intervention -- MICCAI 2021 (2021). Submitted.

<https://arxiv.org/abs/2104.10745>

#### Data
---
MICCAI Liver and Tumor Segmentation Challenge 2017 dataset (LiTS) - <https://competitions.codalab.org/competitions/17094#learn_the_details-overview>

Neurofeedback Skull-stripped repository (NFBS) - <http://preprocessed-connectomes-project.org/NFB_skullstripped/>

MICCAI Brain Tumor Segmentation Challenge 2020 dataset (BraTS) - <https://www.med.upenn.edu/cbica/brats2020/registration.html>

#### Usage instructions
---
1) Download each dataset and save to a directory of your choice.
2) Preprocess the data with ```preprocess.ipynb```
3) Train models using ```train_pocketnet.ipynb```
4) Train for model saturation using ```saturation.ipynb```
4) Run performance profiling with ```performance_profile.ipynb```

A generic implementation of each architecture (pocket and non-pocket versions) is available in ```pocketnet.ipynb```. 