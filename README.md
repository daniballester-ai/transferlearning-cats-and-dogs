# 🐾 Transfer Learning with TensorFlow: Cats vs. Dogs Classification

This project demonstrates the use of **transfer learning** 🧠 to classify images of 🐱 cats and 🐶 dogs using a pre-trained convolutional neural network (CNN). The process involves fine-tuning a base model trained on a large dataset (ImageNet) and adapting it to a new, smaller dataset.

At the end, we will test the trained model on a **Kaggle dataset** 🗂️ to evaluate its performance on unseen data.

## 🎯 Objectives
- 🚀 Utilize transfer learning to leverage the features learned by a pre-trained model.
- 🏋️ Train the model using TensorFlow's `cats_vs_dogs` dataset.
- 🔍 Test the trained model's performance on an external dataset from Kaggle.
- ✨ Apply data augmentation techniques to enhance generalization capabilities.

## 📝 Steps Overview
1. **🗂️ Data Preparation**: Load and preprocess the training dataset from TensorFlow and prepare the test dataset from Kaggle.
2. **🔧 Model Selection**: Use a pre-trained MobileNetV2 as the base model.
3. **🎨 Fine-Tuning**: Enable trainable layers in the base model to improve performance on the target dataset.
4. **📊 Evaluation**: Test the model on 10 images from each category in the Kaggle dataset and analyze its predictions.

## 🌟 Highlights
This project showcases the practical application of transfer learning in image classification tasks. By using **data augmentation** 🎭 and **fine-tuning** 🎯, the model achieves high accuracy on unseen data. The results provide insights into the model's strengths and areas for improvement.

---
Run the code 🖥️ to see the predictions and verify how well the model performs in classifying 🐱 cats and 🐶 dogs. Happy coding! 🚀
Codeby: daniballester-ai
