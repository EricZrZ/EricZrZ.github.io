# 2023-05-26-neural_network_weights

Today, I learned how to visualize the neural network weights in each layer of the model. Actually, all machine learning models can be fully understood. 
After understanding this, I will not treat the deep learning model as a black box.

In 2013, Matt Zeiler proposed the method ["Visualizing and Understanding Convolutional Networks"](https://arxiv.org/pdf/1311.2901.pdf) 
to deal with the visualization of neural network weights in each layer of the deep learning model. 

The first layer is shown below, the reconstructed weight pictures are shown in the image with grey background. The bottom section is training images that are matched with the weights.

<img src="/images/layer1.jpg" width = "200" height = "200" alt="" align=center />

In layer 2, the figure below shows that the model finds nine examples of weight reconstructions for each feature. The feature detectors are built by the model and can be used to look for lines, circles, and corners.

<img src="/images/layer2.jpg" width = "400" height = "200" alt="" align=center />

The figure below shows the results of reconstructing features in layer 3.

<img src="/images/layer3.jpg" width = "400" height = "200" alt="" align=center />

In layers 4 and 5, the features can be identified and match the high-level semantic components, like wheels, dogs, cars, etc.

<img src="/images/layer4.jpg" width = "500" height = "200" alt="" align=center />

Click here [links](https://github.com/fastai/fastbook/blob/master/01_intro.ipynb) to see details
