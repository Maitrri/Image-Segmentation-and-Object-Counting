# 🧠 Object Detection and Counting via Image Segmentation

## 📌 Overview
This project implements object detection and counting in static images using various **image segmentation techniques**. The focus is on three core methods:
- **Thresholding segmentation**
- **Edge-based segmentation**
- **Region-based segmentation**

Each method processes images to isolate and count object instances effectively.

---

## 🎯 Objective
To accurately count the number of object instances in an image using classical image segmentation approaches such as adaptive thresholding, morphological operations, and region labeling.

---

## 🛠️ Steps Applied

1. **Image Selection and Conversion**  
   Load and convert RGB images to grayscale for uniform processing.

2. **Gamma Correction**  
   Improve contrast and clarity of images before segmentation.

3. **Threshold Segmentation**  
   Apply local adaptive thresholding to separate foreground objects from the background.

4. **Erosion and Dilation (Morphological Operations)**  
   Clean up noise and connect broken parts of segmented objects.

5. **Labeling and Counting**  
   Use connected component labeling to count distinct object instances.

---

## 🚀 Usage

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/object-detection-and-counting.git
```

### 2. Navigate to the Project Directory
```bash
cd object-detection-and-counting
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Script
```bash
python object_counter.py
```

---

## 📦 Requirements

- Python 3.x  
- OpenCV (`cv2`)  
- NumPy  
- Matplotlib  

Install them using:
```bash
pip install opencv-python numpy matplotlib
```

---

## 🙋‍♀️ Questions?
Feel free to open an issue or contact me on [LinkedIn](https://www.linkedin.com/in/maitrrichandra).

