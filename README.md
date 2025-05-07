
## 📌 Project Overview

This project presents a deep learning-based system for the automated detection of tea leaf diseases in Bangladesh. Leveraging the power of **ResNet-50** and various machine learning classifiers, the model classifies tea leaves into healthy or one of **seven common disease categories**, aiming to modernize crop disease identification and reduce reliance on error-prone manual inspection.

## 🧠 Key Features

* **Transfer Learning with ResNet-50:** Used for robust feature extraction and classification.
* **Traditional ML Classifiers:** Includes Logistic Regression, SVM, Random Forest, etc., for model comparison.
* **Image Preprocessing:** Includes resizing, data augmentation, and balancing for effective training.
* **Dimensionality Reduction:** PCA and t-SNE for feature visualization and cluster analysis.
* **Performance Evaluation:** Accuracy, F1-score, ROC-AUC, and confusion matrices used for evaluation.
* **Data Visualization:** Training curves, feature maps, and projection plots for interpretability.

## 🗂 Dataset

* Source: [Kaggle - Tea Sickness Dataset](https://www.kaggle.com/datasets/shashwatwork/identifying-disease-in-tea-leafs/code)
* Classes:

  * Red Leaf Spot
  * Algal Leaf Spot
  * Bird’s Eyespot
  * Gray Blight
  * White Spot
  * Anthracnose
  * Brown Blight
  * Healthy Leaves

## 🛠️ Technologies Used

* **Python**, **TensorFlow**, **Keras**
* **ResNet-50** for deep feature extraction
* **scikit-learn** for traditional classifiers
* **Matplotlib**, **Seaborn** for data visualization
* **PCA**, **t-SNE** for dimensionality reduction

## 📈 Results

* **Best Model:** Fine-tuned ResNet-50
* **Accuracy:** \~81% on validation set
* **AUC:** > 0.90 for all classes
* **Strengths:** High precision, robust classification, generalization to unseen data
* **Limitations:** Some confusion between visually similar diseases (e.g., red leaf spot and gray blight)

## 🔮 Future Work

* Increase dataset diversity for real-world conditions
* Explore Vision Transformers and ensemble models
* Develop mobile/real-time deployment for in-field use by farmers

## 📄 License

This project is for academic purposes under the supervision of Prof. Dr. Md. Ashraf Ali, Machine Learning Course, American International University-Bangladesh.

