# 🧠 Brain Tumor Detection using Deep Learning

A deep learning-based medical image classification system that detects and classifies brain tumors from MRI images using CNN and MobileNetV2.

The model analyzes MRI scan images and predicts tumor categories using transfer learning and image preprocessing techniques.

---

## Features

✅ Brain MRI image classification

✅ Detects multiple tumor categories

✅ Uses CNN + MobileNetV2 architecture

✅ Data augmentation support

✅ Duplicate image cleaning

✅ Training and testing pipelines

✅ Performance evaluation metrics

✅ Video demonstration included

---

## Tumor Classes

- Glioma
- Meningioma
- Pituitary
- No Tumor

---

## Technologies Used

- Python
- TensorFlow
- Keras
- MobileNetV2
- CNN
- OpenCV
- NumPy
- Matplotlib
- Scikit-Learn
- Streamlit

---

## Dataset Structure

```text
Training/
    glioma/
    meningioma/
    notumor/
    pituitary/

Testing/
    glioma/
    meningioma/
    notumor/
    pituitary/
```

---

## Project Workflow

1. Load MRI dataset

2. Clean duplicate images

3. Apply preprocessing

4. Apply image augmentation

5. Train deep learning model

6. Validate performance

7. Predict tumor category

8. Display classification result

---

## Installation

Clone repository:

```bash
git clone https://github.com/yourusername/Brain-Tumor-Detection.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run notebooks:

```bash
jupyter notebook
```

Open:

PROJECT_MODEL_1.ipynb

or

PROJECT_MODEL_2.ipynb

---

## Model Architecture

Transfer Learning:

MobileNetV2

Additional Layers:

- GlobalAveragePooling
- Dropout
- Dense Layers
- Softmax Classifier

---

## Example Prediction

Input:

MRI Scan Image

Output:

Prediction: Glioma

Confidence: 96%

---

## Demo Video

Project output video available:

```text
demo/OUTPUT FOR PROJECT MODEL 1.mp4
```

You can watch the complete prediction workflow in the repository.

---

## Future Improvements

- Real-time prediction system
- Web deployment
- Medical report generation
- Tumor localization using segmentation
- Multi-model comparison

---

## Author

Kishore G
