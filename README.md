# 🩺 Lung Cancer detection using ResNet50

## 📌 Overview

This project presents a **deep learning-based approach for lung cancer detection** using CT scan images. It leverages **transfer learning with ResNet50** to classify lung conditions into three categories:

* Malignant cases
* Benign cases
* Normal cases

The model is optimized using **data augmentation, focal loss, class balancing, and fine-tuning techniques** to improve accuracy and handle class imbalance effectively.

---

## 🚀 Features

* ✅ Transfer Learning using ResNet50 (pretrained on ImageNet)
* ✅ Custom **Focal Loss** for handling class imbalance
* ✅ Data augmentation for better generalization
* ✅ Oversampling of minority class
* ✅ Fine-tuning of deep layers
* ✅ Performance evaluation using:

  * Accuracy
  * Classification Report
  * Confusion Matrix

---

## 🧠 Technologies Used

* Python
* TensorFlow / Keras
* OpenCV
* NumPy, Pandas
* Matplotlib, Seaborn
* Scikit-learn

---

## 📂 Dataset

* Dataset used: **IQ-OTHNCCD Lung Cancer Dataset**
* Contains CT scan images categorized into:

  * Malignant
  * Benign
  * Normal

⚠️ Note: Due to size limitations, the dataset is not included in this repository.
👉 You can download it from: (https://www.kaggle.com/datasets/hamdallak/the-iqothnccd-lung-cancer-dataset)

---

##  Model Architecture

* Base Model: **ResNet50 (pretrained)**
* Global Average Pooling
* Dropout (0.4)
* Fully Connected Dense Layer (Softmax)

---

##  Workflow

1. Load and preprocess dataset
2. Train-test split
3. Oversample minority class
4. Convert grayscale to 3-channel images
5. Apply data augmentation
6. Train model (frozen base)
7. Fine-tune last layers of ResNet50
8. Evaluate model performance

---

##  Results

*  High classification accuracy on test data
*  Improved performance after fine-tuning
*  Reduced overfitting using augmentation and dropout

*(Add screenshots of confusion matrix & accuracy graphs here)*

---

## ▶️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/lung-cancer-detection-ml.git
   cd lung-cancer-detection-ml
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook or script:

   ```bash
   jupyter notebook
   ```

   OR

   ```bash
   python lung_cancer.py
   ```

---

## 📈 Sample Output

* Confusion Matrix
<img width="341" height="290" alt="confusion matrix" src="https://github.com/user-attachments/assets/fa06bbc7-cab8-433a-af54-afaef1b52e00" />
* Accuracy & Loss Graphs
 <img width="690" height="275" alt="accuracy graphs" src="https://github.com/user-attachments/assets/c49053e7-0ba5-4310-90a2-a0d5007cde77" />
* Model Performance Summary
 <img width="155" height="63" alt="Screenshot 2026-03-30 095732" src="https://github.com/user-attachments/assets/bc67421e-00af-48da-a4eb-341b9e007dbd" />

---

## 📌 Future Improvements

* 🔹 Deploy as a web application
* 🔹 Use larger and more diverse datasets
* 🔹 Implement real-time prediction
* 🔹 Try advanced architectures (EfficientNet, Vision Transformers)

---

## 👩‍💻 Author

Garika chandu sri
📧garikachandusri@gmail.com
🔗 LinkedIn: (https://www.linkedin.com/in/garika-chandu-sri-4a394425b/)

---

## 📜 License

This project is licensed under the **MIT License**.

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and support!
