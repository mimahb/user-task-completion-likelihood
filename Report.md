 # Introduction

This project aims to predict whether a user will complete an online course based on their engagement patterns. A Decision Tree Classifier was used to build the model, utilizing features such as time spent on the course, number of videos watched, quizzes taken, and completion rate.

## Dataset Overview
Target Variable: CourseCompletion (1 = Completed, 0 = Not Completed)

### Features Used:
#### TimeSpentOnCourse
#### NumberOfVideosWatched
#### NumberOfQuizzesTaken
#### QuizScores
#### CompletionRate
#### DeviceType

## Data Preprocessing
#### Checked for missing values and dropped any if necessary.
#### Scaled numerical features using StandardScaler.
#### Split the dataset into 80% training and 20% testing.

## Model Selection & Training
##### Chose Decision Tree Classifier as the model.
##### Trained the model on the processed dataset.

## Evaluation Metrics & Results
The model was evaluated using accuracy, precision, and recall:
##### Accuracy: Measures overall correctness.
##### Precision: Indicates how many predicted completions were actually completed.
##### Recall: Measures how many actual completions were correctly identified.

#### Accuracy: 0.81

#### Precision: 0.80

#### Recall: 0.72

## Key Insights & Observations

#### Feature Importance: Features like CompletionRate and QuizScores had the strongest correlation with course completion.

#### Data Imbalance: Slight imbalance between completed and non-completed cases, but handled effectively.

### Potential Improvements:
##### Experiment with other models like Random Forest or XGBoost for better accuracy.
##### Tune hyperparameters to optimize performance.
##### Collect more diverse data to enhance model robustness.

## Conclusion

This project successfully built a predictive model for course completion using engagement data. The results show promising performance, with potential for further improvements through feature engineering and model tuning.
