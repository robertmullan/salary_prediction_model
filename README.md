# 3300 - Salary Prediction Model

![Python badge](https://img.shields.io/static/v1?message=python&logo=python&labelColor=5c5c5c&color=3776AB&logoColor=white&label=%20&style=for-the-badge)

This application uses an interactive Python notebook to import [2022 Kaggle Machine Learning & Data Science Survey](https://www.kaggle.com/c/kaggle-survey-2022/data) data, clean the data, build a random forest regression model, test the model, and export the model to a file.

I am not a machine learning person. There were some liberties taken with the data for the purposes of teaching. For example, the salaries were randomly generated between the categorical low and high values for each row. The model has not been tuned.

The idea for this project came from [Predicting Year of Marriage - End to End Machine Learning Deployment with FLASK and AWS -PART 1](https://www.youtube.com/watch?v=sm5xeKal72I). I adapted to a data science salary prediction model and Microsoft Azure for purposes of teaching.

### To Run This Application

---

1. Clone this repository to local computer

2. Create a new virtual environment

   - Windows: `python -m venv ./venv`
   - Mac: `python3 -m venv ./venv`

3. Activate the new virtual environment

   - Windows: `.\venv\Scripts\activate`
   - Mac: `source ./venv/bin/activate`

4. Install the dependencies `pip install -r requirements.txt`

5. If necessary, add the Visual Studio Code extension for Jupiter Notebooks.

6. Run the interactive Python notebook file (salary_prediction.ipynb)
