# Obesity_Feature_Analysis 

Introduction
Obesity is a growing public health concern worldwide, leading to various chronic diseases such as diabetes, cardiovascular disorders, and hypertension. Understanding obesity patterns through data analysis can help identify risk factors and develop preventive strategies. This project applies machine learning clustering techniques to obesity-related data to segment individuals into meaningful groups based on their health characteristics. By identifying different obesity clusters, we can gain insights into potential risk factors and lifestyle patterns associated with obesity.

Dataset Overview
The dataset used in this project contains various features related to individuals’ demographic, lifestyle, and health attributes. These include age, gender, BMI (Body Mass Index), physical activity levels, dietary habits, and medical history. Before applying clustering algorithms, data preprocessing was performed, including handling missing values, scaling numerical features, and encoding categorical variables. The dataset was then split into training and testing sets for further analysis.

Methodology
The analysis begins with data preprocessing, where numerical features are standardized using scikit-learn’s StandardScaler, and categorical variables are encoded using Label Encoding. After preparing the data, various clustering algorithms such as K-Means, Hierarchical Clustering, and DBSCAN are applied to segment individuals into different obesity risk categories. The optimal number of clusters is determined using methods like the Elbow Method and Silhouette Score. The results of each clustering approach are then compared to assess which method provides the most meaningful segmentation of the data.
