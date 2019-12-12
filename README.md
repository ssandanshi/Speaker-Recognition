# Speaker-Recognition
CSC591 Machine Learning for User Adaptive Systems Self Selected Project: Speaker Identification Embedding generation
<br>
Group ID: ALL_8 . 
<br>
Group Members:
<br>
Chengyuan Liu (cliu32@ncsu.edu) <br>
Rachit Shah (rshah25@ncsu.edu)<br>
Sourabh Sandanshi (ssandan@ncsu.edu)<br>

Three Notebooks have the following Purpose - 

CSC_591_G8_Speaker_Recognition.ipynb - This is the main code for preprocessing and training the embedding model.
<br>
Speaker_Recognition_Baseline.ipynb - this has code to build baseline models.
<br>
Speaker_Recognition_HMM.ipynb - thtis has code for HMM-GMM

Best way to run the notebook is using google colab. Open the notebook and colab at https://colab.research.google.com. You can find link to the colab notebook when you open the notebook in gitthub or locally. Or you can run locally on jupyter.

As the Data set takes too much time for preprocessing, we have saved the Extractetd features as npy files. This can be found in subset3_npy.zip file. Here is a link to file [LINK TO FILE](https://drive.google.com/open?id=13x5mgth1FR0244i-45B5JZEY2oLSPRl2) . add the file to your drive root folder.

We are also providing three model saved weights. The link to them are as follows. Add them to your drive to use.

model_4000_2.21986.h5 is weights for only triplet loss. Link -  https://drive.google.com/open?id=10iyqdx7ks9nKY2THY1HFOxJ-rsxBQWFA
model_8000_1.72135.h5 is weights right after pretraining. Link - https://drive.google.com/open?id=11dPSCQrpaJcG5xeOvo4dvxSRbqmCWhs6
model_1152_0.21762_0.17803.h5 is weights for pretraining + triplet loss. Link - https://drive.google.com/open?id=105-GWQ4xCXCvylMX0_02Bt-ltI90uEfh

similar to subsett3_npy.zip, we also have a subset of data which is used to fit and compute accuracy of baseline and final embedding models. This file is named vox_test_npy.zip. Here is a link to file [LINK TO FILE](https://drive.google.com/open?id=1-614iq2PzXvN0p8J3rGmuIxsUaKlhUfS) . add the file to your drive root folder.

There is code in the notebooks to unzip the zip files if used from google colab. If using locally, you may need to remove the copy command from google drive to local env.
