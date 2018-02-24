# Dog-Breed-Classifier
This project is to apply Convolutional Neural Networks (CNN) to recognize dog breeds.

The project is first to build a CNN that is trained by 6 thousand images. The CNN is constructed of 3 pairs of Conv2D/MaxPooling layers. In which the Conv2D has 16,32, 64 filters respectively to detect the different level of patterns. In the end, a GlobalAveragePooling2D is applied to flatten the data and use a full layer with 133 nodes for classification of the breed type.

The second step of the project is use transfer learning from a pre-trained model such as VGG-19, ResNet-50, or Xception. I picked ResNet-50 which has an accuracy of 82%.
