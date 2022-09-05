# Breast-Cancer-Classification-With-Neural-Network

![breast_cancer_classification_dataset](https://user-images.githubusercontent.com/71970250/188055612-8a2465bd-cd21-4d00-9737-b68b41e1493f.jpg)

--> <b> <i> DATASET : </i> </b>

The dataset is directly imported from <b> <i> sklearn </i> </b> module.

--> <b> <i> METHODOLOGY : </i> </b>

0 and 1 are used to predict whether a person have a brain tumor or not in the following way:

● 0 --> The brain tumor is Benign

● 1 --> The brain tumor is Malignant 

The libraries used here are  <b> <i> Tensorflow </i> </b> and <b> <i> Keras </i> </b>.

The prgram then divides the dataset into training and testing samples in <b> <i> 80:20 </i> </b> ratio randomly using <b> <i> train_test_split() </i> </b> function available in <b> <i> sklearn </i> </b> module.

Accuracy score is then calculated by comparing with the correct results of the training dataset.

Model predict function used here provides ous the two values in the output. 

● The first value provides us with the probability that the brain tumor is Malignant;

● And the second value provides us with the probability that the brian tumor is Benign.

So to predict whether the brain tumor is benign and malignant , we use <b> <i> np.argmax() </i> </b> function to predict the output.

You can also predict the data by entering your data according to the dataset.
  
--> <b> <i> OUTPUT : </i> </b>
  
The given output is :

<img width="213" alt="Screenshot 2022-09-02 at 9 27 04 AM" src="https://user-images.githubusercontent.com/71970250/188056370-f352b680-a178-4c80-b529-89174e416eba.png">
