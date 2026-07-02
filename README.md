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
<img src="https://github.com/jrafa1607/Digital_Gauge_Solution_CV/blob/main/Attachments/svc.jpeg">

### System Output (Processed Data)
<img src="https://github.com/jrafa1607/Digital_Gauge_Solution_CV/blob/main/Attachments/result.jpeg">

---
### 📋 Reference Key (Test Data)
The table below presents the ground truth values for each image analyzed in the dataset.

| Name File | Values |
| :--- | :---: |
| img01.BMP | 63063 |
| img02.BMP | 00692 |
| img03.BMP | 03446 |
| img04.BMP | 04392 |
| img05.BMP | 05276 |
| img06.BMP | 06579 |
| img07.BMP | 07584 |
| img08.BMP | 07670 |
| img09.BMP | 07999 |
| img10.BMP | 08450 |

---

## 🛠 Technologies Used
* **Language:** Python
* **Main Library:** OpenCV
* **Concepts:** Image pre-processing, Character recognition, Thresholding, Contour detection.

---
