# 👕 StyleSense — Fashion Recommendation System

StyleSense is a deep learning-based fashion recommendation system that recommends visually similar fashion items based on an uploaded image.

The system uses a pretrained **ResNet50** model to extract meaningful visual features from fashion images and **Cosine Similarity** to identify the most similar items from the dataset.

---

## 🔗 Links

- **GitHub Repository:** [fashion-rec-ai](https://github.com/kumarsunny-nitian/fashion-rec-ai)
- **Live Demo:** [Hugging Face Spaces](https://huggingface.co/spaces/rishusah/fashion-recommender)

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
