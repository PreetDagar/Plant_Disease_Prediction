# 🌿 Plant Disease Detection Using Deep Learning

## 📌 Project Overview

Plant diseases can negatively affect crop quality, agricultural productivity, and farmers' income. Early identification of plant diseases can help farmers take appropriate action and reduce crop losses.

**Plant Disease Detection** is a machine-learning project designed to identify plant diseases from leaf images using image classification and deep learning. The project aims to classify leaf images into the disease categories supported by the trained model.

The project can be used to explore image preprocessing, dataset preparation, model training, model evaluation, and prediction using a trained deep-learning model.

## 🎯 Objectives

* Detect plant diseases from leaf images.
* Classify plant leaves into supported disease categories.
* Apply image preprocessing techniques before prediction.
* Train or use a deep-learning image classification model.
* Evaluate model performance using suitable metrics.
* Demonstrate how artificial intelligence can support agricultural applications.

## ✨ Features

* Plant leaf image input.
* Image preprocessing for model inference.
* Deep-learning-based image classification.
* Prediction of supported plant disease classes.
* Support for a saved model, such as a `.keras` file, if included.
* Jupyter Notebook-based experimentation, if included.
* Sample images for testing and demonstration.

*Features should be adjusted to match the functionality actually implemented in the repository.*

## 🛠️ Technologies Used

* **Python** — primary programming language.
* **TensorFlow / Keras** — deep-learning model development and inference, if used.
* **NumPy** — numerical operations.
* **Pandas** — dataset handling, if required.
* **Matplotlib** — visualization of training results, if used.
* **Pillow / OpenCV** — image loading and preprocessing, depending on the implementation.
* **Jupyter Notebook** — experimentation and model development.
* **Git and GitHub** — version control and project hosting.

## 📂 Project Structure

The following is an example structure. Update the filenames to match your repository.

```text
Plant-Disease-Detection/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── notebooks/
│   └── plant_disease_detection.ipynb
│
├── models/
│   └── plant_disease_model.keras
│
├── src/
│   ├── preprocessing.py
│   └── prediction.py
│
├── data/
│   └── sample_images/
│       ├── leaf_sample_1.jpeg
│       └── leaf_sample_2.jpeg
│
└── config/
    └── class_indices.json
```

Not every file or folder shown above is required. Keep only the entries that exist in your project, and document any additional important files.

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/PreetDagar/Plant-Disease-Detection.git
```

Navigate into the project directory:

```bash
cd Plant-Disease-Detection
```

### 2. Create a virtual environment

For macOS:

```bash
python3 -m venv venv
```

Activate the environment:

```bash
source venv/bin/activate
```

### 3. Install dependencies

If the project includes a `requirements.txt` file, run:

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

If no dependency file exists, create one containing the packages actually used by the project. For example, a TensorFlow/Keras implementation may require TensorFlow, NumPy, and Pillow. Check your code and compatible package versions before installing.

## ▶️ How to Run the Project

The exact execution command depends on the files included in the repository.

### Option 1: Run the Jupyter Notebook

Install Jupyter if it is not already included in the dependencies:

```bash
pip install notebook
jupyter notebook
```

Open the plant disease detection notebook in your browser and execute its cells in the documented order.

### Option 2: Run a Python prediction script

If your project includes a prediction script, run the actual script name. For example:

```bash
python predict.py
```

This command is applicable only if `predict.py` exists and supports command-line execution.

### Option 3: Load a trained Keras model

If a trained `.keras` model is included, a basic loading example is:

```python
import keras

model = keras.models.load_model("models/plant_disease_model.keras")

print("Model loaded successfully!")
```

Replace the path with the actual location of your model. The required package version and any custom model components must be compatible with the saved model.

## 🧠 Project Workflow

1. **Dataset collection:** Obtain plant leaf images and their corresponding labels from an authorized dataset.
2. **Data preparation:** Organize images into the classes required by the project.
3. **Preprocessing:** Resize and normalize images according to the model's training configuration.
4. **Model development:** Train or load the selected image classification model.
5. **Model evaluation:** Assess performance on suitable validation or test data.
6. **Prediction:** Process a new leaf image and generate a prediction.
7. **Result interpretation:** Map the model output to the appropriate class label.

The exact model architecture, image dimensions, preprocessing steps, and class names depend on the implementation.

## 📊 Model Evaluation

A plant disease classification model can be evaluated using metrics such as:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion matrix

Include only the metrics actually calculated by your project, and report numerical results only after obtaining them from a reproducible evaluation.

**Model accuracy:** Not reported here because the actual evaluation results have not been verified.

## 🖼️ Sample Images

The repository may include sample healthy and diseased leaf images for testing and demonstration.

Add screenshots or sample predictions here once you have verified them. Ensure that the images are authorized for redistribution and that any required credits are retained.

## 📁 Dataset

Document the dataset used by your implementation, including:

* Dataset name and source.
* Plant species represented.
* Disease categories included.
* Number of images, if known.
* Training, validation, and test split, if used.
* Dataset license and attribution requirements.

If the complete dataset is too large or cannot be redistributed, provide a link to its official source rather than committing the entire dataset to GitHub.

## ⚠️ Limitations

* Predictions depend on the quality and variety of the training data.
* Image lighting, background, leaf orientation, and image quality may affect results.
* The model may not recognize diseases that were not represented in its training classes.
* A predicted class is not a guarantee of a correct diagnosis.
* Performance on laboratory or curated images may differ from performance in real agricultural environments.

This project should be treated as an educational or decision-support tool, not as a replacement for expert agricultural diagnosis.

## 🔮 Future Improvements

Potential improvements include:

* Adding more plant species and disease categories.
* Improving dataset diversity and image quality.
* Evaluating performance on independent field images.
* Developing a web interface for image uploads.
* Adding confidence scores and clearer prediction explanations.
* Deploying the model through an API or mobile application.

These are possible future enhancements, not claims about existing features.

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Test the changes.
5. Submit a pull request with a clear description.

Please ensure that contributions respect the licenses of datasets, pretrained models, and third-party code.

## 📜 License and Attribution

Add a `LICENSE` file that reflects the rights you have to distribute this project. Do not assume that all included code, datasets, images, or trained models can be redistributed under the same license.

Acknowledge the original authors and sources of any third-party code, datasets, images, or pretrained models as required by their licenses.

## 👨‍💻 Author

**GitHub:** [PreetDagar](https://github.com/PreetDagar)

## ⭐ Support

If you find this project useful for learning about deep learning and agricultural image classification, consider giving the repository a star.

---

*Disclaimer: This project is intended for educational and research purposes. Predictions should be independently verified before making crop treatment or agricultural management decisions.*

