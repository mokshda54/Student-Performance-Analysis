**Student Performance Analysis**: Identifying the Key Factors Affecting Academic Results



**Project Overview**



This project analyzes student performance data to understand how different demographic, family, lifestyle, and educational factors are associated with academic results.



The analysis focuses on students' mathematics, reading, and writing scores to identify patterns related to parental education, lunch type, test preparation, ethnicity, sports participation, weekly study hours, and other factors.



**Project Objective**



The main objective is to identify factors associated with student academic performance and understand which student groups achieve higher average scores.



**Key Questions**



* How does academic performance vary across ethnic groups?



* Is parental education associated with students' scores?



* Do students receiving standard lunch achieve higher average scores?



* Does completing test preparation relate to better academic results?



* Is there a difference in scores based on parents' marital status?



* How is sports participation associated with academic performance?



* Does being the first child or having siblings relate to student scores?



* How do transportation methods relate to academic results?



* How do weekly study hours relate to mathematics, reading, and writing scores?



**Dataset**



Source: Student Data Dataset on GitHub



File: student\_data.csv



Format: CSV





**Tools and Technologies**



* Python – Data analysis



* Google Colab – Notebook development and execution



* Pandas – Data cleaning, grouping, and pivot tables



* NumPy – Numerical operations



* Matplotlib – Data visualization support



* Seaborn – Heatmaps and statistical visualization



* Data Cleaning and Preparation



* The following steps were performed:



* Imported the required Python libraries.



* Loaded the dataset using Pandas.



* Examined dataset information, column names, and data types.



* Removed the unnecessary Unnamed: 0 column.



* Checked for missing values and removed rows containing them.



* Checked for duplicate records.



* Reset the DataFrame index after cleaning.



* Prepared the cleaned dataset for exploratory data analysis.





**Exploratory Data Analysis (EDA)**



Pivot tables were created to calculate average mathematics, reading, and writing scores for different student groups. Seaborn heatmaps were used to visualize the results.



1\. Ethnic Group Analysis



Compared average scores across ethnic groups.



Observation: Groups D and E showed comparatively strong academic performance in the analyzed dataset.



2\. Parental Education Analysis



Examined the relationship between parents' education levels and students' scores.



Observation: Students whose parents had bachelor's or master's degrees showed higher average scores in the analysis.



3\. Lunch Type Analysis



Compared academic performance across lunch types.



Observation: Students receiving standard lunch showed higher average scores.



4\. Test Preparation Analysis



Compared the scores of students based on test preparation course status.



Observation: Students who completed test preparation showed higher average scores.



5\. Parents' Marital Status Analysis



Compared mathematics, reading, and writing scores across parental marital-status groups.



Observation: No clear difference was identified from the initial visual analysis. Further statistical analysis would be needed to assess the relationship.



6\. Sports Participation Analysis



Examined academic scores according to sports participation.



Observation: Students who practiced sports regularly showed comparatively higher average scores.



7\. First Child and Number of Siblings Analysis



Investigated whether being the first child or having different numbers of siblings was associated with academic performance.



Observation: The initial visual analysis did not establish a clear relationship.



8\. Transportation Analysis



Compared student scores across transportation methods.



Observation: The initial analysis did not establish a strong or consistent relationship between transportation method and academic scores.



9\. Weekly Study Hours Analysis



Examined average scores across weekly study-hour categories.



Observation: Students studying 5–10 hours or more per week showed comparatively strong academic performance in the analyzed data.





**Key Findings**



Based on the initial exploratory analysis:



Ethnic groups D and E showed comparatively higher average scores.



Higher parental education levels were associated with stronger average academic results.



Students receiving standard lunch showed higher average scores.



Completing test preparation was associated with better average scores.



Regular sports participation was associated with comparatively higher scores.



Students in higher weekly study-hour categories showed strong academic performance.



The initial analysis did not establish clear relationships for parental marital status, first-child status, number of siblings, or transportation method.



These findings describe patterns in the dataset and do not establish that any factor directly causes better or worse academic performance.



**Conclusion**



This project demonstrates how Python can be used to clean, analyze, and visualize student performance data.



The analysis suggests that parental education, lunch type, test preparation, sports participation, and weekly study hours are useful factors to investigate when studying academic performance. The findings can help educators and researchers identify patterns and explore areas where students may benefit from additional academic support.

