# COMPUTER-AIDED MELANOMA DETECTION USING MACHINE LEARNING TECHNIQUES

Here are four notebooks that I created for my term paper that was dedicated to the application of neural network models for melanoma detection.

I trained several models on the same dataset to compare different approaches:

•	Simple neural network with fully connected 

•	Convolutional Neural Network

•	Transfer learning algorithms with prebuilt architecture (Inception, MobileNet, Xception)

For all models input size of images was 256x256x3. As an optimizer was used stochastic gradient descent (Adam optimizer), and categorical crossentropy as a loss function. After the training of the model, the best coefficients were saved to be used later for evaluation.

Data source: ISIC dataset (The International Skin Imaging Collaboration, https://www.isic-archive.com).  
I used 5 535 images of benign and malignant moles for experiments (including 200 images for testing). 

Overall transfer learning demonstrated better result that fully-connected neural network and convolutional neural network. Inception proved the most accurate result in the test set among other models that were compared (Inception – 81.5%, Exception – 78.5%, MobileNet – 74.5%, CNN – 73%, fully-connected NN – 71%). Results on the training set appeared to be more accurate than on the test set for all models except of Inception.
Number of false negative cased is also an important metric as no diagnosis of melanoma, when it takes place, can be lethal. Fully-connected NN shows the lowest number of false negative cases – 10 vs. 17 of the most accurate model. 

Main libraries: tensorflow, keras, sklearn, matplotlib, numpy, pandas
