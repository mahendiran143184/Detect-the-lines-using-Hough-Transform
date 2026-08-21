#  Lane Detection

##  Aim

To implement a basic lane detection pipeline using OpenCV by completing missing code segments at specified locations.

---

## Learning Objective

* Understand each stage of image processing
* Learn how to build a complete computer vision pipeline
* Practice writing code in guided sections

**Important Instruction:**
👉 Write code **ONLY in places marked as `# Your Code Here`**
👉 Do NOT modify any other part of the code

---

##  Software Used

* Anaconda – Python 3.7
* Jupyter Notebook / VS Code
* OpenCV (cv2)
* NumPy
* Matplotlib

---

##  Algorithm & Explanation

---

###  Step 1: Import Libraries

```python
import cv2
import numpy as np
import matplotlib.pyplot as plt
```

---

###  Step 2: Read the Image

```python
# Read the image using OpenCV

###
# Your Code Here
###
```

---

###  Step 3: Convert to Grayscale

```python
# Convert to grayscale.

###
# Your Code Here
###
```

---

###  Step 4: Display Images

```python
plt.figure(figsize=(10,5))

###
# Your Code Here
###
```

---

###  Step 5: Thresholding

```python
# Apply thresholding

threshold = 
###
# Your Code Here
###
```

---

###  Step 6: Region of Interest (ROI)

```python
# ROI masking already provided
# (Do not modify)
```

---

### Step 7: Edge Detection (Canny)

```python
# Perform Edge Detection

###
# Your Code Here
###
```

---

###  Step 8: Gaussian Blur

```python
# Apply Gaussian Blur

###
# Your Code Here
###
```

---

###  Step 9: Hough Transform

```python
# Detect lines using Hough Transform

###
# Your Code Here
###
```

---

### Step 10: Lane Detection Logic

```python
# Already implemented
# (Do not modify)
```

---

##  Expected Output

* Original image
<img width="211" height="135" alt="image" src="https://github.com/user-attachments/assets/249d3316-cd23-44a5-8190-12e90202945f" />


  
* Grayscale image
  <img width="221" height="135" alt="image" src="https://github.com/user-attachments/assets/825e511b-58b1-4a27-9b25-7256d0aac788" />

* Thresholded image
  <img width="227" height="138" alt="image" src="https://github.com/user-attachments/assets/071aa067-8b7c-4004-893b-2c39120abb1f" />

* ROI masked image
  <img width="211" height="137" alt="image" src="https://github.com/user-attachments/assets/bd1bcda1-51cb-48b6-b3c6-b6eb9c55dbea" />

* Edge detected image
  <img width="218" height="140" alt="image" src="https://github.com/user-attachments/assets/40c1c803-dce6-4cd1-9e9b-339c127a727b" />

* Smoothed image
  <img width="223" height="142" alt="image" src="https://github.com/user-attachments/assets/f1f237b8-eb93-455f-970c-996bc962c26f" />

* Detected lines
  <img width="217" height="146" alt="image" src="https://github.com/user-attachments/assets/0cebcdf7-18a6-44c1-86a9-b3603b053f7a" />

* Final lane detection output
  <img width="231" height="150" alt="image" src="https://github.com/user-attachments/assets/acb96d03-5f3b-4740-90e5-7aafbc682432" />


---

##  Instructions

* Fill ONLY in `# Your Code Here` sections
* Do NOT change existing code
* Run step-by-step
* Verify outputs

---

## Result

Thus, the lane detection pipeline is successfully implemented by completing the missing code sections. The system detects and highlights lane lines effectively.

---

##  Developed By

* **Name:** M.MAHENDIRAN
* **Register No:** 212225230165
