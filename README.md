# 🧠 CIFAR-10 Image Classification Using CNN

This project builds and trains a **Convolutional Neural Network (CNN)** to classify images from the **CIFAR-10 dataset** into 10 categories.

---

## 💡 Objective

Explore how CNN architecture, activation functions, and regularization affect performance in multi-class image classification.

---

## 📊 Techniques Used

- **Data Preprocessing**:
  - Normalize pixel values (0–255 → 0–1)
  - One-hot encode labels

- **Model Building**:
  - Convolutional layers (Conv2D)
  - MaxPooling
  - Dense layers
  - Softmax output

- **Regularization**:
  - Dropout (optional)
  - EarlyStopping callback

- **Evaluation & Visualization**:
  - Accuracy and loss curves
  - Prediction examples

---

## 🧠 Tools & Libraries

- Python  
- `TensorFlow`, `Keras`  
- `NumPy`, `Matplotlib`  

---

## 📁 Dataset: CIFAR-10

- 60,000 color images (32x32 pixels, RGB)
- 10 classes:
  - airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck
- Training: 50,000 images  
- Test: 10,000 images  
- Loaded via: `keras.datasets.cifar10`

---

## ⚙️ Training Details

- **Optimizer**: `Adam`  
- **Loss Function**: `CategoricalCrossentropy`  
- **Batch Size**: `126`  
- **Epochs**: `25`  
- **Callback**: `EarlyStopping` (patience = 3, monitor = `val_accuracy`)

---

## 📈 Project Workflow

1. **Load & Preprocess Data**
2. **Build CNN Model**
3. **Train the Model with Validation**
4. **Evaluate Accuracy and Loss**
5. **Visualize Results**

---

## 🔍 Example Output

- Training vs. Validation Accuracy  
- Training vs. Validation Loss  
- Model performance on test set  
- Sample predictions with true vs. predicted labels

---


## 👩‍💻 Author

**Mariam Badr**  
Faculty of Computers & Artificial Intelligence, Cairo University  
[GitHub](https://github.com/Mariam-Badr-MB) – [LinkedIn](https://www.linkedin.com/in/mariambadr13/)

---

## 📜 License

This project is for **educational and learning purposes only**.
