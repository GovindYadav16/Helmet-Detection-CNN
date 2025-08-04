# Helmet Detection using CNN 🧠🪖

This project builds and evaluates a **Convolutional Neural Network (CNN)** for binary image classification to detect **helmet usage** from MRI-style image data.

---

## 🚀 Business Context

Rider safety is a major concern in transportation. Helmet usage significantly reduces the risk of head injury. This project simulates a visual detection system for helmet presence using image classification — a concept applicable in real-world surveillance and smart traffic systems.

---

## 🎯 Objective

To build an image classification model using CNN that can:
- Identify whether a person is wearing a helmet (label = 1)
- Detect absence of helmet (label = 0)

The pipeline includes:
- Image analysis and preprocessing
- Model building using CNN
- Training & evaluation
- Visualization of predictions

---

## 🧠 Dataset Description

- Binary classification dataset with two classes:
  - `yes/` → images with helmets
  - `no/` → images without helmets
- Images are RGB or grayscale
- Dataset was analyzed for:
  - Corrupt files
  - Channel consistency
  - Shape uniformity
  - Class balance

---

## 📊 Class Distribution

Balanced dataset with nearly equal number of samples in both classes:
- Helmet: 316
- No Helmet: 314

---

## 📈 Model Performance

| Metric         | Value |
|----------------|-------|
| Accuracy       | 99%+  |
| Loss           | Very low |
| Model Used     | CNN with Conv2D, MaxPooling, Flatten, Dense layers |

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- OpenCV
- NumPy / Pandas / Matplotlib / Seaborn

---

## 📁 Folder Structure

```
📦Helmet-Detection-Assignment/
 ┣ 📜Helmet_Detection_CNN_Govind.ipynb
 ┣ 📂data/
 ┃ ┣ 📂yes/
 ┃ ┗ 📂no/
 ┣ 📜README.md
 ┣ 📜requirements.txt
 ┗ 📜.gitignore
```

---

## 📝 How to Run

1. Clone the repository:
   ```bash
   https://github.com/GovindYadav16/Helmet-Detection-CNN.git
   cd Helmet-Detection-CNN
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   - Open `Assignment_HelmNet_Code_Govind.ipynb` in Jupyter or Colab
   - Execute all cells

---

## 📌 Future Improvements

- Convert to real-time video detection using OpenCV
- Deploy the model via Streamlit or Flask
- Add data augmentation to improve robustness

---

## 👤 Author

**Govind Yadav**  
AI/ML Engineer | Deep Learning, NLP, Generative AI | Python, PyTorch, TensorFlow
📧 [Email](mailto:yadavgovind16@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/govind-yadav-3ba6a8b9/)

---

## ⭐️ Give it a star if this helped you!
