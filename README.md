# 📊 Glassdoor Job Analysis & Salary Prediction  

## 🔍 Project Overview  
This project analyzes **Glassdoor job listings** to extract **key insights about salaries, company ratings, and hiring trends**. Using **data science, machine learning, and NLP**, we explore factors that impact salary distribution and job market trends.  

## 🚀 Features & Goals  
- **Data Wrangling:** Cleaning and preprocessing job data.  
- **Exploratory Data Analysis (EDA):** Visualizing **salary trends, ratings, and job locations**.  
- **Hypothesis Testing:** Validating assumptions (e.g., "Do higher-rated companies offer better salaries?").  
- **Machine Learning:** Predicting salaries based on job attributes.  

## 📂 Dataset  
- **Source:** Glassdoor job listings.  
- **Size:** 956 job postings.  
- **Key Features:**  
  - `Job Title`, `Company Name`, `Rating`, `Location`  
  - `Min Salary`, `Max Salary`, `Avg Salary`  
  - `Industry`, `Sector`, `Revenue`, `Company Age`  

## 📊 Data Analysis & Visualization  
- **Correlation Heatmap** → Identifies relationships between salary, company rating, and industry.  
- **Salary Distribution** → Shows variations across job roles.  
- **Industry-wise Salary Trends** → Highlights high-paying sectors.  
- **Top Hiring Cities** → Reveals job market hotspots.  

## 🧪 Hypothesis Testing  
- **Do high-rated companies offer better salaries?** *(t-test applied)*  
- **Does company age affect salary range?** *(scatter plot analysis)*  

## 🛠️ Tech Stack  
- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Seaborn, Matplotlib, SciPy, Sklearn  

## 📌 How to Use This Project?  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/glassdoor-job-analysis.git
   cd glassdoor-job-analysis
2. Install Dependencies:
   ```bash
   pip install -r requirements.txt

  - if using colab:
     ```bash
     !pip install pandas numpy seaborn matplotlib scipy scikit-learn
3. Load the Dataset:
   ```bash
   from google.colab import drive
   drive.mount('/content/drive')
4. Run the Notebook:
   ```bash
   jupyter notebook
5. Perform Data Wrangling
      - Handle missing values and duplicates.
      - Extract salary information.
      - Split location into City and State.
      - Convert founded year to company age.
6. Explore Data visualization

     - Use Seaborn & Matplotlib to generate insights:
     - Salary Distribution Histogram → Understand salary spread.
     - Salary vs. Rating Boxplot → Check if higher-rated companies pay more.
     - Industry-wise Salary Trends → Identify top-paying sectors.
     - Top Hiring Cities Bar Chart → Find job market hotspots.
     - Correlation Heatmap → Analyze relationships between features.




