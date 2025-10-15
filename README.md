# Deep Architectures for Medical Image Segmentation  
*A Comparative Study on BraTS 2020 Brain Tumor MRI Dataset*  

## 🧠 Overview  
This project compares four U-Net–based architectures — **Vanilla U-Net**, **U-Net++**, **Attention U-Net**, and **Swin U-Net** — for automated brain tumor segmentation on the **BraTS 2020** dataset.  
It evaluates how dense skip connections, attention gates, and transformer-based encoders impact segmentation accuracy.

## ⚙️ Highlights  
- Implemented 4 U-Net variants in **PyTorch**  
- Multimodal MRI inputs: *T1, T1c, T2, FLAIR*  
- Metrics: **Dice**, **Jaccard**, qualitative overlays  
- Best performance: *Attention U-Net* — **Dice = 0.893**, **Jaccard = 0.812**

## 🚀 Usage  
```bash
git clone https://github.com/Aditya-dev5/BMEN4460-Deep-Learning-in-Biomedical-Imaging.git
cd BMEN4460-Deep-Learning-in-Biomedical-Imaging
