# DriveGuard-Driver-Distraction-Detection
Deep learning project for detecting distracted driving behaviors using the State Farm Distracted Driver Detection dataset. Includes training scripts, Jupyter notebook, and pretrained model support.
# 🚗 Distracted Driver Detection (State Farm Dataset)

## 📌 Overview
This project detects distracted driving behaviors using **deep learning** and the **State Farm Distracted Driver Detection** dataset from Kaggle. It classifies images into 10 categories such as:
- Safe driving
- Texting (left/right)
- Talking on phone (left/right)
- Operating the radio
- Drinking
- Reaching behind
- Hair & makeup
- Talking to passengers

---

## 📂 Dataset
Download from Kaggle:  
👉 [State Farm Distracted Driver Detection](https://www.kaggle.com/competitions/state-farm-distracted-driver-detection/data)

**Classes:**
- c0: safe driving  
- c1: texting - right hand  
- c2: talking on the phone - right hand  
- c3: texting - left hand  
- c4: talking on the phone - left hand  
- c5: operating the radio  
- c6: drinking  
- c7: reaching behind  
- c8: hair and makeup  
- c9: talking to passenger  

---

## ⚙️ Installation
```bash
git clone https://github.com/your-username/distracted-driver-detection.git
cd distracted-driver-detection
pip install -r requirements.txt
