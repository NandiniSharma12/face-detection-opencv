# face-detection-opencv
Real-time face detection using OpenCV and pre-trained Caffe model
# 🎯 Real-Time Face Detection Using OpenCV and Caffe Model

This project demonstrates real-time face detection using a webcam feed and a pretrained Caffe-based SSD (Single Shot Detector) model. The application uses OpenCV’s deep learning (`cv2.dnn`) module to process live video frames and detect faces with high accuracy.

---

## ⚙️ Project Overview

- Built using **Python** and **OpenCV** inside a **Conda-managed virtual environment**.
- Utilizes **Caffe Model** (`res10_300x300_ssd_iter_140000_fp16.caffemodel`) for face detection, paired with its configuration file (`deploy.prototxt`).
- Uses **4D Blob** conversion (`cv2.dnn.blobFromImage`) to prepare video frames for neural network input.

---

## 🤖 Why Caffe Model?

Caffe is a deep learning framework developed by Berkeley AI Research (BAIR). It is:
- Lightweight and **fast for inference**.
- Ideal for image processing tasks.
- Well-supported in OpenCV for **real-time computer vision** applications.

Compared to models like TensorFlow or PyTorch, Caffe is **less resource-intensive** and performs better on traditional CV tasks when speed is crucial.

---

Thanks! Here's your corrected `README.md` **with proper markdown syntax** — I’ve fixed the heading formatting, closed the code block, and made sure all sections are rendered correctly.

---Thanks! Here's your corrected `README.md` **with proper markdown syntax** — I’ve fixed the heading formatting, closed the code block, and made sure all sections are rendered correctly.

---


## ▶️ Environment Setup
````markdown
## 🧪 Environment Setup

We used the **Conda tool** to manage the environment. To recreate the environment:

```bash
conda env create -f environment.yml
conda activate cs-env
````

---


## ▶️ Run the Project

```bash
jupyter notebook
```

---

## 👤 Author

**Nandini Sharma**
🔗 [LinkedIn](https://www.linkedin.com/in/nandinisharma12)

---

## 🗂️ Assets

Model files are automatically downloaded at runtime from Dropbox, ensuring a smooth setup.

````

---
