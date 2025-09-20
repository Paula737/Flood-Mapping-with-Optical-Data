# 🌊 Flood Rapid Mapping with Optical Data (Image Segmentation)  

An **AI-driven flood mapping system** that leverages **optical multispectral satellite imagery** and **deep learning segmentation models** to rapidly identify and monitor flood-affected regions.  
This project demonstrates the use of **U-Net with EfficientNet backbone** for robust, real-time disaster response.  

---

## 📖 Overview  

Floods are among the most frequent and devastating natural disasters.  
This project builds an **end-to-end pipeline** for **flood detection and segmentation** using **12-band optical satellite data**.  

✅ Contributions:  
- Preprocessing and combining **multi-channel masks**.  
- Band-level visualization and percentile-based contrast stretching.  
- Training a **custom U-Net + EfficientNet model** for binary segmentation (water vs background).  
- Deployment-ready data pipelines for **real-time disaster monitoring**.  

---

## 🎯 Objectives  

- **Data Preprocessing**  
  - Normalize multispectral bands.  
  - Combine binary masks into a single segmentation target.  
  - Contrast-stretch each band for improved clarity.  

- **Visualization**  
  - RGB composites (Bands 3, 2, 1 and alternative band selections).  
  - Per-band grayscale visualizations.  
  - Overlay of masks and predictions.  

- **Model Development**  
  - **Custom U-Net** with EfficientNetB0 encoder.  
  - Adapted for **10-band multispectral input**.  
  - Metrics: **Loss, Accuracy, Mean IoU**.  

---

## 🛠️ Technology Stack  

- **Language:** Python 3.x  
- **Frameworks:** TensorFlow, Keras  
- **Libraries:** NumPy, Pandas, OpenCV, TiffFile, PIL, Scikit-learn  
- **Visualization:** Matplotlib, Seaborn  
- **Compute Environment:** Kaggle / Google Colab (GPU-enabled)  

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/TIFF_File-009688?style=for-the-badge&logo=file&logoColor=white"/>
</p>  

---

👨‍💻 Author

✨ 𝑬𝒏𝒈. 𝒫𝒶𝓊𝓁𝒶 𝐻𝒶𝓃𝓃𝒶 𝒩𝒶𝑔𝓊𝒾𝒷 ✨

📌 “Knowledge is power. Applying AI to disaster management transforms information into life-saving insights.”
