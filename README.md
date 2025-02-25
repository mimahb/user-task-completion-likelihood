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
├── 📄 main.py             # Main script for data processing, training, and evaluation
├── 📄 requirements.txt    # Required dependencies
├── 📄 README.md           # Documentation
├── 📄 report.pdf          # Project summary report
└── 📂 data                # Dataset

## Installation & Set Up 
### Clone the repository
git clone <your-github-repo-link>
cd online-course-prediction
### Install Dependencies 
pip install -r requirements.txt
### Run the project
python main.py

## Model & Performance 
Model Used: Decision Tree Classifier
Evaluation Metrics: Accuracy, Precision, Recall

## Results 
Accuracy: 81%
Precision: 80%
Recall: 72%
