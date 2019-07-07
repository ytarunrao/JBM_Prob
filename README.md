# JBM_Prob

Solution to find if the fender aprons are defected or healthy.

This solution is based on the Deep convolution neural network approach. DNN is used due to close similerities between the different classes as standard machine learning approach won't able to differentiate between similer look alike images. CNN is used as the data is of image type.
I used few convolution layers and flatten layer followed by fully connected layer and softmax layer for the classification. ADAM optimizer is used for the for the cost minimization. 

I trained it for only first 100 and then for 1000 iterations due to less compute power. After few more thousand iteration and with change in network achitecture by adding few more convolution layers to learn high level fearure, network can attain better accuracy and can give above 99% results.
