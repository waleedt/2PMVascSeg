# 2PMVascSeg

Code for vascular segmentation of large-scale cerebral two-photon microscopy angiograms.

**environment.yaml** lists dependencies used to run this code on a Nvidia Titan Xp GPU.


# Training new model
The folder **Train_new_model/network** contains the code for training the network. 

In order to train the model, the data can be downloaded from the following google drive link:
https://drive.google.com/open?id=1BIJFx8zs0IT1UX4AvgnHCj8k6dYh93o3

Download the 'data' folder from the above link and copy it to the 'Train_new_model' folder, such that it's path is **.../Train_new_model/data**.

In the folder *Train_new_model/network**, execute the script main.py with default configurations as follows:

$ python main.py -d



