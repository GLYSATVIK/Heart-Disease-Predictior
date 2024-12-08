
# Heart Disease Predictor

![Python](https://img.shields.io/badge/Python-3.8%2B-blue) ![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Enabled-brightgreen) ![Status](https://img.shields.io/badge/Status-Complete-success)

## Overview

The **Heart Disease Predictor** is a machine learning project that uses patient health data to predict the likelihood of heart disease. By leveraging predictive analytics and machine learning techniques, this tool aims to assist healthcare professionals in early diagnosis and proactive treatment planning.

## Features

- **Data Exploration**: Insights into patient health metrics.
- **Feature Engineering**: Preprocessing steps to handle missing data, normalization, and feature selection.
- **Model Training**: Implementation of machine learning algorithms to build a predictive model.
- **Evaluation Metrics**: Performance analysis using metrics such as accuracy, precision, recall, and F1-score.

## Dataset

The project uses a dataset containing patient health data such as:

- Age
- Blood Pressure
- Cholesterol Levels
- Blood Sugar Levels
- Maximum Heart Rate
- Resting ECG Results

> **Note**: The dataset may have been sourced from publicly available repositories like [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease).

## Requirements

To run the project, install the following dependencies:

- Python 3.8+
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

Install the requirements using:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/GLYSATVIK/Heart-Disease-Predictor.git
   cd heart-disease-predictor
   ```

2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Heart\ Disease\ Predictor.ipynb
   ```

3. Follow the steps in the notebook to:
   - Load and preprocess the data.
   - Train machine learning models.
   - Evaluate the results.

4. Customize the code or experiment with new datasets and models.

## Results

The model achieved the following performance:

- **Accuracy**: 85%
- **Precision**: 87%
- **Recall**: 84%
- **F1-Score**: 85%

![Confusion Matrix](images/confusion_matrix.png)

## Project Structure

```
├── Heart Disease Predictor.ipynb  # Main notebook
├── data/                          # Dataset (not included for privacy reasons)
├── images/                        # Visualizations and output images
├── requirements.txt               # Dependencies
└── README.md                      # Project documentation
```

## Contribution

Contributions are welcome! If you have ideas for improving the model or adding new features:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push to the branch:
   ```bash
   git push origin feature-name
   ```
4. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgments

- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/)
- The creators of open-source tools and libraries used in this project.

