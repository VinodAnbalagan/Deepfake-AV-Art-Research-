# **Deepfake Detection, Autonomous Vehicle Perception, & AI-Generated Art Research**

## **📌 Project Overview**

This repository contains research and implementation on **Robustness & Explainability in AI-Generated & AI-Detected Content**, focusing on:

🔹 **Deepfake Detection & Prevention** – Detecting AI-generated fake videos using CNNs, Transformers & Adversarial Training.\
🔹 **Autonomous Vehicle Perception** – Using GANs to create synthetic AV training data for safer self-driving systems.\
🔹 **AI-Generated Art & Style Transfer** – Exploring explainability in neural networks for AI-generated creative content.

This work is inspired by the latest research from **Meta, DARPA, and AI Ethics communities**, aiming to build robust AI models against adversarial manipulation.

---

## **📑 Research Goals**

✔ **Develop more robust deepfake detection models resistant to adversarial attacks**.\
✔ **Use GANs to generate synthetic driving scenarios for AV model training**.\
✔ **Create an explainability framework for AI-generated art using CLIP & Grad-CAM**.\
✔ **Publish findings in AI/ML conferences (NeurIPS, ICML, CVPR, IEEE).**

---

## **📂 Repository Structure**

```
Deepfake-AV-Art-Research/
│── datasets/               # Dataset links, preprocessing scripts
│   ├── deepfake/           # Deepfake datasets (DFDC, Celeb-DF)
│   ├── av_perception/      # AV datasets (KITTI, BDD100K)
│   ├── ai_art/             # AI Art datasets (WikiArt, QuickDraw)
│
│── notebooks/              # Jupyter notebooks for experiments
│   ├── 1_data_analysis.ipynb  # Capstone 1: Data Exploration & Preprocessing
│   ├── 2_ml_models.ipynb      # Capstone 2: ML-based Detection
│   ├── 3_gan_training.ipynb   # Capstone 3: GANs & Explainability
│
│── models/                 # Trained model weights, logs
│   ├── deepfake_model.pth   # Saved model for deepfake detection
│   ├── av_gan_model.pth     # GAN model for AV data augmentation
│   ├── style_transfer.pth   # StyleGAN model for AI-generated art
│
│── src/                    # Python scripts for modular implementation
│   ├── deepfake_detection.py
│   ├── av_perception.py
│   ├── ai_art_generator.py
│
│── reports/                # Research findings, graphs, and logs
│   ├── figures/            # Plots and visualizations
│   ├── research_paper.md   # Markdown draft of the research paper
│
│── deployment/             # Web app (Flask/Streamlit) for testing models
│   ├── app.py
│   ├── requirements.txt
│
│── README.md               # Front page for the repository
│── LICENSE                 # Open-source license
│── .gitignore              # Ignore unnecessary files
```

---

## **📊 Datasets Used**

| **Domain**         | **Dataset**                                                                                                                                     | **Purpose**                                |
| ------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------ |
| Deepfake Detection | [DFDC](https://www.kaggle.com/c/deepfake-detection-challenge/data)                                                                              | Training deepfake detection models         |
| AV Perception      | KITTI, BDD100K                                                                                                                                  | Object detection & synthetic scene testing |
| AI Art             | WikiArt, QuickDraw                                                                                                                              | Generating & explaining AI-created art     |

---

## **🛠️ Technologies Used**

- **Programming:** Python, PyTorch, TensorFlow, OpenCV
- **Deep Learning Models:** CNNs (XceptionNet, EfficientNet), Vision Transformers, CycleGAN, StyleGAN
- **Adversarial AI:** GAN-based synthetic data generation & adversarial training
- **Deployment:** Flask, FastAPI, Streamlit
- **Explainability Tools:** CLIP, Grad-CAM, SHAP, LIME

---

## **📌 Research Roadmap**

- ✅ **Capstone 1:** Data Analysis & Preprocessing (Deepfake, AV, AI Art Datasets)
- ✅ **Capstone 2:** Train ML Models for Detection & Generation
- ✅ **Capstone 3:** Implement GAN-based Augmentation & Explainability
- 🚀 **Publish Research Findings & Deploy Models**

---

## **📝 Citation & Acknowledgments**

If you use this research, please cite:

```
Dolhansky, B., Bitton, J., Pflaum, B., Lu, J., Howes, R., Wang, M., & Canton Ferrer, C.  
"The DeepFake Detection Challenge Dataset." arXiv:2006.07397v4, 2020.  
```

**Acknowledgments:** Meta AI, Kaggle DFDC, KITTI, WikiArt, and the ML research community.

---

**⭐ Star this repository if you find it useful!** 🚀

