Plant Leaf Disease Detection Using Custom VGG19 CNN

This project focuses on detecting multiple plant leaf diseases using a custom-built convolutional neural network (CNN) based on the VGG19 architecture. Unlike existing models that focus on detecting diseases in a single plant leaf or use pre-trained networks, this model was built from scratch for improved versatility and performance.

Dataset
We used the PlantVillage Dataset, which contains leaf images from 14 plant species with 38 different diseases. Each image is standardized to 224x224 pixels.

Model Overview
Our approach reconstructs the VGG19 architecture without using pre-trained models, allowing for more flexibility and adaptation to the specific dataset. Key changes made to optimize the model include:

Learning Rate: Adjusted from 0.001 to 0.01.
Optimizer: Replaced Adam with Stochastic Gradient Descent (SGD).
Through these adjustments, we achieved a high validation accuracy of 97.54%, and after further tuning, we attained a final accuracy of 98.51%.
Unique Contributions
No Pre-Trained Models: This model was developed entirely from scratch, rather than leveraging existing pre-trained models like the standard VGG19.
Multi-Plant Detection: Our model detects diseases across multiple plant species, surpassing the limitations of existing systems that detect diseases in a single plant species.
GUI Implementation
A Tkinter-based GUI was developed, enabling users to drag and drop an image of a plant leaf into the application. The model then identifies and displays the disease on the screen.

Key Points

98.51% Accuracy
Supports 14 Plant Species, 38 Diseases
Custom VGG19 Architecture
GUI with Drag-and-Drop Feature.

DATASET LINK:https://www.kaggle.com/datasets/emmarex/plantdisease/data
Run GUI code in Jupyter Notebook and Model code in Google Colab.
