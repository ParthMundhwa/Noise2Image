# AI-Powered Notebooks

This repository includes two deep learning projects:

---

## 📘 Noise2Image - Biomedical Denoising

This project applies denoising diffusion models to medical imaging data (e.g., MRI and CT scans). The goal is to enhance image clarity for better diagnostics.

### Features
- Trained on datasets like BraTS or LIDC-IDRI
- Uses denoising diffusion probabilistic models (DDPM)
- Evaluated with PSNR and SSIM metrics

### Installation
```bash
pip install -r requirements.txt
```

### Usage
Run `Noise2Image.ipynb` cell-by-cell in a Jupyter environment or adapt the code for your image dataset.

---

## 🧠 Real-Time Code Comment Generator

A tool that generates intelligent code comments using a deep learning model. Helps developers improve documentation and code clarity.

### Features
- Uses a Transformer-based model (replaceable with custom models)
- Real-time generation from input code
- Trained on function-comment pairs

### Installation
```bash
pip install -r requirements.txt
```

### Usage
Open `CodeCommentGenerator.ipynb`, input your code snippet, and run the notebook to generate comments.

---

## 🔧 Requirements

Common packages:
- `torch`
- `transformers`
- `datasets`
- `matplotlib`
- `scikit-image` (for SSIM/PSNR)
- `kornia` (for vision ops)

Create a `requirements.txt` using:
```bash
pip freeze > requirements.txt
```

---

## 🙌 Contributions

Pull requests and issues are welcome!

---

## 📜 License

[MIT License](LICENSE)
