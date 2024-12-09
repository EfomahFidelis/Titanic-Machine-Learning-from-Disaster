# Titanic-Machine-Learning-from-Disaster
To build a predictive model that answers the question: “what sorts of people were more likely to survive?” the sinking of the Titanic,the most infamous shipwrecks in history.
<br>
<br>
<strong>Introduction:</strong><br>
This project employs machine learning techniques to predict the survival likelihood of Titanic passengers based on demographic, social, and economic features. Using a dataset containing passenger information such as age, gender, ticket class, and more, the project explores relationships between features and survival rates, applies feature engineering, and builds a Random Forest Classifier to produce predictions. The aim is to identify key survival factors while refining data science and machine learning workflows.

<strong>Methodology:</strong>
<ul>
  <li><strong>Exploratory Data Analysis:</strong> Visualized survival distributions and key variables such as gender and age to understand patterns.</li>
  <li><strong>Feature Engineering:</strong>
    <ul>
      <li>Derived new features like family size, isolation status, and cabin presence.</li>
      <li>Extracted titles from passenger names to capture social standing.</li>
      <li>Imputed missing data for age, fare, and embarked location.</li>
    </ul>
  </li>
  <li><strong>Data Preprocessing:</strong> One-hot encoded categorical features and ensured feature alignment between training and test datasets.</li>
  <li><strong>Model Training:</strong> Utilized a Random Forest Classifier with hyperparameter tuning to predict survival outcomes.</li>
  <li><strong>Evaluation:</strong> Analyzed feature importance to identify significant predictors of survival.</li>
</ul>

<strong>Technology:</strong>
<ul>
  <li><strong>Programming Languages:</strong> Python</li>
  <li><strong>Libraries:</strong> Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib</li>
</ul>

<strong>Results:</strong>
<ul>
  <li>Trained a Random Forest Classifier that effectively predicts survival with key features such as gender, fare, and family-related variables.</li>
  <li>Visualizations highlighted the importance of variables like social class (<strong>Class</strong>) and gender in predicting survival.</li>
  <li>Demonstrated practical experience in feature engineering, data preprocessing, and implementing machine learning workflows.</li>
</ul>
