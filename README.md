# 🌿 AI Plant Disease Detection Using Deep Learning

## 📌 Project Overview

**AI Plant Disease Detection** is a Deep Learning-based image classification project designed to identify plant diseases from leaf images.

The project uses the **PlantVillage dataset** through **TensorFlow Datasets (TFDS)**. Plant leaf images are processed and provided to a Deep Learning image classification model to predict the corresponding plant disease class.

The main objective of this project is to demonstrate how **Artificial Intelligence, Deep Learning, and Computer Vision** can be applied to the agricultural domain for automated plant disease detection.

---

## 🎯 Objectives

* Detect plant diseases from leaf images using Deep Learning.
* Use the PlantVillage dataset for image classification.
* Preprocess plant leaf images before model training.
* Train a Deep Learning classification model.
* Evaluate the trained model using appropriate performance metrics.
* Predict the disease class of a new plant leaf image.
* Demonstrate an AI-based application in the field of smart agriculture.

---

## 🗂️ Dataset

### PlantVillage Dataset

This project uses the **PlantVillage** dataset for training and evaluating the plant disease classification model.

The dataset is loaded programmatically using **TensorFlow Datasets** instead of manually storing the complete dataset inside this GitHub repository.

The dataset loading code used in the project is:

```python
import tensorflow as tf
import tensorflow_datasets as tfds

(ds_all, ds_info), = tfds.load(
    "plant_village",
    split=["train"],
    as_supervised=True,
    with_info=True
)
```

The complete dataset is therefore **not included in this repository** because of its size.

---

## 🧠 Model

The project uses a **Deep Learning-based image classification approach**.

The exact model architecture and configuration used for the final experiment are implemented directly inside:

```text
SantanuMandal_PlantDiseaseDetection.ipynb
```

The notebook contains the complete implementation of:

* Dataset loading
* Image preprocessing
* Dataset preparation
* Model creation
* Model compilation
* Model training
* Model evaluation
* Disease prediction

> **Important:** The model name and architecture in this README should match the final model actually used in the notebook. The notebook is the source of truth for the final implementation.

---

## 🔄 Project Workflow

```text
PlantVillage Dataset
        ↓
Dataset Loading using TFDS
        ↓
Image Preprocessing
        ↓
Dataset Preparation
        ↓
Deep Learning Model
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Disease Prediction
```

---

## 🖼️ Image Preprocessing

Before training, plant leaf images are prepared for the Deep Learning model.

The preprocessing pipeline includes the operations implemented in the notebook, such as:

* Image resizing
* Pixel-value normalization
* Dataset preparation
* Training/validation/test data preparation where applicable

The exact preprocessing configuration can be found in the project notebook.

---

## 🔧 Technologies Used

| Technology          | Purpose                        |
| ------------------- | ------------------------------ |
| Python              | Programming                    |
| TensorFlow          | Deep Learning                  |
| TensorFlow Datasets | PlantVillage dataset loading   |
| Keras               | Model development and training |
| NumPy               | Numerical operations           |
| Matplotlib          | Visualization                  |
| Pandas              | Data handling                  |
| Scikit-learn        | Model evaluation               |
| Pillow              | Image processing               |
| Jupyter Notebook    | Project development            |

---

## 📁 Repository Structure

```text
AI-Plant-Disease-Detection/
│
├── SantanuMandal_PlantDiseaseDetection.ipynb
├── requirements.txt
├── README.md
└── Project_Report.pdf
```

### File Description

#### `SantanuMandal_PlantDiseaseDetection.ipynb`

This is the **main project file**.

It contains the complete Python implementation of the project, including:

* Importing required libraries
* Loading the PlantVillage dataset
* Exploring the dataset
* Image preprocessing
* Dataset preparation
* Deep Learning model
* Model training
* Model evaluation
* Visualization
* Plant disease prediction

#### `requirements.txt`

Contains the Python libraries required to run the project.

#### `README.md`

Contains the project description, setup instructions, workflow, and documentation.

#### `Project_Report.pdf`

Contains the detailed project report and documentation.

---

## 💻 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/AI-Plant-Disease-Detection.git
```

### 2. Open the Project Folder

```bash
cd AI-Plant-Disease-Detection
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

If TensorFlow Datasets is not installed, run:

```bash
pip install tensorflow-datasets
```

---

## ▶️ How to Run the Project

1. Install Python.
2. Install the required dependencies.
3. Open the repository in **VS Code** or **Jupyter Notebook**.
4. Open:

```text
SantanuMandal_PlantDiseaseDetection.ipynb
```

5. Run the notebook cells sequentially.
6. The notebook will load the PlantVillage dataset using TensorFlow Datasets.
7. The images will be processed according to the implemented preprocessing pipeline.
8. The Deep Learning model will be trained.
9. The model will be evaluated.
10. A plant leaf image can then be used for disease prediction according to the prediction code in the notebook.

---

## 📊 Model Evaluation

The project evaluates the trained model using the evaluation methods implemented in the notebook.

Possible evaluation outputs include:

* Training accuracy
* Validation accuracy
* Training loss
* Validation loss
* Confusion matrix
* Classification report
* Prediction results

### Results

The **final numerical results are intentionally not hard-coded in this README**.

The actual accuracy, loss, and other performance values should be taken from the **final training run of the notebook** rather than using estimated or example values.

This ensures that the results reported on GitHub correspond to the actual experiment performed in this project.

---

## 🔍 Disease Prediction

After training, the model can be used to predict the class of a plant leaf image.

The prediction process follows:

```text
Input Leaf Image
       ↓
Image Preprocessing
       ↓
Trained Deep Learning Model
       ↓
Class Prediction
       ↓
Predicted Plant Disease
```

The prediction implementation is available in:

```text
SantanuMandal_PlantDiseaseDetection.ipynb
```

---

## 🌱 Applications

This project demonstrates potential applications of AI in:

* Smart Agriculture
* Crop Monitoring
* Plant Health Monitoring
* Automated Disease Detection
* Agricultural Research
* Precision Agriculture

---

## ⚠️ Limitations

* The model's performance depends on the quality and diversity of the training dataset.
* PlantVillage images may differ from photographs taken in real-world field conditions.
* Some diseases can have visually similar symptoms.
* The system provides an AI-based image classification result and should not be considered a replacement for professional agricultural diagnosis.

---

## 🚀 Future Scope

The project can be further improved by:

* Developing a web-based application.
* Developing a mobile application.
* Adding more plant species and disease classes.
* Training with real-world field images.
* Adding disease severity detection.
* Providing disease prevention information.
* Providing treatment recommendations from verified agricultural sources.
* Deploying the model for real-time camera-based detection.

---

## 👨‍💻 Author

**Santanu Mandal**

### Project Title

**AI Plant Disease Detection Using Deep Learning**

### Project Type

Academic / Internship Project

### Domain

Artificial Intelligence • Deep Learning • Computer Vision • Smart Agriculture

---

## 📚 References

* PlantVillage Dataset
* TensorFlow Documentation
* TensorFlow Datasets Documentation
* Keras Documentation
* Python Documentation

---

## ⭐ Conclusion

This project demonstrates the use of **Artificial Intelligence and Deep Learning for automated plant disease classification**.

By using plant leaf images from the PlantVillage dataset, the system processes the images and uses a trained Deep Learning model to identify the corresponding disease class.

The project provides a practical example of how Computer Vision and Deep Learning techniques can be applied to agricultural problems.
