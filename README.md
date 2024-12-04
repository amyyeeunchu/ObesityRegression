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

***Objective:***
We want to implement a few models (regression, classification (SVM), GMM (probabilistic), Random Forrest, Decision Tree) based on different approaches and evaluate their performance (pros and cons, where the models struggle, how much time it takes, etc.)

***How can we put some Maths into this?***
1) We need to check if the data is linearly separable (there are a lot of methods for that, but we use the most retarded and Maths-related one). So we check the **rank of the matrix** and if it's smaller than k (where k is the number of features), then we are screwed and the data is slightly shitty since some features are redundant. (Please forget about linear separation of data, I was delusional)
2) **Regularization**
To make models behave themselves, we would apply the regularization, using sklearn Ridge regression (and its classification alternative)
3) **Hyperparameters tunning**
If we are considering the Random Forest/Decision Tree, we can use the Grid search to find the best hyperparameters (if my dear colleagues let me use Random Forest model).
4) **PCA**
To get rid of not important features and reduce the dimensionality of the data.
5) **K-fold cross-validation**
6) **Gradient decent**
To calculate the derivatives and compute the loss and update the weights for regression.
No one will take the model seriously if we use the training set as a validation one.
8) **Responsibilities**
We will have to implement the EM iteratively, untill the model is well adjusted to the dataset. Will have to update mean, weights and covariance matrix all the time.
9) **Kernel trick for SVM** or just Lagrangian in best case
Kernel shit and linearly inseparable data suck a lot, so we would want to avoid that. But in case we do a SVM for classification, we have to implement Lagrangian as a solution for constrined optimization problem.
10) **Actually, can be a lot more**
Only Allah knows how much more shit is waiting for us in the nearest future. Stay strong everyone!

***How to interpret results?***
1) Should check the feature importance for all the models, perform the PCA for some of them according to the results and see if some of them should be removed to improve the performance.
2) Should display the F1 analysis and compare their accuracy.
3) Compare decision boundaries and time complexity
4) If some models are so fucking bad, then report them immidiatelly.
5) Express gratitude towards Allah for giving us willpower and strength to handle this shit.

***Conclusion:***
Is yet to come


