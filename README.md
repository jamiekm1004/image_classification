# Image Classification with Convolutional Neural Networks

A machine learning project utilizing **Convolutional Neural Networks (CNNs)** to classify images from the **CIFAR-10 dataset**, which contains 60,000 32x32 color images across 10 categories, such as airplanes, automobiles, and birds.

---

## Features

- **Data Exploration:**
  - Visualized sample images from the CIFAR-10 dataset to understand class distribution and image quality.
  - Preprocessed the dataset for training, validation, and testing.

- **Model Architecture:**
  - Designed a CNN with:
    - Multiple convolutional layers for feature extraction.
    - Max-pooling layers to reduce dimensionality and retain critical features.
    - Dense layers for classification across 10 categories.

- **Model Training:**
  - Compiled the model using the Adam optimizer and sparse categorical cross-entropy loss function.
  - Trained the model over 10 epochs, achieving a test accuracy of 70.7%.

- **Visualization:**
  - Plotted training and validation accuracy and loss to monitor model performance.
  - Visualized predictions with confidence scores to analyze misclassifications.

---

## Key Insights

- **Performance:**
  - Achieved a test accuracy of 70.7%, indicating effective learning for a baseline CNN.
  - Identified classes where the model struggled, suggesting potential improvements with more advanced architectures.

- **Learning Process:**
  - Observed overfitting in later epochs, highlighting the need for regularization techniques like dropout.

- **Future Improvements:**
  - Experimenting with deeper architectures, data augmentation, and transfer learning could further boost accuracy.

---

## Technologies Used

- **Programming Language:** Python
- **Libraries:** TensorFlow, Keras, NumPy, Matplotlib
- **Tools:** Jupyter Notebook

---

## Contact

For any inquiries or feedback, feel free to reach out:

- **Portfolio:** [Portfolio Link](https://jamiekm1004.github.io/)
- **LinkedIn:** [Jamie Kim](https://linkedin.com/in/jamie-kim-stats)
- **GitHub:** [GitHub Profile](https://github.com/jamiekm1004)
