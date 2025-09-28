# PalmWildNet  

**PalmWildNet** is a deep learning framework for **mobile palmprint recognition**, designed with **residual blocks + SE blocks** and optimized using **Triplet Loss**.  
It is introduced together with the **MPW-180 dataset**, a mobile palmprint corpus captured across multiple devices, illumination conditions (flash / non-flash), and realistic environments.  

---

## 🔥 Features  
- Residual + SE block architecture tailored for palmprint recognition  
- Metric learning with Triplet Loss for robust embedding space  
- Preprocessing scripts for ROI extraction and normalization  
- Evaluation protocols for **cross-illumination** scenarios  
- Benchmark results on MPW-180 and other public palmprint datasets  

## 📂 Repository Structure  

PalmWildNet/
│
├── src/ # Model code and training scripts
├── preprocessing/ # ROI extraction and dataset preparation
├── experiments/ # Evaluation scripts and configs
├── examples/ # Sample visualizations and figures
├── LICENSE # Apache 2.0 license for the code
├── DATASET_LICENSE # CC BY-NC 4.0 license for the dataset
└── README.md

## 📊 Dataset: MPW-180  

- **Subjects:** 180 (current release; larger annotated extension in progress)  
- **Devices:** Multiple smartphones (e.g., iPhone, Android models)  
- **Conditions:** Flash / non-flash, indoor/outdoor, shadowed & mixed-lighting  
- **Samples:** 720 videos, thousands of ROI images  

👉 [Dataset DOI / Link]  

## License

- **Code (PalmWildNet framework, scripts):** Licensed under the Apache License 2.0.  
- **Dataset (MPW-180):** Released under the CC BY-NC 4.0 license (academic and non-commercial use only).  

## ✍️ Citation

If you use PalmWildNet or MPW-180 in your research, please cite:

@article{PalmWildNet2025,
  title   = {A Video-Based Mobile Palmprint Dataset and an Illumination-Robust Deep Learning Architecture for Unconstrained Environments},
  author  = {Koşmaz Sünnetci, Betül and Bingöl, Özkan and Gedikli, Eyüp and Ekinci, Murat and Doğan, Ramazan Özgür and Türk, Salih and Güngör, Nihan},
  journal = {Applied Sciences},
  publisher= {MDPI},
  year    = {2025},
  note    = {under review}
}
