# 🔥 Fire Detection Using 2D CNN  

A **Convolutional Neural Network (CNN)** built with **TensorFlow/Keras** to classify images as **fire** or **non-fire**.  
This project shows how deep learning can be applied for **early fire detection** in applications like **forest fire monitoring, surveillance systems, and safety alerts**.  

---

## 📌 Features  
✅ Upload an image and classify it as **fire** or **non-fire**  
✅ Preprocessing pipeline: resize → normalize → batch  
✅ Displays image with **prediction label + bounding box**  
✅ Built with a **custom 2D CNN architecture**  
✅ Easy to run in **Google Colab** or locally  

---

## 🧠 2D CNN Architecture  

The CNN is designed to learn spatial patterns (flames, smoke textures, fire shapes) from images.  

**Architecture Flow:**  

Input (128x128x3 RGB Image)
↓
Conv2D (32 filters, 3×3) + ReLU
↓
MaxPooling (2×2)
↓
Conv2D (64 filters, 3×3) + ReLU
↓
MaxPooling (2×2)
↓
Flatten
↓
Dense (128 neurons, ReLU)
↓
Dropout (0.5)
↓
Dense (2 neurons, Softmax)


🔹 **Activation**: ReLU (hidden layers), Softmax (output layer)  
🔹 **Loss Function**: Categorical Crossentropy  
🔹 **Optimizer**: Adam  

---

## 📊 Workflow  

1. **Input** → Upload an image (fire or non-fire)  
2. **Preprocessing** → Resize (128×128), normalize, and batch  
3. **Prediction** → Model outputs class probabilities  
4. **Output** → Displays image with bounding box + label (`fire` / `non_fire`)  

---


## 🛠️ Tech Stack  

- **Python 3**  
- **TensorFlow / Keras**  
- **NumPy**  
- **Matplotlib**  
- **Google Colab / Jupyter Notebook**  

