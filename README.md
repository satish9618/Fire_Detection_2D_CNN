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

---

## 🧠 2D CNN Architecture (Mind Map)

```mermaid
mindmap
  root((Input Image 128x128x3))
    Convolution
      "Conv2D (32 filters, 3×3)"
      "ReLU Activation"
    Pooling
      "MaxPooling (2×2)"
    Convolution
      "Conv2D (64 filters, 3×3)"
      "ReLU Activation"
    Pooling
      "MaxPooling (2×2)"
    Dense Layers
      Flatten
      "Dense (128 neurons, ReLU)"
      "Dropout (0.5)"
      "Dense (2 neurons, Softmax)"
---

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

