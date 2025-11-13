#  Pearlite and Ferrite Phase Fraction Detection using U-Net Algorithm

## Project Overview

This project is developed with the aim of **automatically detecting and calculating the phase fractions of Pearlite and Ferrite** in steel microstructures. It leverages the **advanced U-Net deep learning algorithm** for precise semantic segmentation of metallurgical images.

This automated approach significantly enhances the efficiency and accuracy of steel microstructure analysis compared to traditional manual methods. 

---

##  Project Goals

The main objectives of this initiative are:

* **Automation** of the steel microstructure analysis process.
* Achieving **high accuracy** in identifying phase boundaries between Pearlite and Ferrite.
* **Precise calculation of the areal percentage** for each phase.
* **Reducing human error** in metallurgical analyses.

---

##  Key Technologies and Libraries

The project is built upon a foundation of deep learning and specialized image processing tools:

* **U-Net Neural Network:** Used for high-performance semantic image segmentation.
* **ImageJ:** Utilized for manual masking and generating reliable Ground Truth data for training.
* **Image Processing:** Techniques for image pre-processing (e.g., contrast enhancement) and post-processing (e.g., refinement of segmentation masks).
* **Python:** The core programming language.
* **OpenCV:** Employed for image analysis and manipulation.
* **Deep Learning Framework:** TensorFlow.

---

##  Core Features

Our solution provides the following key capabilities:

* **Intelligent Pre-processing:** Automated preparation of metallurgical images for optimal analysis.
* **Accurate Segmentation:** Precise distinction of Pearlite and Ferrite regions.
* **Areal Percentage Calculation:** Statistical algorithms for calculating the phase fraction of each component.
* **Quantitative Output:** Automatic generation of reports and quantifiable results.

---

##  Applications

The developed tool has broad applications across industry and research:

* **Quality Control (QC):** Rapid and consistent microstructure analysis in the steel industry.
* **Metallurgical Research:** A powerful tool for materials science studies.
* **Laboratory Microstructure Analysis:** Standardizing and speeding up lab tests.
* **Heat Treatment Optimization:** Assisting in the fine-tuning of thermal processes based on resulting phase fractions.

---

## 📊 Results and Performance Comparison

The table below compares the calculated phase fraction (e.g., Pearlite percentage) achieved by the proposed U-Net Model against results obtained from a standard reference tool (Metal Software) for various images.

| Image | Metal Software (%) | U-Net Model (%) |
| :---: | :---: | :---: |
| Image 1 | 18.97 | 18.53 |
| Image 2 | 25.95 | 20.24 |
| Image 3 | 21.80 | 18.80 |
| Image 4 | 23.57 | 19.20 |

