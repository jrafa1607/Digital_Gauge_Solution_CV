# ⏰ Digital Clock Solution - Automatic Gauge Reader

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-Computer_Vision-green?logo=opencv)](https://opencv.org/)

## 📝 Project Description
The **Digital Clock Solution** is a Computer Vision System (CVS) developed to optimize data collection from digital pressure gauges. The system automates the display reading process, eliminating human error and ensuring agility in capturing critical values in industrial or laboratory environments.

---

## 🎯 Objectives
The system was designed to process images captured by cameras, performing real-time character recognition and applying the following rules:

- [x] **Digit Recognition:** Precise identification of the numbers displayed.
- [x] **Visual Output:** Immediate display of the values read on the computer screen.
- [x] **Data Cleaning:** Processing to exclude irrelevant characters, such as the decimal point.

---

## 📸 Visual References

### System Input (Original Image)
<img src="https://github.com/jrafa1607/Computational-Vision-In-Python/blob/main/Digital%20Clock%20Solution/Anexos/svc.jpeg" width="400">

### System Output (Processed Data)
<img src="https://github.com/jrafa1607/Computational-Vision-In-Python/blob/main/Digital%20Clock%20Solution/Anexos/Resultado.jpeg" width="400">

---

## 📋 Test Reference (Ground Truth)
Below is the comparison used to validate the accuracy of the reading algorithm.

<img src="https://github.com/jrafa1607/Computational-Vision-In-Python/blob/main/Digital%20Clock%20Solution/Anexos/Gabarito.jpeg" width="600">

---

## 🛠 Technologies Used
* **Language:** Python
* **Main Library:** OpenCV
* **Concepts:** Image pre-processing, Character recognition, Thresholding, Contour detection.

---
