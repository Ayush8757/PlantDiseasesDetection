# 🌱 Plant Disease Classification using Deep Learning

## 🚀 Project Overview

This project focuses on **plant disease classification** using advanced deep learning models trained on the **PlantVillage** dataset. By leveraging **transfer learning** and **fine-tuning techniques**, the models achieve state-of-the-art performance, offering potential real-world applications in agriculture and plant health monitoring.

---

## 📌 Key Highlights

* **📂 Dataset**: PlantVillage dataset (via TensorFlow Datasets)
* **🤖 Models Trained**:

  * EfficientNetV2B3
  * ResNet50V2
  * Xception
  * ConvNeXt-Tiny 
  * DenseNet121 
  * MobileNetV3-Large 
* **📈 Accuracy Achieved**:

  * EfficientNetV2B3 – 99.83%
  * ResNet50V2 – 99.71%
  * Xception – 99.77%
  * ConvNeXt-Tiny – 99.98% 
  * DenseNet121 – 99.94% 
  * MobileNetV3-Large – 99.96% 
---

## 🧪 Model Evaluation

Beyond accuracy, the following evaluation metrics were also computed for deeper insights:

* **Precision**
* **Recall**
* **F1-Score**
* **Confusion Matrix**

These metrics help assess the robustness of the models and their performance across different plant disease classes.

---

## ⚙️ Preprocessing & Training Optimizations

* 🖼️ **Image Preprocessing** & **Data Augmentation**
* ⚡ **Mixed Precision Training** for speedup on supported hardware
* 🔀 **80-20 Train-Test Split** for better generalization
* 🛑 **Early Stopping** and **Learning Rate Scheduling**
* 💾 **Model Checkpoints** to preserve best-performing models
* 🔓 **Fine-Tuning**: Unfroze the last 10 layers of pretrained networks
* 🧱 **Model Architecture**: Implemented using **Keras Functional API**

---

## 🎯 Results Summary

| Model             | Accuracy |
| ----------------- | -------- |
| ConvNeXt-Tiny     | 99.98%   |
| MobileNetV3-Large | 99.96%   |
| DenseNet121       | 99.94%   |
| EfficientNetV2B3  | 99.83%   |
| Xception          | 99.77%   |
| ResNet50V2        | 99.71%   |

---

## 📌 Future Enhancements

* 🏃 Improve **real-time inference** performance
* 🌐 Deploy on web using **Streamlit**
* 📱 Optimize using **pruning** and **quantization** for mobile deployment
* 🛰️ Integrate with IoT-based crop monitoring systems

---

## 💡 Contributing

Contributions are welcome! Fork this repo, submit issues, or propose enhancements via pull requests.

---

## 📩 Contact

📧 Ayush Kacholiya – [ayushrkacholia@gmail.com](mailto:ayushrkacholia@gmail.com)
---

## 🌟 Show Your Support

If this project helped you or inspired your work, please give it a ⭐ on GitHub!

