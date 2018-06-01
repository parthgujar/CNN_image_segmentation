# CNN_image_segmentation

CNN for classifying generated zener images data.

conv_train file takes the arguments as below :
```
conv_train.py <mode> <network_description> <epsilon> <max_updates> <class_letter> <model_file_name> <data_folder>
```
This file produces a graph among other statistics like Training Cost,Validation cost as well as training and validation statistics.

Possible modes are : cross, cross-l1, cross-l2, test. 

Test mode is can be used to test a already developed model using test data.

If test mode is used,  epsilon and max_updates will be required.
