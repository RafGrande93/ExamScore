# ExamScore

Exam Score Prediction
=================================

This project predicts student exam scores using a neural network built with TensorFlow/Keras.

Contents
--------
- Jupyter notebook with data exploration, preprocessing, model training, and evaluation.
- Dataset: `Exam_Score_Prediction.csv` (place in a `data/` folder or update path).
- `requirements.txt` for dependencies.

How to Run
----------
1. Install packages:
   pip install -r requirements.txt

2. Launch Jupyter:
   jupyter notebook

3. Open the notebook and run all cells.

Metrics
-------
The model is a fully connected neural network implemented with Keras for a regression task. It predicts a continuous exam score.

Reported evaluation metrics on the test set include:
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² score (coefficient of determination, R^2=0.72) 

The R^2=0.73.

