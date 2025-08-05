# 🔐 Fingerprint Liveness Detection using DTCWT and MHSA

This project implements a fingerprint liveness detection system to distinguish between real and spoofed fingerprints. It uses **Dual Tree Complex Wavelet Transform (DTCWT)** for feature extraction and **Multi-Head Self Attention (MHSA)** to enhance spoof detection accuracy.



## 📚 Project Description

Biometric authentication systems are increasingly targeted by spoofing attacks using fake fingerprints. This project improves biometric security by building a robust liveness detection model. The model extracts high-frequency fingerprint details using DTCWT and leverages MHSA to focus on informative regions, improving classification between live and fake samples.



## 🚀 Tech Stack

- **Language:** Python  
- **Environment:** Jupyter Notebook  
- **Libraries:** NumPy, PyTorch, OpenCV, Matplotlib, scikit-learn  
- **Techniques Used:**  
  - Dual Tree Complex Wavelet Transform (DTCWT)  
  - Multi-Head Self Attention (MHSA)  


## 🧠 Key Features

- Real vs. Fake fingerprint classification  
- DTCWT-based feature extraction  
- MHSA module to improve spatial attention  
- Trained on fingerprint liveness datasets  
- Model export and validation accuracy monitoring  



## 🧪 Dataset

- **Classes:** `live` and `fake`  
- **Structure:** Images stored in separate `train` and `test` folders  
- **Source:** IIT Bombay Fingerprint Dataset

---

## 📊 Results

Real:
| Metric         |      Value     |
|----------------|----------------|
| Accuracy       |     97.53%     |
| Precision      |     96.34%     |
| Recall         |     98.75%     |
| Model Used     |  DTCWT + MHSA  |





