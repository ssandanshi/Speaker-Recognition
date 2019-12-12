# Speaker-Recognition
Code for CSC591 Machine Learning for User Adaptive Systems Self Selected Project: Speaker Identification Embedding generation
Group ID: ALL_8 . Group Members:
Chengyuan Liu (cliu32@ncsu.edu) 
Rachit Shah (rshah25@ncsu.edu)
Sourabh Sandanshi (ssandan@ncsu.edu)

Three Notebooks have tthe following Purpose - 

CSC_591_G8_Speaker_Recognition.ipynb - This is the main code for preprocessing and training the embedding model.
<br>
Speaker_Recognition_Baseline.ipynb - this has code to build baseline models.
<br>
Speaker_Recognition_HMM.ipynb - thtis has code for HMM-GMM

Best way to run the notebook is using google colab. Open the notebook and colab at https://colab.research.google.com. You can find link to the colab notebook when you open the notebook in gitthub or locally. Or you can run locally on jupyter.

As the Data set takes too much time for preprocessing, we have saved the Extractetd features as npy files. This can be found in subset3_npy.zip file. Here is a link to file [LINK TO FILE] . add the file to your drive root folder.

We are also providing three model saved weights. The link to them are as follows. Add them to your drive to use.

model_4000_2.21986.h5 is weights for only triplet loss. Link - 
model_8000_1.72135.h5 is weights right after pretraining. Link -
model_1152_0.21762_0.17803.h5 is weights for pretraining + triplet loss. Link - 

similar to subsett3_npy.zip, we also have a subset of data which is used to fit and compute accuracy of baseline and final embedding models. This file is named vox_test_npy.zip. Here is a link to file [LINK TO FILE] . add the file to your drive root folder.

There is code in the notebooks to unzip the zip files if used from google colab. If using locally, you may need to remove the copy command from google drive to local env.
