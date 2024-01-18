
# Emotion Detection using Machine learning

### Overview
- This project focuses on developing an emotion detection model capable of recognizing seven distinct emotions: 
**anger, happy, sad, surprise, disgust, shock, and normal**. 
- The process involves dataset preprocessing, model initialization using TensorFlow and Keras, and subsequent training.
- The project aims to provide a comprehensive understanding of emotions through a machine learning model, with the training progress visualized using loss graphs.

### Dataset Preprocessing
- The initial step involves preprocessing datasets specific to each emotion. 
- This includes cleaning, normalization, and feature extraction to ensure a consistent and meaningful representation of emotional cues in the data.

### Model Initialization and Training
- The TensorFlow and Keras frameworks are employed to construct a neural network tailored for emotion detection. 
- The model architecture is designed to accommodate the nuances of different emotions. 
- Training involves feeding the preprocessed datasets into the model and iteratively optimizing its parameters to achieve accurate emotion classification.

### Training Progress Visualization
- Training and validation loss graphs are generated to visually assess the model's performance. 
- These graphs offer insights into the convergence and generalization of the model, aiding in fine-tuning and optimization.

## Libraries used : 
- Tensorflow.
- Keras.
- Joblib.
- Preprocessing.
- numpy.
- CV2.
- Image.
- Pytorch.

# Flow of Execution : 
### Preprocessing Images:
- Preprocessing individual emotion images for enhanced model performance, including normalization, resizing, and feature extraction.

### Dataset Splitting:
- Splitting the dataset into training and validation sets to facilitate model training and evaluation.

### Model Initialization:
- Initializing a sequential model using TensorFlow and Keras to effectively capture the intricacies of emotion detection.

### Model Training with 139 Epochs:
- Train the model for 139 epochs to strike a balance between achieving convergence and preventing overfitting. This choice is based on iterative experimentation and observing the trade-off between training time and model accuracy.

### Accuracy: 
- Achieved an accuracy of 86% during model evaluation, demonstrating the model's proficiency in accurately classifying emotions.

### Graphs Printing:
- Displayed visual representations of the model's accuracy and loss during the validation process, providing insights into its performance and convergence.

### Model Dumping:
- Saved the trained model in a joblib file for future use or to improve performance of my emotion classifier model, ensuring ease of deployment and integration into applications requiring emotion detection capabilities.
