# Archaeology Image Retrieval using Deep Learning

A deep learning-based Content-Based Image Retrieval (CBIR) system developed for archaeology and historical monument datasets. The project retrieves visually similar images using feature extraction and cosine similarity techniques.

## Project Overview

This project uses deep learning models such as VGG16, MobileNet, and ResNet to extract image features from historical monuments and temple datasets. The extracted feature vectors are then compared using cosine similarity to retrieve the most visually similar images.

The project was later customized using Indian archaeology datasets including temples and monuments.

---

## Features

- Content-Based Image Retrieval (CBIR)
- Deep feature extraction using:
  - VGG16
  - MobileNet
  - ResNet
- Cosine similarity-based image matching
- Historical monument and archaeology dataset support
- Retrieval of top similar images
- GUI-based implementation using Tkinter
- Model performance comparison

---

## Tech Stack

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Pandas
- Scikit-Learn
- Tkinter
- Matplotlib
- Seaborn

---

## Dataset

The project was trained using:
- COREL1000 Dataset
- Archaeology/Temple Image Dataset

The archaeology dataset contains images of Indian temples and historical monuments. :contentReference[oaicite:1]{index=1}

---

## Model Performance

| Model | Accuracy |
|-------|----------|
| VGG16 | 90.90% |
| MobileNet | 86.49% |
| ResNet | 0.51% |

Performance results generated during testing are available in the project output files. :contentReference[oaicite:2]{index=2}

---

## Workflow

1. Upload image dataset  
2. Preprocess and normalize images  
3. Train deep learning models  
4. Extract image feature vectors  
5. Apply cosine similarity  
6. Retrieve top matching images

---

## Installation

Clone the repository:

```bash
git clone https://github.com/saimadhavmk/archaeology-image-retrieval.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the project:

```bash
python CBIR.py
```

---

## Future Improvements

- Real-time image search
- Web deployment
- Larger archaeology datasets
- Faster retrieval optimization

---

## Author

**Sai Madhav Mokirala**
