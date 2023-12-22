# Facial-Expression-Recognition using CNN 

**Dataset:**

[FER2013 dataset](https://www.kaggle.com/datasets/msambare/fer2013), comprises 48x48 pixel grayscale images of faces, automatically aligned to center the facial expressions consistently across 28,709 training and 3,589 public test examples. Each image is classified into one of seven emotion categories (0=Angry to 6=Neutral). 


**Problem Statement:**

Interpreting facial expressions is critical in various innovative contexts, such as monitoring driver alertness to prevent accidents, enhancing customer service with emotion-responsive interfaces, and improving social robotics for better human-machine interactions. However, manual interpretation is not scalable and lacks real-time responsiveness. An automated, accurate, and fast recognition system is needed to address these diverse applications.


**Goal:**

To create an advanced facial emotion recognition model capable of real-time interpretation from images. The model will leverage Convolutional Neural Networks to classify emotions in various real-life scenarios, such as detecting drowsiness in drivers or gauging customer satisfaction, enhancing safety and service quality through immediate and accurate emotional understanding.


**Methods and Models used:**

**Convolutional Neural Network (CNN):** To capture spatial hierarchies and characteristics of facial expressions in image data.
**Optimizers:** Experimentation with Adam, SGD, RMSprop, and Adamax to determine the most effective algorithm for training our CNN model.
**Data Augmentation:** To enhance the model's ability to generalize from the training data by introducing variations such as rotations and flips.
**Class Imbalance Handling:** Employing techniques like class weighting or oversampling to ensure a balanced representation of emotions.


**Results:**

The optimized CNN model, particularly when using the Adamax optimizer, demonstrated impressive accuracy and generalization capabilities, making it a promising solution for real-time emotion recognition.
