# Knee Osteoarthritis Severity Prediction & XAI Visualization

This repository contains a lightweight, research-ready pipeline for **automatic Knee Osteoarthritis (OA) severity prediction** using deep learning and explainable AI (XAI). The workflow includes image upload, KL grade prediction, Grad-CAM, Integrated Gradients, SmoothGrad visualizations, and consensus ROI analysis.

---

## Features

- **Fast Training:** Uses MobileNetV2 for quick training on small datasets.
- **Prediction:** Upload any knee X-ray image and get KL grade prediction.
- **XAI Visualization:** Grad-CAM, Integrated Gradients, SmoothGrad, and consensus map highlighting cartilage/joint-line regions.
- **ROI Metrics:** Quantitative evaluation of heatmap intensity in regions of interest.
- **Overlay with ROI Boxes & Contours:** Highlights OA-affected areas visually for research or clinical interpretation.

I developed a lightweight AI pipeline for Knee Osteoarthritis (OA) severity prediction using MobileNetV2, capable of fast training on small datasets. The model predicts KL grades from X-ray images and is optimized for Colab and low-RAM environments. The pipeline integrates state-of-the-art XAI techniques—Grad-CAM, Integrated Gradients, and SmoothGrad—to generate interpretable heatmaps, highlighting cartilage and joint-line regions. A consensus map and ROI overlays with boxes and contours provide research-ready visualization, enabling both qualitative and quantitative evaluation. Metrics such as average heatmap intensity in ROI allow objective assessment of model focus. The code is modular: Cell 1 handles training, Cell 2 enables new image prediction, Cell 3 compares XAI methods, and Cell 4 computes metrics and ROC/AUC curves. This workflow bridges AI accuracy and interpretability for biomechanics and medical imaging research.

