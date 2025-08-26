# ML-Projects

A collection of machine learning projects created in early 2024. All notebooks were developed and run using **Google Colab**, and make use of common Python libraries such as **pandas**, **matplotlib**, and **scikit-learn**.

## Projects

### 1. Digit Classification (`Digit_Classification.ipynb`)

Builds and evaluates a model to classify handwritten digits. Likely uses the MNIST dataset. Demonstrates data preprocessing, model training, and performance evaluation.

### 2. Emotion Detector (`Emotion-Detector.ipynb`)

Trains a model to recognize human emotions from images. Covers key steps like data loading, feature extraction, model architecture, training, and evaluation metrics.

### 3. Image Detection (`Image_Detection.ipynb`)

Performs object detection in images. Includes dataset handling, model setup, inference, visualization of detection results, and evaluation.

### 4. Predicting Diabetes (`Predicting_Diabetes.ipynb`)

Builds a predictive model for diabetes outcomes using a tabular dataset. Typically includes exploratory data analysis (EDA), feature engineering, model training, validation, and performance reporting.

## Setup and Requirements

1. **Clone the repository**

   ```bash
   git clone https://github.com/danielpul101/ML-Projects.git
   cd ML-Projects
   ```

2. **Create a virtual environment (recommended)**

   ```bash
   python3 -m venv venv
   source venv/bin/activate   # macOS/Linux
   venv\Scripts\activate      # Windows
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

   *If there is no ****`requirements.txt`****, you can install common ML libraries like:*

   ```bash
   pip install numpy pandas scikit-learn matplotlib tensorflow keras torchvision notebook
   ```

4. **Launch Jupyter Notebook**

   ```bash
   jupyter notebook
   ```

   Then open any of the `.ipynb` files to explore.

## Usage Overview

For each notebook:

* **Load** the dataset (e.g., MNIST, image classifier, tabular data).
* **Preprocess** data (scaling, encoding, cleaning).
* **Define** and compile the model.
* **Train** the model, tracking accuracy/loss.
* **Evaluate** model performance with metrics and visualizations.
* (Optional) **Save** and **load** trained models for inference.

## Repository Structure

```
ML-Projects/
│
├── Digit_Classification.ipynb
├── Emotion-Detector.ipynb
├── Image_Detection.ipynb
├── Predicting_Diabetes.ipynb
└── README.md
```

## Contributing

Contributions are welcome. To contribute:

1. Fork this repository.
2. Create a new branch: `git checkout -b feature/YourIdea`.
3. Make your changes (e.g., improve a notebook, add a new project).
4. Commit your changes: `git commit -m "Add new project or improvement"`.
5. Push to the branch and open a pull request.

##
