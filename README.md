<p align="center">
  <a href="https://github.com/XpressAI/xircuits/tree/master/xai_components#xircuits-component-library-list">Component Libraries</a> •
  <a href="https://github.com/XpressAI/xircuits/tree/master/project-templates#xircuits-project-templates-list">Project Templates</a>
  <br>
  <a href="https://xircuits.io/">Docs</a> •
  <a href="https://xircuits.io/docs/Installation">Install</a> •
  <a href="https://xircuits.io/docs/category/tutorials">Tutorials</a> •
  <a href="https://xircuits.io/docs/category/developer-guide">Developer Guides</a> •
  <a href="https://github.com/XpressAI/xircuits/blob/master/CONTRIBUTING.md">Contribute</a> •
  <a href="https://www.xpress.ai/blog/">Blog</a> •
  <a href="https://discord.com/invite/vgEg2ZtxCw">Discord</a>
</p>





<p align="center"><i>Xircuits Component Library to interface with TensorFlow Keras! Build and deploy deep learning solutions with ease.</i></p>

---
## Xircuits Component Library for TensorFlow Keras 

Integrates TensorFlow Keras into Xircuits for streamlined deep learning workflows. Simplifies model design, training, and deployment with reusable components. Reduces complexity and accelerates development for scalable AI solutions.

## Table of Contents

- [Preview](#preview)
  
- [Prerequisites](#prerequisites)
- [Main Xircuits Components](#main-xircuits-components)
- [Try the Examples](#try-the-examples)
- [Installation](#installation)

## Preview

### TFKerasTransferLearning Example

<img src="https://github.com/user-attachments/assets/78f3460f-a9a0-4f1d-a1cf-ed0104c6a81b" alt="TFKerasTransferLearning example" />


### TFKerasTransferLearning Result

<img src="https://github.com/user-attachments/assets/b16a84f2-8eaf-4f47-8af2-5326c148c34f" alt="TFKerasTransferLearning result"  />

### TFKerasTrainImageClassifier Example

<img src="https://github.com/user-attachments/assets/9abbdecd-3b26-454c-b40f-8e9aac9f2383" alt="TFKerasTrainImageClassifier_Example" />

### TFKerasTrainImageClassifier Result

<img src="https://github.com/user-attachments/assets/6fd41596-aa0e-45bd-98e2-34b2baf0b5dd" alt="TFKerasTrainImageClassifier_Result" />

### TFKerasModelPredict Example

<img src="https://github.com/user-attachments/assets/80946c8e-dc45-40ba-be6c-1bee31371062" alt="TFKerasModelPredict_example"  />


### TFKerasModelPredict Result

<img src="https://github.com/user-attachments/assets/c9b863b4-6b66-42a2-94a3-0c9d027dec9a" alt="TFKerasModelPredict_result"  />


## Prerequisites

Before you begin, you will need the following:

1. Python3.9+.
2. Xircuits.

## Main Xircuits Components 

### KerasCreate1DInputModel:  
Creates 1D Keras models for datasets with 1D input structures.

<img src="https://github.com/user-attachments/assets/cf3c5bf4-b2ea-48e3-b964-e3fe2dbffd38" alt="KerasCreate1DInputModel" width="200" height="75" />


### KerasCreate2DInputModel:  
Assembles 2D Keras models, ideal for image-based datasets.  

<img src="https://github.com/user-attachments/assets/def84826-5549-4de4-90c2-d01eaad9dc36" alt="KerasCreate2DInputModel" width="200" height="75" />


### KerasTrainImageClassifier:  
Trains Keras models for image classification tasks. 

<img src="https://github.com/user-attachments/assets/1eeca792-d7d0-40fb-b689-f352bca59999" alt="KerasTrainImageClassifier" width="200" height="100" />


### KerasEvaluateAccuracy:  
Evaluates Keras models for accuracy and loss using test datasets.  

<img src="https://github.com/user-attachments/assets/489b6f59-df84-4120-bc6d-64eec7ef6625" alt="KerasEvaluateAccuracy" width="200" height="100" />


### KerasTransferLearningModel:
Fetches TensorFlow Keras Models for transfer learning.

<img src="https://github.com/user-attachments/assets/5b98def2-87fe-4a92-8680-a2a5822210d6" alt="KerasTransferLearningModel" width="200" height="250" />


### TrainKerasModel:
Trains compiled Keras models with training data.

<img src="https://github.com/user-attachments/assets/7e2b8507-c31c-415a-81a0-c00ee1194e8a" alt="TrainKerasModel" width="200" height="150" />


## Try the Examples

We have provided an example workflow to help you get started with the TensorFlow Keras component library. Give it a try and see how you can create custom TensorFlow Keras components for your applications.

### TFKerasTransferLearning

Demonstrates transfer learning with MobileNetV2 pre-trained on ImageNet to classify the "cats_vs_dogs" dataset, evaluate accuracy, and save the model.

### TFKerasTrainImageClassifier

This workflow trains a 2D convolutional model on a dataset, evaluates its accuracy, and demonstrates basic image classification.

### TFKerasModelPredict

Uses the pre-trained ResNet50 model to classify an input image and predict its class label.

## Installation
To use this component library, ensure that you have an existing [Xircuits setup](https://xircuits.io/docs/main/Installation). You can then install the TensorFlow Keras library using the [component library interface](https://xircuits.io/docs/component-library/installation#installation-using-the-xircuits-library-interface), or through the CLI using:

```
xircuits install tensorflow_keras
```
You can also do it manually by cloning and installing it:
```
# base Xircuits directory
git clone https://github.com/XpressAI/xai-tensorflow-keras xai_components/xai_tensorflow_keras
pip install -r xai_components/xai_tensorflow_keras/requirements.txt 
```
