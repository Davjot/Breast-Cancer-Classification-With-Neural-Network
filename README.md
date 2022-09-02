# Breast-Cancer-Classification-With-Neural-Network

![breast_cancer_classification_dataset](https://user-images.githubusercontent.com/71970250/188055612-8a2465bd-cd21-4d00-9737-b68b41e1493f.jpg)

The dataset is directly import from sklearn module.

0 and 1 are used to predict whether a person have a brain tumor or not in the following way:

● 0 --> The brain tumor is Benign

● 1 --> The brain tumor is Malignant 

The libraries used here are Tensorflow and Keras.

The prgram then divides the dataset into training and testing samples in 80:20 ratio randomly using train_test_split() function available in sklearn module.

Accuracy score is then calculated by comparing with the correct results of the training dataset.

Model predict function used here provides ous the two values in the output. 

● The first value provides us with the probability that the brain tumor is Malignant;

● And the second value provides us with the probability that the brian tumor is Benign.

so to predcit whether the brain tumor is benign and malignant , we use np.argmax() function to predict the output.

You can also predict the data by entereing your data according to the dataset.

For Example:

The input data taken in this case is :

11.76,21.6,74.72,427.9,0.08637,0.04966,0.01657,0.01115,0.1495,0.05888,0.4062,1.21,2.635,28.47,0.005857,0.009758,0.01168,0.007445,0.02406,0.001769,12.98,25.72,82.98,516.5,0.1085,0.08615,0.05523,0.03715,0.2433,0.06563

The given output is :

<img width="213" alt="Screenshot 2022-09-02 at 9 27 04 AM" src="https://user-images.githubusercontent.com/71970250/188056370-f352b680-a178-4c80-b529-89174e416eba.png">


