Rock vs Mine Prediction

This project uses Logistic Regression to classify sonar signals as either a rock or a mine (metal cylinder). The dataset used is the Sonar Dataset (UCI Machine Learning Repository).

📊 Dataset

Each record has 60 numerical features representing sonar signal returns.

Label column (61st):

R → Rock

M → Mine

🔧 Dependencies

Install the required libraries before running the script:
pip install numpy pandas scikit-learn

▶️ How to Run

1- Clone this repository:
git clone https://github.com/sohapervez/rock-vs-mine-prediction.git
cd rock-vs-mine-prediction

2- Make sure the dataset ([Copy of sonar data.csv](https://drive.google.com/file/d/1pQxtljlNVh0DHYg-Ye7dtpDTlFceHVfa/view)) is placed in the same directory or update the path inside the script.

3- Run the script:
python rock_vs_mine_prediction.py

📈 Model

Algorithm: Logistic Regression

Evaluation Metric: Accuracy Score

The script trains the model, evaluates it, and outputs the accuracy.

🚀 Future Improvements

Experiment with different ML algorithms (Random Forest, SVM, Neural Networks).

Apply hyperparameter tuning for better performance.

Deploy using Flask or Streamlit for an interactive web app.
