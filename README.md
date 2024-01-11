Description: This report aims to detail the efforts and outcomes of the project titled "Data Engineering for Deepfake Detection." The project's primary objective was to train, validate, and test a deep learning model on real and fake images of political figures, namely Biden, Putin, and Modi. The trained model was intended to be capable of predicting whether general images are real or fake, providing a valuable tool for detecting deepfake content.
 
The dataset used for the project was divided into three categories - Biden, Putin, and Modi - each with separate sets for training, validation, and testing. The Biden dataset consisted of 398 images in the training set, 147 images in the validation set, and 65 images in the test set. Similarly, the Putin dataset had 202 images for training, 74 for validation, and 15 for testing, while the Modi dataset comprised 100 training images, 58 validation images, and 38 test images.
 
 
Results: The model achieved seemingly impressive results, reporting 100% test accuracy for all three political figures: Biden, Putin, and Modi. However, this high level of accuracy may indicate overfitting, where the model has learned the training data too well and struggles to generalize to new, unseen data.
 
 
Conclusion: The observed 100% test accuracy raises concerns about the model's generalization capabilities, suggesting overtraining on the provided datasets. Potential solutions to this issue include adding more diverse data to the training set or implementing random shuffling of images across the training, validation, and test folders as Dr. Chakrabarty recommended me to do earlier. The latter approach aims to ensure that the model encounters a broader range of scenarios during training, fostering better generalization
