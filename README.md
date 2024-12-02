# ObesityRegression MATH432 Project
WHAT THIS FILE SHOULD LOOK LIKE ***CHAT GPT'S POV***
README File on GitHub

Yes, you should include a README file on GitHub. It helps organize your project, makes it more presentable, and provides essential context for anyone reviewing your work. Here’s what to include:
	•	Project Title and Description: Briefly explain the project objective (e.g., obesity prediction and using ridge regression).
	•	Team Members: List contributors.
	•	Objective: Clearly outline your goals, such as applying ridge regression to analyze obesity-related factors.
	•	Dataset Information: Briefly describe the dataset (source, features, output).
	•	Methods: Highlight theoretical concepts applied (ridge regression, PCA, etc.) and implementation methods (e.g., sklearn).
	•	Milestones: Document major steps, such as data preprocessing, ridge regression implementation, results evaluation, etc.
	•	Usage Instructions: Explain how to run the code.
	•	Results: Summarize findings and provide visuals if available (accuracy plots, etc.).
	•	Future Work: Mention any limitations and potential improvements.

***Project title:*** "Comparation of different approaches for obesity classification problem"
Since the problem is somehow intuitively understandable and doesn't require a lot of brain power, in case not to look retarded, we need to make it look fancy by adding some spice: solving the problem implementing different models and then comparing their performance.

***How can we put some Maths into this?***
1) We need to check if the data is linearly separable (there are a lot of methods for that, but we use the most retarded and Maths-related one). So we check the **rank of the matrix** and if it's smaller than k+1, than we are screwed and the data can not be linearly separated that well.
2) **Regularization**
To make models behave themselves, we would apply the regularization, using sklearn Ridge regression (and its classification alternative)
3) **Hyperparameters tunning**
If we are considering the Random forest, we can use the Grid search to find the best hyperparameters(if my dear colleagues let me use Random Forest model).


