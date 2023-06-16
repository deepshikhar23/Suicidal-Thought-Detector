# Suicidal-Thought-Detector

This repository contains a Suicidal Thought Detector model trained using the Logistic Regression algorithm. The model is designed to classify text data and determine if it contains suicidal thoughts or not.

## Overview

The Suicidal Thought Detector is built using natural language processing techniques and machine learning algorithms. It takes text data as input and predicts whether the text expresses suicidal thoughts or not. The model is trained on a labeled dataset and achieves high accuracy in identifying suicidal content.

## Files

The repository includes the following files:

- `jupyter notebook.ipynb`: Jupyter Notebook file that contains the code for data preprocessing, model training, and evaluation. It provides a step-by-step guide to reproduce the model and analyze the results.

- `Suicide_Detection.csv`: Compressed dataset file containing text data labeled with suicidal thoughts. Please note that the actual data has been removed for size limit reasons. You can use your own labeled dataset or explore public datasets related to suicide detection for training and evaluation.

- `logistic_regression_model.pkl`: Pickle file that contains the trained logistic regression model. This model can be loaded and used to make predictions on new text data. Refer to the Jupyter Notebook for an example of how to load and use this model.

- `tfidf_vectorizer.pkl`: Pickle file that contains the fitted TF-IDF vectorizer. This vectorizer is used to transform text data into numerical features before feeding them into the model. It is necessary to preprocess new text data in the same way as the training data to ensure consistency and accurate predictions. Refer to the Jupyter Notebook for an example of how to load and use this vectorizer.

## Usage

To use the Suicidal Thought Detector, follow these steps:

1. Clone the repository to your local machine.

2. Open and run the `jupyter_notebook.ipynb` file in Jupyter Notebook or JupyterLab. This notebook contains the code for data preprocessing, model training, and evaluation. It provides detailed explanations and code snippets to guide you through each step of the process.

3. If you want to make predictions on new text data using the trained model, you can load the `logistic_regression_model.pkl` file and the `tfidf_vectorizer.pkl` file in your Python script or notebook. Refer to the Jupyter Notebook for an example of how to load and use these files.

4. Feel free to explore and experiment with the code in the Jupyter Notebook to customize the model, try different algorithms, or incorporate additional features for improved performance.

## Disclaimer

Please note that the dataset provided in this repository is compressed, and the actual text data has been removed to ensure size limit considerations. The purpose of sharing this repository is to demonstrate the implementation of the Suicidal Thought Detector model rather than providing the actual data. It is important to handle sensitive content with care and adhere to ethical guidelines when working with suicide-related data.

## Contributing

Contributions to this project are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code in this repository for personal and commercial purposes.

## Contact

For any inquiries or questions, please contact Deepshikhar Saxena at deepshikhar2305@gmail.com

