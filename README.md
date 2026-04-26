# 🌍 Global Terrorism Analysis

## 📌 Project Overview

This project analyzes the Global Terrorism dataset to study patterns in terrorist incidents around the world. The dataset contains event details such as year, country, region, attack type, target type, weapon type, casualties, and other related attributes.

The goal of this project is to clean the data, explore important trends, and create meaningful visualizations that help understand terrorism patterns over time and across regions.

---

## 📌 PROJECT SUMMARY

This project focuses on performing Exploratory Data Analysis (EDA) on the United Nations Global Terrorism Analysis (UNGTA) dataset, which contains detailed information on terrorist incidents worldwide from 1970 to 2017. With over 180,000 recorded events, this dataset provides a rich source of structured data for analyzing patterns, trends, and characteristics of global terrorism.

The primary objective of this project is to uncover meaningful insights from the dataset using data analysis and visualization techniques. By leveraging libraries such as Pandas, NumPy, Matplotlib, and Seaborn, the analysis aims to explore temporal, geographical, and operational patterns in terrorist activities.

The initial phase of the project involves data preprocessing and cleaning. This includes handling missing values, correcting inconsistent entries, and selecting relevant features for analysis. Given the large size and complexity of the dataset, preprocessing plays a crucial role in ensuring accurate and efficient analysis.

Following data cleaning, the project explores time-based trends in terrorism. This includes analyzing how the frequency of attacks has changed over the years and identifying periods of significant increase or decline. Such analysis helps in understanding the evolution of global terrorism and detecting any historical patterns or anomalies.

The project also emphasizes geographical analysis, identifying the most affected regions, countries, and cities. By visualizing the distribution of attacks across different locations, the analysis highlights hotspots of terrorist activity and provides insights into regional vulnerabilities. This can be further extended to compare terrorism intensity across continents and regions.

Another key aspect of the analysis is examining attack characteristics, such as attack types, weapon types, and target categories. This helps in understanding the most commonly used methods and the typical targets of terrorist organizations. For example, insights can be drawn about whether bombings, armed assaults, or kidnappings are more prevalent, and which sectors (e.g., civilians, military, government) are most frequently targeted.

The project also includes an impact assessment, analyzing casualties in terms of the number of people killed and wounded. This provides a deeper understanding of the severity of attacks and helps identify the most destructive incidents. Additionally, relationships between different variables—such as attack type and casualty count—are explored to uncover deeper patterns.

To effectively communicate findings, the project utilizes at least five different visualizations, including bar charts, line graphs, heatmaps, and distribution plots. These visual tools play a vital role in simplifying complex data and making insights more interpretable.

Overall, this EDA project provides a comprehensive overview of global terrorism trends and patterns. It demonstrates how data analysis techniques can be applied to large real-world datasets to extract actionable insights. The findings from this analysis can contribute to a better understanding of terrorism dynamics and may support policymakers, researchers, and security agencies in making informed decisions.


---

## 🎯 Objectives

* 📂 Load and inspect the dataset
* 🧹 Handle missing values and duplicate rows
* 🔄 Clean incorrect data types
* ➕ Create new useful columns such as casualties
* 📊 Perform exploratory data analysis
* 📈 Visualize key trends using charts
* 💡 Generate insights that are useful for stakeholders
* 🧹Analyze terrorism trends from 1970–2017
* 📊 Identify most affected countries and regions
* 📊Understand attack types and weapons used
* ➕  Study casualties and impact
* 📈Generate insights useful for stakeholders

---

## 🛠️ Tools Used

* 🐍 Python
* 🐼 Pandas
* 🔢 NumPy
* 📉 Matplotlib
* 🎨 Seaborn

---

## 🧼 Data Cleaning Steps

The following cleaning steps were performed:

* 🗑️ Removed duplicate rows
* ⚠️ Handled missing values in important columns
* 🔧 Converted incorrect data types into proper numeric or text formats
* ➕ Created a new column called `casualties` using `nkill + nwound`
* 📅 Created additional helpful columns such as `year`, `decade`, and `month_name`

---

## 📌 Key Columns Used

* 📅 `iyear`
* 📆 `imonth`
* 📍 `iday`
* 🌎 `country_txt`
* 🗺️ `region_txt`
* 🏙️ `city`
* 💣 `attacktype1_txt`
* 🎯 `targtype1_txt`
* 👥 `gname`
* 🔫 `weaptype1_txt`
* ☠️ `nkill`
* 🤕 `nwound`
* ✅ `success`
* ⚔️ `suicide`
* 📊 `casualties`

---

## 📊 Exploratory Data Analysis

The analysis focuses on:

* 📈 Terrorist attacks by year
* 🌍 Countries with the highest number of attacks
* 💣 Most common attack types
* 🎯 Most affected target types
* ☠️ Casualty distribution
* 📦 Outliers in attack impact
* 🔗 Correlation between numerical variables

---

## 📉 Visualizations

The project includes the following visualizations:

1. 📈 Line chart for attacks by year
2. 📊 Bar chart for top affected countries
3. 💣 Bar chart for attack type frequency
4. 🥧 Pie chart for target type distribution
5. 📉 Histogram for casualties
6. 📦 Box plot for outliers in casualties
7. 🔥 Heatmap for numerical correlations

---

## 💡 Key Insights

* 🌍 Terrorist attacks are not evenly distributed across time or geography
* 📍 Some countries and regions experience significantly more attacks than others
* 💣 Bombing and explosive attacks are often common
* 🎯 Civilian and public targets are frequently affected
* 📊 Casualty values are highly skewed, showing that a small number of events cause large losses
* 🧠 The dataset can help identify high-risk areas and support security planning

---

## 👥 Stakeholder Usefulness

This project is useful for:

* 🏛️ Governments planning counter-terrorism strategies
* 🛡️ Security agencies monitoring risk patterns
* 🎓 Researchers studying terrorism trends
* 📜 Policy makers allocating resources
* 🌐 International organizations evaluating regional threats

---

## 📁 Project Structure

```bash
project-folder/
├── Global_Terrorism_Data.csv
├── notebook.ipynb
├── README.md
└── images/
```

---

## 🚀 How to Run

1. 📥 Clone this repository
2. 💻 Open the notebook in Google Colab or Jupyter Notebook
3. 📦 Install required libraries if needed
4. ▶️ Run the notebook cells step by step
5. 👀 View the cleaned dataset, charts, and insights

---

## 🏁 Conclusion

This project provides a structured analysis of global terrorism data. It shows how data cleaning, exploratory analysis, and visualization can uncover useful patterns and support better decision-making.

---

## ✍️ Author

**Adiba Ansari**
