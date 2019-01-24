# CNN
**About Algorithm:**<br/>
In neural networks, Convolutional neural network (ConvNets or CNNs) is one of the main categories to do images recognition, images classifications.Deep learning CNN models to train and test, each input image will pass it through a series of convolution layers with filters (Kernals), Pooling, fully connected layers (FC) and apply Softmax function to classify an object with probabilistic values between 0 and 1<br/>
Here I have used a 2,3,5 Layer Architecture giving me various outputs.I have also added drop-outs and batch Normalisation which could help to overcome overfitting.Data trained here is MNIST data.<br/>
**Summary:**<br/>

|          Model           | Test-Loss |   Test-Accuracy   | 
| ------------- | ------------- |------------- |
|       2-Layer CNN Architecture |         0.03619625380380894           | 0.9908 |
|       3-Layer CNN Architecture         |         0.044668429520819335            |  0.9887 |
|       5-Layer CNN Architecture       |         0.05102709092050791           |  0.9905 |


