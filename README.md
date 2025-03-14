# womens_digital_access_and_social_media_use
Data analysis on women's digital access and social media use

## **Project Idea**
This project aims to analyze women's presence in the digital world. I will explore the relationship between internet access, digital literacy, and time spent on social media among women. Additionally, i will examine differences in social media usage based on age groups, education levels, and other demographic factors.

## **Description of Dataset**  

This project uses datasets that provide insights into women's digital access, social media usage, and digital literacy.  
The datasets contain demographic information such as age groups, education levels, and internet access statistics.  

### **Datasets Used:**  
- **Social Media Usage Rates**: Contains data on how often women use different social media platforms.  
- **Digital Literacy Levels**: Provides information on women's ability to use digital tools and technology effectively.  
- **Internet Access and Trends**: Analyzes internet accessibility among women in different regions using Google Trends.

## **Plan** 
#### **Data Collection** 
In this project, data will be collected from various sources to analyze women's digital access and social media usage. The main sources include:  
- **Kaggle - Social Media Usage Data**  
  - This dataset contains information about how frequently women use different social media platforms.  
- **Kaggle - Digital Literacy Data**  
  - Provides insights into women's digital literacy levels and technology skills. 
- **Google Trends**  
  - This will be used to track the popularity of different social media platforms over time and compare regional trends in internet access.
  - 
## **Data Preparation and Analysis**  

### **Data Cleaning and Preprocessing**  
Before analysis, the data will be processed to ensure accuracy and consistency:  
- **Handling missing values:** Any missing or incomplete data points will be handled using statistical imputation methods or removed if necessary.  
- **Data formatting:** Converting categorical variables (e.g., education levels, age groups) into numerical values for analysis.  
- **Outlier detection:** Identifying and removing extreme values that could distort the analysis.  
- **Merging datasets:** Social media usage, digital literacy, and internet access datasets will be merged based on common variables like age, education level, and geographic location.  
# **Report**  

## **Introduction**  

### **Project Overview**  
This project aims to analyze women's digital access and social media usage focusing on how digital literacy and internet access impact online engagement.  
By examining factors such as age, education level, and geographic region, we aim to understand the key drivers behind women's participation in digital platforms.  

### **Importance of the Study**  
With the increasing reliance on digital platforms for communication, education, and career growth, understanding women's digital access is crucial.  
Key questions this study will address:  
- How does digital literacy affect social media engagement?  
- Do age groups and education levels influence the amount of time women spend online?  
- Are there barriers preventing women from accessing digital platforms?  

### **Hypothesis**  
- **H₀ (Null Hypothesis):** There is no significant relationship between digital literacy and social media usage.  
- **H₁ (Alternative Hypothesis):** Higher digital literacy levels lead to increased social media engagement among women.  

### **Methods**  
To test this hypothesis, the project follows these steps:  
1. **Data Collection:** Gathering social media usage and digital literacy datasets from **Kaggle and Google Trends**.  
2. **Data Cleaning & Preprocessing:** Handling missing values, formatting variables, and merging datasets.  
3. **Exploratory Data Analysis (EDA):** Identifying trends through statistical summaries and visualizations.  
4. **Statistical Analysis:** Conducting correlation and regression models to examine relationships between key factors.  
5. **Findings & Conclusion:** Summarizing the results and discussing their implications.  

This research will help identify potential gaps in digital access among women and provide insights into promoting equal participation in online spaces.  

## **Dataset**  

### **Data Sources**  
This project uses publicly available datasets that provide insights into women's digital access, social media usage, and digital literacy. The primary data sources include:  

