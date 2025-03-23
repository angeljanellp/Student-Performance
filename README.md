# Student performances

Education systems have been trying to find ways improve the overall grade of students. They started implementing more help services, such as tutoring, family-support centers, mental-health services, etc. However, we do not know whether or not they need it, as there is a variety of students that need these or not.

## Goal:

This clustering analysis will help see who needs those services and who doesnt based on their cluster group

## Source:

This csv file was created by Rabie El Kharoua, in 2024, and was published in Kaggle. 

url: https://www.kaggle.com/ds/5195702

## Description:
- Imports
- Data Exploration
- Data Analysis
- A bit of data preparation. No encoding as all values were numerical and No filling tyhe Nan Values as they were no null values.
- Creation of Model 1: KMeans
- Creation of Model 2: DBSCAN
- Analysis with both models
- Creation of final Model and new predictions

## Findings:

- We saw that their age did not matter on their study weekly time.
- We saw that their gpa were affected by Extracurricular Activities, Parental support, absences an study time.
- In the creation of the models, we saw that kmeans had better more equal clustering group compared to DBSCAN.

Enjoy the analysis :grin:
