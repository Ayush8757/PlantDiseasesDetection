# 🌱 Plant Disease Classification using Deep Learning

## 🚀 Project Overview
This project focuses on **plant disease classification** using deep learning models trained on the **PlantVillage dataset**. The models used include **EfficientNetV2B3, ResNet50V2, and Xception**, achieving high accuracy through **transfer learning and fine-tuning**.

## 📌 Key Highlights
- **Dataset**: 📂 Used **PlantVillage dataset** from TensorFlow Datasets (**TFDS**)
- **Models**: 🤖 Trained **EfficientNetV2B3, ResNet50V2, and Xception**
- **Accuracy**: 📈 Achieved **99.83% (EfficientNetV2B3), 99.71% (ResNet50V2), and 99.77% (Xception)**
- **Preprocessing**: 🖼️ Applied **image preprocessing & data augmentation**
- **Training Optimizations**:
  - ✅ **Mixed precision training** for faster computations ⚡
  - ✅ **80-20 train-test split** for better generalization
  - ✅ **Dropout (30%)** to prevent overfitting
  - ✅ **Learning rate reduction** & **early stopping** for optimized training
  - ✅ **Model checkpoints** to save best-performing models
- **Fine-Tuning**: 🔍 Unfroze **last 10 layers** for better feature extraction
- **Model Architecture**: 🏗️ Used **Keras Functional API** instead of Sequential API

## 🛠️ Setup & Installation
```bash
# Clone the repository
git clone https://github.com/Ayush8757/PlantDiseasesDetection.git
```

## 🎯 Results
| Model             | Accuracy  |
|------------------|-----------|
| EfficientNetV2B3 | **99.83%** |
| ResNet50V2       | **99.71%** |
| Xception         | **99.77%** |

## 📌 Future Enhancements
- 🏆 Improve **real-time inference performance**
- 🎯 Deploy model using **Streamlit Web App**
- ⚡ Experiment with **pruning & quantization** for mobile deployment

## 💡 Contributing
Feel free to **fork** this repository, submit issues, or contribute improvements! 🚀

## 📩 Contact
For any queries, reach out to **Ayush Kacholiya** at **ayushrkacholia@gmail.com**

---
🌟 **If you found this project useful, don't forget to ⭐ the repository!**

