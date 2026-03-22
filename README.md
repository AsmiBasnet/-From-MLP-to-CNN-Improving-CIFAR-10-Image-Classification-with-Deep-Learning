# 🧠 From MLP to CNN: Improving CIFAR-10 Classification

## 🚀 Overview

This project explores the limitations of **fully connected networks (MLPs)** on image data and demonstrates how **Convolutional Neural Networks (CNNs)** significantly improve performance.

The focus is not just building models — but **systematically improving them through experimentation**.

---

## 🎯 Objective

* Evaluate MLP performance on image classification
* Identify limitations
* Improve results using:

  * Regularization
  * Data augmentation
  * CNN architectures

---

## 📊 Dataset

* CIFAR-10 (60,000 images, 10 classes)
* Image size: 32×32 RGB

---

## 🧪 Experiments

### 🔹 1. Baseline MLP

* Architecture: 512 → 256 → 128
* Result:

  * Train Acc: **71%**
  * Val Acc: **53%**

📉 Overfitting observed

---

### 🔹 2. Regularization (Dropout + BatchNorm)

* Improved generalization

✅ Val Accuracy: **55%**

---

### 🔹 3. Data Augmentation

* Random crop, flip, rotation

📊 Result:

* Slight generalization improvement
* Limited impact due to lack of spatial learning

---

### 🔹 4. CNN Model (Key Improvement 🚀)

* Convolutional layers extract spatial features

🔥 Result:

* Val Accuracy: **~70–75%**

---

## 📈 Model Comparison

| Model                | Val Accuracy |
| -------------------- | ------------ |
| MLP (Baseline)       | 53%          |
| MLP + Regularization | 55%          |
| MLP + Augmentation   | 49%          |
| CNN                  | **~72%**     |

---

## 📊 Results Visualization

*Add your plots here:*

![Accuracy](results/plots/accuracy.png)

---

## 💡 Key Insights

* MLPs fail to capture spatial structure in images
* CNNs significantly outperform due to feature extraction
* Regularization helps, but architecture matters more
* Data augmentation is more effective with CNNs

---

## 🛠️ Tech Stack

* Python, PyTorch
* NumPy, Matplotlib

---

## ▶️ How to Run

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO

pip install -r requirements.txt
python train.py
```

---

## 🔮 Future Work

* ResNet / Transfer Learning
* Hyperparameter tuning
* Early stopping

---

## 👨‍💻 Author

**Asmi Basnet**
📧 [asmibas18@gmail.com](mailto:asmibas18@gmail.com)
🔗 linkedin.com/in/asmibasnet/

---

## ⭐ Impact

This project demonstrates:

* Strong ML fundamentals
* Experimentation mindset
* Ability to improve models based on evidence

➡️ Transition from **“training models” → “thinking like a data scientist”**
