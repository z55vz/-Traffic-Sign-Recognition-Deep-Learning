# 🚦 German Traffic Sign Recognition Benchmark (GTSRB)

A deep learning project evaluating two neural network approaches to classify **43 categories** of traffic signs, surpassing the human accuracy benchmark.

**Course:** Deep Learning  
**Authors:** Abdulrahman Aqili & Ali Al-Qarni

---

## 📊 Quick Results

| Model | Top-1 Accuracy | Top-5 Accuracy | Parameters | Status |
| :--- | :---: | :---: | :---: | :--- |
| **ResNet-50** (Transfer Learning) | **99.18%** | 99.96% | ~23.6 M | **Exceeds human benchmark** (98.84%) |
| **Custom CNN** (From Scratch) | **97.82%** | 99.74% | **~0.46 M** | **Lightweight alternative** (50x smaller) |

---

## 🗂️ Dataset Setup

Due to GitHub size limits, download the dataset directly from Kaggle:
👉 **[Download GTSRB Dataset on Kaggle](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign)**

### Project Tree
Extract the downloaded ZIP into a root folder named `data/` (ensure it is added to your `.gitignore`):

```text
GTSRB-Traffic-Sign-Recognition/
├── data/                  # ⚠️ Excluded from GitHub (Contains Meta, Train, Test)
├── notebooks/             # Contains GTSRB_Explanation_Professional.ipynb
├── results/               # Saved plots and benchmarks
├── .gitignore             
├── README.md              
└── requirements.txt
🚀 Quick Start
Bash
# 1. Clone & Navigate
git clone [https://github.com/](https://github.com/)<your-username>/GTSRB-Traffic-Sign-Recognition.git
cd GTSRB-Traffic-Sign-Recognition

# 2. Install Dependencies
pip install -r requirements.txt

# 3. Open Notebook
jupyter notebook notebooks/GTSRB_Explanation_Professional.ipynb
📜 License
MIT License — see LICENSE.
