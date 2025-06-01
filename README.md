
# 🌿 Plant Disease Identification

A deep learning-based project for identifying plant diseases from leaf images using the Swin Transformer architecture. This project aims to assist farmers and agriculturists in early and accurate disease detection to prevent crop loss.

## 🚀 Features

- 📸 Image classification for plant disease detection
- 🧠 Transformer-based deep learning (Swin Transformer)
- 📊 High model accuracy (up to 98%)
- 🧪 Jupyter Notebook for easy experimentation and reproducibility

## 🧰 Tech Stack

- Python
- PyTorch / Torchvision
- Swin Transformer (timm)
- Jupyter Notebook
- CUDA (for GPU acceleration)

## 🗂 Project Structure

```
plant-disease-identification/
├── Plant_Disease_Identification.ipynb
├── dataset/ (not included in repo)
├── models/
│   └── swin_transformer.pth
├── requirements.txt
└── README.md
```

## ⚙️ Installation

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/plant-disease-identification.git
   cd plant-disease-identification
   ```

2. Create and activate a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # or venv\Scripts\activate on Windows
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 🧪 Usage

Run the notebook:

```bash
jupyter notebook Plant_Disease_Identification.ipynb
```

Make sure to have the dataset in place and update the paths in the notebook accordingly.

## 📈 Results

- Accuracy: ~98%
- Model: Swin Transformer
- Training Time: ~X hours on NVIDIA GPU (fill in if known)

## 📂 Dataset

You can use publicly available datasets like:

- [PlantVillage Dataset](https://www.kaggle.com/datasets/emmarex/plantdisease)

> Make sure to follow the dataset's license and terms of use.

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first.

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
