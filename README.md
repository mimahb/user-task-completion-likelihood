# user-task-completion-likelihood
This project builds a machine learning model to predict whether a user will complete an online course based on engagement patterns. It uses a classification approach with a Decision Tree model.

## Dataset
The dataset contains user activity features such as:
TimeSpentOnCourse
NumberOfVideosWatched
NumberOfQuizzesTaken
CompletionRate
DeviceType
CourseCompletion (Target Variable: 1 = Completed, 0 = Not Completed)

## Project Structure
📂 online-course-prediction
     📄 main.py             
     📄 README.md           
     📄 report.pdf          
📂 data              

## Installation & Set Up 
### Clone the repository
git clone https://github.com/mimahb/user-task-completion-likelihood.git
### Install Dependencies 
pip install -r requirements.txt
### Run the notebook
user-task-completion-likelihood.ipynb

## Model & Performance 
Model Used: Decision Tree Classifier
Evaluation Metrics: Accuracy, Precision, Recall

## Results 
Accuracy: 81%
Precision: 80%
Recall: 72%
