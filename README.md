## 🌾 Rice Leaf Disease Detection – Hybrid Deep Learning Model

A high-accuracy deep learning system built to identify and classify rice leaf diseases using computer vision. This project combines a pretrained ResNet-50v2 model with a custom-connected neural network, trained on a large image dataset to support timely and precise agricultural diagnostics. It enables farmers and agronomists to detect crop diseases early, reducing crop loss and improving yield.

---

## 🌟 Features

- 🔍 Identifies multiple rice leaf diseases from images
- 🤝 Hybrid architecture combining ResNet-50v2 + custom classifier
- 🧠 Applied techniques like Batch Normalization, Dropout, and L2 regularization
- 📈 Achieved 99.53% accuracy on a dataset of 15,023 rice leaf images
- 📊 Real-time prediction with user-uploaded leaf images

---

## 🧪 Model Architecture

- **Base Model**: ResNet-50v2 (pretrained on ImageNet)
- **Custom Layers**: Fully connected layers with ReLU, Dropout, and L2 regularization
- **Training**: Data augmentation (zoom, rotation, flipping), Adam optimizer, early stopping
- **Evaluation**: Accuracy, loss curves, confusion matrix, precision & recall

---

## 📸Accuracy

<p align="center">
  <img src="assets/prediction_sample.png" width="600"/>
</p>

---

## 🌍 Impact

- ✅ Supports farmers in early detection of rice diseases
- 🌱 Reduces crop loss through AI-based disease recognition
- 🤖 Promotes smart agriculture and precision farming in rural areas

---

## 💡 Use Cases

- 📷 Mobile app for farmers to click & diagnose rice leaves
- 🛰️ Integrate into drone surveillance systems for field scanning
- 🧪 Agricultural research & crop disease tracking
- 🌾 Government or NGO-led rural AI adoption programs

---

## 🛑 Disclaimer

This model is trained on publicly available data and is intended for educational and prototyping purposes only. Not for clinical or commercial use without further validation.


