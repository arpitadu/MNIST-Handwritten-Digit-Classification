# MNIST-Handwritten-Digit-Classification
The MNIST (Modified National Institute of Standards and Technology) dataset is a large database of handwritten digits. The dataset consists of 60,000 training and 10,000 test images, each of 28x28 grayscale pixels, representing digits from 0 to 9. 
The goal of this project is to build an automated model that can accurately classify these digits.

**Analysis**
Three deep networks were utilized in this study. Firstly, a simple CNN was built using TensorFlow's Keras API. Secondly, the initial CNN was made denser by adding an additional convolutional layer. Thirdly, a transfer learning approach was employed by applying the pre-trained VGG19, which had been previously trained on the ImageNet dataset.


**Findings**
The initial simple CNN model demonstrated the highest accuracy and was less complex and more computationally efficient compared to the denser model and the VGG-19 transfer learning approach. Therefore, the initial simple CNN was deemed the best model for this task, effectively distinguishing between different digits and generalizing well to unseen data.
| Regression Model              | Accuracy | 
|-------------------------------|----------|
|Simple CNN            | 0.990   | 
|Denser CNN             |0.989   | 
| VGG19    | 0.976   | 


This repository demonstrates that a simple CNN can achieve high accuracy and efficiency in classifying handwritten digits, outperforming more complex and transfer learning models in this specific task. The simple CNN model is effective for distinguishing between different digits and generalizing well to new data.
