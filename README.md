# 📌 Implementation of Canny Edge Detection using OpenCV in Python

## 📖 Description  
This project implements the Canny Edge Detection algorithm, a widely used technique in computer vision for detecting edges in images. It identifies object boundaries by detecting intensity changes in the image.

The algorithm follows a multi-stage process to produce accurate and noise-free edge detection results.

---

## 🎯 Objectives  
- To detect edges in images using the Canny algorithm  
- To understand basic image processing techniques  
- To build a command-line executable project  

---

## ⚙️ Features  
- Converts image to grayscale  
- Applies Gaussian blur for noise reduction  
- Detects edges using Canny algorithm  
- Saves output image automatically  
- Simple command-line interface  

---

## 🛠️ Tech Stack  
- Python  
- OpenCV  
- NumPy  

---

## 📂 Project Structure  
canny-edge-detection/  
│── main.py  
│── README.md  
│── requirements.txt  
│── sample_images/  
│     └── input.jpg  
│── output/  
│     └── edges.jpg  

---

## ⚡ Installation  

git clone https://github.com/your-username/canny-edge-detection  
cd canny-edge-detection  
pip install -r requirements.txt  

---

## ▶️ Usage  

python main.py --image sample_images/input.jpg  

---

## 📸 Output  

output/  
 └── edges.jpg  

- edges.jpg → Final edge-detected image  

(Optional)  

output/  
 ├── original.jpg  
 └── edges.jpg  

---

## 🧠 Algorithm Steps  

1. Noise Reduction (Gaussian Blur)  
2. Gradient Calculation (Sobel Operator)  
3. Non-Maximum Suppression  
4. Double Thresholding  
5. Edge Tracking by Hysteresis  

---

## ⚠️ Important Notes  
- Ensure correct image path is provided  
- Run the project from command line  
- Output is automatically saved in output folder  

---

## 📌 Conclusion  
This project demonstrates how edge detection can be performed using the Canny algorithm. It highlights key concepts of image processing and computer vision.

---

## 👨‍💻 Author  
Sougat (23BAI11043)
