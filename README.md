# MRI Reconstruction Using complex-valued convolutional neural network


This repository presents the **official implementation of FSSCAN (Frequency–Spatial Skip Connection Attention Network)** for accelerated MRI reconstruction. FSSCAN is a **complex-valued deep learning architecture** designed to effectively exploit both frequency-domain and image-domain information for high-quality MRI recovery.

In addition to the proposed FSSCAN model, this repository includes implementations of several **state-of-the-art (SOTA) MRI reconstruction methods**, comprehensive **ablation studies**, and reusable **complex-valued convolutional neural network modules**.

---
## 🎯 Project Objectives

- Accelerated MRI reconstruction using deep learning  
- Comparison of proposed TEID-Net with SOTA methods  
- Ablation study for architecture analysis  
- Proper handling of complex-valued MRI data  

---
## 📂 Repository Structure

- **Ablation study/** – Ablation experiments for model analysis  
- **DCRCNN_code/** – DCR-CNN implementation  
- **DMSENet_code/** – DMSENet implementation  
- **Data/** – undersampling masks  
- **FSSCAN_Revision/** – FSSCAN experiments  
- **Modules-20260202.../Modules** – Complex-valued neural network components  
- **RNLF_code/** – RNLF model implementation  
- **SOTA_paper_2_HFGN/** – HFGN implementation  
- **TEID_Code/** – TEID-Net implementation  
- **Unet_code/** – U-Net baseline implementation  

Each model is organized in a separate folder with training and testing scripts.

### 📥 Dataset for Ablation Studies

The dataset subsets used for ablation studies (including **training**, and **validation**) can be downloaded from the following Google Drive link:

👉 train : https://drive.google.com/drive/folders/1uqKEVBWeeDOZv3QKsYBA_4GHt0uww7hK?usp=drive_link

👉 Val : https://drive.google.com/drive/folders/1syxbiZyVPZcFCcw8q15TMIBSoTnOGlsL?usp=drive_link


