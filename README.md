# German Traffic Sign Recognition with Deep Learning

Classifying **43 categories** of German traffic signs using two deep-learning approaches:
a **Custom CNN** built from scratch and **ResNet-50** with transfer learning.

**Course:** Deep Learning  
**Authors:** Abdulrahman Aqili · Ali Al-Qarni

---

## 📊 Results

| Model       | Top-1 Accuracy | Top-5 Accuracy | Parameters |
|-------------|---------------:|---------------:|-----------:|
| Custom CNN  | **97.82 %**    | 99.74 %        | 0.46 M     |
| ResNet-50   | **99.18 %**    | 99.96 %        | 23.6 M     |

> ResNet-50 surpasses the human benchmark of 98.84 % (Stallkamp et al., 2012).

![Benchmark](results/benchmark.png)

---

## 🗂️ Dataset

[GTSRB – German Traffic Sign Recognition Benchmark](https://benchmark.ini.rub.de/gtsrb_news.html)
- 43 classes, ~39k train / ~12k test images
- Downloaded automatically by `torchvision.datasets.GTSRB`

See [`data/README.md`](data/README.md) for setup details.

---

## 🚀 Quick Start

```bash
# 1. Clone
git clone https://github.com/<your-username>/GTSRB-Traffic-Sign-Recognition.git
cd GTSRB-Traffic-Sign-Recognition

# 2. Install dependencies
pip install -r requirements.txt

# 3. Open the notebook
jupyter notebook notebooks/GTSRB_DeepLearning_1.ipynb
```

---

## 🧠 Models

**Custom CNN** – three Conv-BN-ReLU blocks → Global Average Pooling → classifier.
**ResNet-50** – pre-trained on ImageNet, backbone frozen, only the final layer retrained.

---

## 📁 Project Structure
(insert the tree from section 1)

---

## 📜 License
MIT — see [LICENSE](LICENSE).
