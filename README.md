# Transformer-Gated-Fusion-Network-for-Cancer-Classification

An advanced deep learning framework designed for highly accurate histopathology image classification to aid in automated cancer diagnosis. 

---

### 📌 Project Highlights
- **Architecture:** Hybrid Wavelet-CNN-Transformer network.
- **Performance:** Achieved an outstanding **97.95% accuracy** score.
- **Dataset:** Validated on over **5,000 biomedical and medical images**.
- **Core Innovation:** Implementation of gated fusion mechanisms to combine multiscale feature inputs dynamically.

---

### ⚙️ Methodology & Architecture

This project overcomes the limitations of standard architectures by integrating three distinct feature extraction components:
1. **Wavelet Transform:** Extracts localized frequency-domain features to preserve structural edge details.
2. **Convolutional Neural Networks (CNN):** Captures local spatial textures and patterns from the histopathology frames.
3. **Vision Transformers (ViT):** Learns global context and long-range dependencies across the entire tissue sample image.
4. **Gated Fusion Network:** A custom fusion mechanism that dynamically weighs and merges features from the Wavelet, CNN, and Transformer streams, minimizing redundancy and maximizing robustness.

---

### 🛠️ Tech Stack & Libraries
- **Deep Learning Frameworks:** PyTorch / TensorFlow
- **Image Processing:** OpenCV, PyWavelets, Scikit-Image
- **Data Analysis & Visualization:** NumPy, Pandas, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook / Python 3

---

### 📊 Key Results
- **Robust Feature Integration:** Gated fusion significantly outperformed traditional feature concatenation methods.
- **High Sensitivity:** Exceptional performance in minimizing false negatives, which is crucial for medical diagnostics.
- **Generalization:** Maintained high accuracy across a large, diverse dataset of 5,000+ medical images.

---

### 📂 Repository Structure
* `PROJECT REPORT.pdf` - Detailed academic documentation of project
* `RESEARCH PAPER.pdf` - Paper detailing the novel architecture.
* `wavelet_cnn_transformer_gated_...` - The source code file of the model.

