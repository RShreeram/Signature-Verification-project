# ✍️ Signature Classification using Deep Learning (VGG16)

## 📌 Overview
This project implements a signature verification system using deep learning. It classifies signatures as genuine or forged using a pre-trained VGG16 model.

---

## 🚀 Key Features
- Uses transfer learning with VGG16
- Image preprocessing and normalization
- Binary classification (Genuine vs Forged)
- Implemented using PyTorch

---

## 🧠 Model Used
We used a pre-trained VGG16 model and fine-tuned it for signature classification. The model learns patterns such as strokes, curves, and structure of signatures.

---

## 📂 Project Structure
```
signature-detection/
│
├── src/
│   └── signature.py
├── requirements.txt
└── README.md
```

---

## ⚙️ How It Works
1. Input signature image
2. Preprocess image (resize, normalize)
3. Pass through VGG16 model
4. Output:
   - Genuine
   - Forged

---

## ▶️ How to Run

```
pip install -r requirements.txt
python src/signature.py
```

---

## 📌 Applications
- Banking authentication
- Document verification
- Fraud detection

---

## 🔮 Future Improvements
- Add web interface
- Improve dataset
- Use advanced architectures like ResNet

---

## 👨‍💻 Author
Shreeram
