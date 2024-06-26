# CIFAR-10 Image Classification Based on Modified ResNet Model
## Introduction
Image classification is one of the most fundamental tasks of computer vision. In this study, we defined a ResNet model that incorporates residual blocks into a normal convolutional neural network and includes 32 parameter layers to improve the accuracy of classification for CIFAR-10 images. The model was trained for 50 epochs on the Google Colab platform, leveraging data preprocessing techniques such as random flipping and cropping, and advanced training strategies including cosine annealing for learning rate adjustment and label smoothing to refine loss functions. The architecture integrates two 3x3 convolution layers followed by batch normalization and ReLU activation to effectively capture complex patterns within the dataset while managing computational efficiency. Residual blocks with skip connections were employed to mitigate degradation issues, enhancing training performance without compromising the depth of the network. The number of total parameters is 4,693,962. Results demonstrated a consistent reduction in training and test loss. The accuracy for the validation batch in CIFAR-10 dataset reached 92%.  In the test dataset, the accuracy of our modified ResNet was 83.4%.

## Requirment
- Python 3.7+
- PyTorch
- Matplotlib
- Numpy
- Pandas



