# 🧠 TumorTrack - MRI-Based Brain Tumor Detection

TumorTrack is a medical image processing project focused on analyzing MRI scans in DICOM format. The goal is to preprocess MRI images, normalize pixel values, and detect potential anomalies (like tumors or lesions) using Python libraries such as NumPy, OpenCV, pydicom, and matplotlib.

---

## 🩺 Project Objective

To build an automated system that:
- Loads high-resolution MRI DICOM files
- Preprocesses the image for analysis
- Masks potential tumor regions
- Visualizes the MRI scan with highlighted anomalies

---

## 📂 Dataset

- Format: `.dcm` (DICOM)
- Source: Sample MRI scan files (can be extended using public datasets like TCIA or BraTS)

---

## 🛠️ Technologies Used

- **Python**
- **NumPy** – Efficient numerical computation
- **pydicom** – Reading medical DICOM images
- **OpenCV** – Image processing and resizing
- **matplotlib** – Visualization and plotting

---

## 📸 Project Workflow

1. **Load MRI scan using pydicom**
2. **Convert pixel data to NumPy array**
3. **Normalize and resize image**
4. **Detect high-intensity regions using NumPy masking**
5. **Display original vs processed image**

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/TumorTrack.git
   cd TumorTrack
