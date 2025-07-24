# Generative AI for Sign Language Translation – Supplementary Code

This repository contains the complete supplementary material for the book **“Generative AI for Sign Language Translation”**, including chapter-wise implementations, code explanations, and result visualizations. The content spans preprocessing, embedding techniques, generative modeling, video synthesis, and evaluation pipelines for Sign Language Translation (SLT).

## 📘 Overview

Each chapter provides runnable Jupyter Notebooks, organized by section and aligned with the corresponding book content. The repository includes:

- Sentence-to-gloss and speech-to-gloss translation pipelines  
- Preprocessing and augmentation for sign language datasets  
- Transformer, diffusion, and multimodal generation techniques  
- Pose keypoint extraction and visualization using MediaPipe  
- Quantitative evaluation using BLEU, ROUGE, SSIM, PSNR, WER  
- Skeleton-based motion modeling and synthetic video synthesis  

## 🗂 Repository Structure

```
├── Chapter 3/   # Sign Language Datasets and Preprocessing
├── Chapter 4/   # Generative AI Techniques for SLT
├── Chapter 5/   # Speech-to-Sign Language Translation
├── Chapter 6/   # Generative Architectures and Evaluation
├── Chapter 7/   # Vision-Based Recognition and Temporal Modeling
├── Chapter 8/   # Sign Language Generation and Video Synthesis
```

## 📌 Chapter-wise Notebooks

### 📁 Chapter 3: Sign Language Datasets  
- Dataset cleaning, gloss analysis, signer variation  
- Video augmentation using OpenCV  
- MediaPipe keypoint extraction and visualization  
- Signer style analysis  
- Gloss quality control and flagging

### 📁 Chapter 4: Generative AI Techniques for SLT  
- Text preprocessing and gloss formatting  
- Embedding generation and similarity heatmaps  
- Synonym-based augmentation and back-translation  
- PCA/t-SNE visualization of semantic space  
- Zero-shot gloss generation with Flan-T5

### 📁 Chapter 5: Speech-to-Sign Language Translation  
- Speech-to-text using Whisper  
- Few-shot and fine-tuned gloss generation using T5  
- Evaluation with BLEU, ROUGE, WER metrics

### 📁 Chapter 6: Generative Architectures and Evaluation  
- Transformer model comparison (BART, mBART)  
- Diffusion-based denoising of pose sequences  
- Multimodal captioning with BLIP-2  
- Radar and heatmap comparison of SLT model features

### 📁 Chapter 7: Vision-Based Recognition and Pose Modeling  
- 2D/3D skeletal visualization  
- GCN, TCN, Transformer-based pose encoders  
- Sequential modeling with LSTM, Transformer  
- Temporal jitter simulation and denoising recovery

### 📁 Chapter 8: Sign Language Generation and Video Synthesis  
- Video synthesis from gloss and pose frames  
- Keypoint-to-video rendering  
- Visual similarity and temporal smoothness evaluation

## ✅ Requirements

Most notebooks are designed to run in **Google Colab** and will automatically install dependencies as needed.

Common packages:
- `transformers`, `datasets`, `sentence-transformers`
- `opencv-python`, `matplotlib`, `seaborn`
- `torchaudio`, `librosa`, `mediapipe`, `pydub`
- `evaluate`, `jiwer`, `scikit-learn`

## 🚀 How to Use

1. Clone this repository or open the notebooks in Colab.
2. Mount your Google Drive and point to the sample files (as shown in each notebook).
3. Follow section headers in the notebooks to execute and interpret results.
4. Match each notebook section with the corresponding book chapter for explanation.

## 📚 Citation

If you use this repository or refer to the implementation in your research, please cite the book:

> Elakkiya R., *Generative AI for Sign Language Translation*, IET Press, 2025.

## ℹ️ License & Disclaimer

This repository is part of the official supplementary material for the book published by **IET Press**. All code and content are provided for academic and non-commercial use only.

**Copyright © 2025 Elakkiya R.**  
Distribution or commercial reuse outside the scope of the book agreement with IET is not permitted without explicit permission.

---

📍 **Main Repository**: [https://github.com/Elakkiya16/IETGenAI-SLT](https://github.com/Elakkiya16/IETGenAI-SLT)
