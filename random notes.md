The dataset includes people only from18 to 54 years old, we should include it as a limitation of the dataset

## 2nd meeting: 12/11

ChatGPT question and response:
We have a machine learning project. Starting from a data set containing some input features we should output the obesity level ofa person. We downloaded the datasaet and cleaned it successfully. Now We are in a meeting and we do not know how to start. Can you give us instructions or guidelines to do. We ara 4 people working on it. How should we divide our work for the next milestone. We thought, depending on the feature of implementing Lasso regression, softmax. We will also implement a validation set and PCA
ChatGPT said:

It's great that you've got your dataset cleaned and have a clear goal to predict obesity levels! Here’s a step-by-step guide to help you get organized and assign tasks among the team members.

1. Define the Project Steps and Divide Tasks
   To achieve the next milestone, let’s break down the tasks into manageable steps and assign roles based on each person's expertise and interest. Here’s a potential plan:

###Nacho:
Step 1: Exploratory Data Analysis (EDA)
Goal: Understand the dataset’s structure, examine feature distributions, and identify relationships with the target variable (obesity level).

Tasks:

Visualize distributions of features (like age, weight, activity levels) and their correlation with obesity.
Identify potential outliers and features that might need further preprocessing.
Generate statistical summaries for each feature (mean, median, standard deviation, etc.).
Suggested Roles:

Person A: Perform the initial visualizations (histograms, scatter plots, box plots).
Person B: Generate correlation heatmaps and summary statistics.
Outcome: Documented findings and initial hypotheses about which features may be most predictive of obesity.

### Sofiia

Step 2: Feature Engineering and Selection (Including PCA)
Goal: Prepare the dataset for modeling by selecting the most relevant features and reducing dimensionality if needed.

Tasks:

Perform initial feature selection based on EDA insights.
Implement Principal Component Analysis (PCA) to reduce feature dimensionality, if applicable.
Test different numbers of components for PCA and evaluate the explained variance.
Suggested Roles:

Person C: Implement PCA and document the variance explained by each component.
Person D: Assess and select features based on the EDA insights and PCA results.
Outcome: A cleaned, engineered set of features ready for modeling, and a summary of PCA results (such as the number of components to keep).

### Momo hako Amy

Step 3: Implement Baseline Models and Model Selection
Goal: Train baseline models (e.g., linear regression, logistic regression, softmax regression) to establish a performance benchmark.

Tasks:

Implement Lasso Regression for feature selection and regularization.
Set up and test Softmax Regression if your output is multiclass (i.e., different obesity levels).
Split the data into training, validation, and test sets.
Suggested Roles:

Person A & Person B: Set up Lasso Regression (testing different regularization parameters) and assess performance.
Person C & Person D: Implement Softmax Regression and optimize the hyperparameters.
Outcome: A trained baseline model for each regression type, along with documented performance (accuracy, loss) for each approach.

### After (would be good if we do it before the final)

Step 4: Model Evaluation and Validation
Goal: Evaluate model performance, tune hyperparameters, and perform cross-validation.

Tasks:

Set up k-fold cross-validation to assess model stability.
Create a validation set to tune hyperparameters and prevent overfitting.
Document model performance on validation and test sets, comparing metrics like accuracy, precision, recall, or F1-score, depending on your needs.
Suggested Roles:

Everyone (if possible): Share cross-validation responsibilities by each taking a subset of the cross-validation analysis.
Person D: Oversee hyperparameter tuning and validation set performance tracking.
Outcome: Well-documented model metrics, validation set performance, and insights on which model/hyperparameters work best.

### After final

Step 5: Final Report and Next Steps
Goal: Compile the findings, prepare for the next meeting, and outline any remaining tasks or challenges.

Tasks:

Prepare a summary of each team member’s work and findings.
List open questions or challenges encountered (e.g., if certain features are weak predictors).
Outline plans for the next meeting.
Suggested Roles:

Everyone: Contribute a summary of their work.
Person A (or whoever is comfortable): Draft the final report or presentation with everyone’s input. 2. Other General Tips
Set a Timeline: Assign deadlines for each step, allowing buffer time to handle unexpected issues.
Communication Tools: Consider a shared workspace (e.g., Google Drive or Notion) for documentation, and set up a Slack/Discord channel or regular check-ins to keep everyone on the same page.
Git Version Control: If working in code, use Git for version control, ensuring each person can commit changes without overwriting others’ work.
By the end of these steps, you’ll have a good foundation in data understanding, feature selection, baseline modeling, and validation techniques, which will allow you to proceed confidently toward more advanced modeling or tuning if needed.
