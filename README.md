# 🔍 Deepfake Content Detection System

A deep learning web application that detects deepfake media with **91% accuracy**, built with a custom CNN and deployed via Flask REST API.

## 🎯 Results
- ✅ 91% accuracy on 500-image labelled test set
- ✅ 18% reduction in false-positive rate vs. baseline SVM
- ✅ Classifies uploaded media in under 3 seconds
- ✅ 30% reduction in debug time via reproducible Jupyter notebook

## 🛠️ Tech Stack
| Category | Tools |
|---|---|
| Deep Learning | TensorFlow, Keras |
| Image Processing | OpenCV, NumPy |
| Data Analysis | Pandas, Scikit-learn |
| Deployment | Flask REST API |
| Frontend | HTML, CSS, JavaScript |

## 📌 How It Works
1. User uploads an image/video via web interface
2. Flask API sends it to the trained CNN model
3. Model extracts 12 image-level features using OpenCV
4. CNN classifies it as **Real** or **Deepfake**
5. Result returned in under 3 seconds

## 👨‍💻 About
Built by **Vishnu Najardhane** — 3rd year CS student at GCE Jalgaon  
📧 najardhanevishnu@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/vishnu-najardhane-13892b28a)  
🌐 [Portfolio](https://vishnu-najardhane.github.io)