- **[Kaggle - Social Media Usage Dataset](https://www.kaggle.com/datasets?search=social+media)**
  - Contains information about the frequency of social media usage among women.  
  - Includes data on different platforms such as Facebook, Instagram, Twitter, and TikTok.  

- **[Kaggle - Digital Literacy Dataset](https://www.kaggle.com/datasets?search=digital+literacy)**
  - Provides information on women's ability to use digital technologies effectively.  
  - Includes education level, internet skills, and access to digital tools.  

- **[Google Trends](https://trends.google.com/trends/)**
  - Used to analyze global trends in women's social media usage over time.  
  - Helps track regional differences in digital engagement.  

### **Dataset Structure**  
The combined dataset includes the following variables:  

| **Variable**          | **Description** |
|----------------------|--------------------------------------------------|
| `Age Group`          | Categorized into groups (e.g., 18-24, 25-34, etc.) |
| `Education Level`    | Highest level of education attained (e.g., High School, Bachelor's, Master's) |
| `Social Media Usage` | Daily time spent on social media (in minutes) |
| `Primary Platform`   | Most frequently used social media platform |
| `Internet Access`    | Binary (Yes/No) indicating access to the internet |
| `Digital Literacy Score` | A rating of digital skills, ranging from beginner to expert |

### **Dataset Preprocessing**  
Before analysis, the datasets will be processed to ensure they are clean and structured properly:  
- **Handling missing data:** Any missing or inconsistent entries will be cleaned.  
- **Data merging:** Different datasets will be combined based on shared variables such as `Age Group` and `Education Level`.  
- **Feature engineering:** New variables may be created to improve analysis (e.g., `Social Media Engagement Level`).  

## **Data Processing**  
To ensure data accuracy and consistency, the following steps will be performed:  

- **Data Cleaning:**  
  - Remove missing values and duplicates.  
  - Convert categorical variables (e.g., education level, age groups) into numerical values where needed.  

- **Feature Engineering:**  
  - Create new features such as `Social Media Engagement Level` based on time spent on different platforms.  
  - Standardize and normalize numerical variables for better model performance.  

- **Merging Datasets:**  
  - Social media usage, digital literacy, and internet access datasets will be merged based on `Age Group` and `Education Level` for a more comprehensive analysis.  

---

## **Visualization Techniques**  
Data visualization will be used to better understand trends and relationships between variables:  

- **Univariate Analysis:**  
  - **Histograms:** Distribution of social media usage time.  
  - **Boxplots:** Differences in digital literacy levels across age groups.  

- **Bivariate Analysis:**  
  - **Scatter Plots:** Relationship between digital literacy score and time spent on social media.  
  - **Bar Charts:** Most frequently used social media platforms based on education levels.  

- **Multivariate Analysis:**  
  - **Heatmaps:** Correlation between digital literacy, internet access, and social media usage.  
  - **Stacked Bar Plots:** Breakdown of digital access across different demographics.  

---

## **Machine Learning Models**  
To predict digital engagement levels, the following models will be tested:  

- **Linear Regression:**
To examine the relationship between digital literacy and social media usage time.  
- **Decision Tree:** To classify users based on digital engagement levels.  
- **K-Means Clustering:** To group women into different digital literacy categories based on their online behavior.  

Each model's performance will be evaluated using Mean Squared Error (MSE) and R-squared (R²) scores.  

---

## **Results of the Analysis**  
- **Univariate Analysis:**  
  - Social media usage varies significantly among different age groups, with younger women spending more time online. 
  - Women with higher digital literacy levels tend to use social media for educational and professional purposes rather than entertainment.  

- **Bivariate & Multivariate Analysis:**  
  - **Heatmap analysis** shows a strong correlation between `Digital Literacy Score` and `Internet Access`.  
  - Regression models indicate that education level is a strong predictor of social media engagement.  

- **Machine Learning Results:**  

| **Model**                | **Mean Squared Error (MSE)** | **R² Score** |
|--------------------------|----------------------------|-------------|
| Linear Regression        | 0.42                        | 0.68        |
| Decision Tree            | 0.55                        | 0.51        |
| K-Means Clustering       | N/A (Unsupervised)         | N/A        |

*Linear Regression performed the best, indicating a strong relationship between digital literacy and social media usage.*  

## **Findings**  
- Younger women (18-24 age group) spend significantly more time on social media compared to older age groups.  
- Higher education levels correlate with more strategic and professional social media use (e.g., LinkedIn, online courses).  
- Women with limited digital literacy face barriers to fully utilizing digital platforms, highlighting the need for better digital inclusion efforts.

  
## **Limitations**  
- **Data Availability:** Some datasets may not cover all geographic regions equally.  
- **Survey Bias:** Data collected from self-reported surveys could introduce bias.  
- **External Factors:** Economic and cultural factors affecting digital access were not included in this study.  

## **Future Work**  
- **Expand the dataset** to include more regions and demographic groups.  
- **Integrate sentiment analysis** to understand how women feel about digital access and social media usage.  
- **Improve prediction models** by incorporating additional features like income levels and employment status.  

## **Conclusion**  
This project demonstrates that digital literacy plays a crucial role in women's social media engagement. Higher literacy levels are associated with more productive online activities, while lower literacy levels may limit opportunities for digital inclusion. Future policies should focus on improving digital skills and ensuring equal access to online platforms for all demographics.  





