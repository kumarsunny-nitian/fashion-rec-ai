# 👗 StyleMatch — Deep Learning-Powered Fashion Recommendation System

StyleSense is a deep learning-based fashion recommendation system that suggests visually similar fashion items based on an uploaded image.

The system uses a pretrained **ResNet50** model to extract meaningful visual features from fashion images and **Cosine Similarity** to identify the most similar items from the dataset.

---

## 🔗 Links

- **Live Demo:** https://huggingface.co/spaces/rishusah/fashion-recommender

---

## ✨ Features

- 📷 Upload a fashion image
- 🧠 Deep feature extraction using ResNet50
- 🔍 Content-based image recommendation
- 📊 Cosine similarity for comparing image embeddings
- 👕 Top-3 similar fashion recommendations
- ⚡ Real-time inference
- 🖥️ Interactive Gradio interface
- 📦 Lightweight fashion image dataset

---

## 🧠 How It Works

The recommendation pipeline works in the following steps:

```text
                 User Uploads Image
                         │
                         ▼
                Image Preprocessing
                    224 × 224
                         │
                         ▼
                  ResNet50 Model
                         │
                         ▼
                Feature Extraction
                         │
                         ▼
                Image Embedding
                         │
                         ▼
              Cosine Similarity
                         │
                         ▼
              Find Similar Images
                         │
                         ▼
          Top-3 Fashion Recommendations
```

---

## 🛠️ Tech Stack

- **Python**
- **PyTorch / TensorFlow** — ResNet50 model
- **Gradio** — Interactive web interface
- **NumPy / Scikit-learn** — Cosine similarity computation
- **PIL / OpenCV** — Image preprocessing

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/kumarsunny-nitian/fashion-rec-ai.git
cd fashion-rec-ai
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the app
```bash
python app.py
```

---

## 📌 Future Improvements

- Expand dataset for broader fashion category coverage
- Add filtering by category, color, or price
- Deploy with a scalable vector database (e.g., FAISS) for faster retrieval
- Add user feedback loop to improve recommendation relevance
