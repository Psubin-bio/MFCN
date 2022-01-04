## Automated Precision Localization of Peripherally Inserted Central Catheter Tip through Model-Agnostic Multi-Stage Networks

we release MFCN evaluation code.    
Collaborators: Kyung-su Kim, Myung Jin chung, Yoon Ki Cha, Subin Park   
Detailed instructions for testing the image are as follows.   


MFCN is Multi-stage Networks that improves PICC tip detection performance through multi-fragment phenomenon improvement.   
Multi fragment phenomenon (MFP) is a phenomenon in which some breaks occur in the predicted line when segmenting the sparse PICC area, making it difficult to accurately detect the catheter tip.   
Each model can be used Model-Agnostic, but it is a code that applies FCDenseNet with the best performance among the current popular segmentation models through experiments.    
MFCN consists of a total of three stages. The first stage is the conventional method, the second stage is the Patch-wise PICC segmentation network, and the third stage is the Line reconnection network that can directly solve the MFP.


## Environments
the setting of the virtual environment we used is described as pytorch_MFCN.yml

## segmentation
