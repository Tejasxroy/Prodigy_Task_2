**🚢 Titanic Dataset Analysis**

**🔍 Project Overview**

  This project focuses on analyzing the Titanic dataset to understand survival patterns based on different factors such as gender, age, and class. The analysis includes data cleaning, handling missing values, and 
  performing exploratory data analysis (EDA) through various visualizations.

**🛠️ Technologies Used**

  Python 🐍

  Pandas for data manipulation

  NumPy for numerical computations

  Matplotlib & Seaborn for data visualization

  Scikit-Learn for preprocessing

📂 Project Structure

📁 Titanic-EDA-Analysi
│── 📁 Task2.ipynb   # Jupyter Notebook containing the analysis
│── 📂 data/         # Folder containing dataset(s)
│── 📂 visuals/      # Saved plots and visualizations
│── 📄 README.md     # Project documentation (this file)

**🏗️ Data Cleaning**

  Checked for missing values and filled them using appropriate techniques:

  Cabin column was dropped due to excessive missing values.

  Age and Fare were filled using the median.
  
  Embarked was encoded using LabelEncoder.
  
  Checked for and removed duplicate entries.
  
  Ensured consistent data formatting.

**📈 Exploratory Data Analysis (EDA)**

  Survival Distribution (Bar Chart)
  
  Gender-Based Survival Rates (Bar Chart)
  
  Survival Rates by Passenger Class (Bar Chart)
  
  Age Distribution (Histogram + KDE Plot)
  
  Fare Distribution (Histogram)
  
  Correlations between features

**📊 Data Visualization**

  This project contains several visualizations to help understand survival patterns:
  
  A Bar Chart for the total survival count.
  
  A Pie Chart for gender distribution.
  
  A Histogram to show the distribution of passengers by age.
  
  A Bar Chart for class-wise survival rate.

**📌 Future Scope**

  Feature engineering for predictive modeling
  
  Building a Machine Learning model to predict survival
  
  Creating an interactive dashboard for analysis

**📜 License**

  This project is open-source under the MIT License.

