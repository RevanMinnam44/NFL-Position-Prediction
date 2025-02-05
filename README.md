# NFL-Position-Prediction
Logistic Regression from Scratch in Python

Project Overview:
This project demonstrates how to implement Logistic Regression from scratch at three different levels of complexity. The goal is to progressively remove dependencies while maintaining model performance.


1️⃣ Full Package Implementation (Easiest, Uses Libraries)

🔹 Packages Used: pandas, numpy, sklearn, random, math


	•	Implements Logistic Regression using scikit-learn (sklearn).
 
	•	Uses pandas for data handling and numpy for numerical computations.
 
	•	Includes feature scaling, train-test split, and model evaluation.
 
	•	Best accuracy achieved: 94%


2️⃣ Partially Restricted Version (No numpy or sklearn, Only pandas, math, random)

🔹 Packages Used: pandas, math, random


	•	Implements Logistic Regression manually without sklearn.
 
	•	Uses pandas for data handling and math for numerical operations.
 
	•	Feature scaling, gradient descent, and stochastic updates done manually.
 
	•	Best accuracy achieved: ~94%

3️⃣ Pure Python Implementation (No External Libraries)

🔹 Packages Used: None! (Only built-in open() for file reading)


	•	Fully manual Logistic Regression model.
 
	•	Reads CSV files without pandas.
 
	•	Manually implements feature scaling (Robust Scaling & Z-Score Scaling).
 
	•	Implements Gradient Descent (SGD) with Adaptive Learning Rate.
 
	•	Uses Fisher-Yates shuffle instead of random.shuffle().

	•	Best accuracy achieved: ~90%
 
