# Canny Edge Detection using OpenCV

## Description
This project focuses on detecting edges in images using the Canny Edge Detection algorithm. Edge detection is an important concept in image processing, as it helps in identifying object boundaries and important features in an image.

In this project, an input image is taken, processed using OpenCV, and the edges are extracted and saved as an output image.

---

## Objective
The main objective of this project is to understand how edge detection works and to implement it using Python and OpenCV.

---

## Tools Used
- Python  
- OpenCV  
- NumPy  

---

## Project Structure
canny-edge-detection  
- main.py  
- requirements.txt  
- README.md  
- sample_images/  
- output/  

---

## How to Run

1. Clone the repository  
git clone https://github.com/your-username/canny-edge-detection  

2. Go to the project folder  
cd canny-edge-detection  

3. Install dependencies  
pip install -r requirements.txt  

4. Run the program  
python main.py --image sample_images/input.jpg  

---

## Output
After running the code, the output image will be saved in the output folder.

- edges.jpg → contains the detected edges  
- (optional) original.jpg → input image for comparison  

---

## Working
The program follows these basic steps:
- Convert image to grayscale  
- Apply Gaussian blur to remove noise  
- Detect edges using Canny algorithm  
- Save the output image  

---

## Note
Make sure the image path is correct before running the program. The output folder will be created automatically if it does not exist.

---

## Author
Sougat (23BAI11043)
