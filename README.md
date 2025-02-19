# ImageClassifier

## Cat vs. Fish Image Classifier  

This project implements an image classification model to distinguish between cats and fish using three different neural network architectures:  

1. **SimpleNet** - A basic fully connected neural network  
2. **CNNNet** - A convolutional neural network (CNN)  
3. **ResNet** - A fine-tuned ResNet50  

## Project Structure  

- `SimpleNet.ipynb`: Implements a simple feedforward neural network  
- `CNNNet.ipynb`: Implements a CNN-based model  
- `ResNet.ipynb`: Fine-tunes a pretrained ResNet50 model for classification  

## Dataset  

The dataset consists of labeled images of cats and fish. Images are preprocessed and fed into the models for training and evaluation.  

## Model Details  

### 1. SimpleNet  
- A basic neural network with fully connected layers  
- Uses ReLU activation and softmax for classification  

### 2. CNNNet  
- A convolutional neural network with multiple Conv2D layers  
- Includes max pooling and dropout for regularization  
- Uses softmax activation for classification  

### 3. ResNet50  
- Fine-tuned ResNet50 pretrained on ImageNet  
- Last few layers are replaced and trained on the custom dataset  
- Utilizes transfer learning for improved performance  

