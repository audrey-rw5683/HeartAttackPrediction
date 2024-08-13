# Heart Attack Prediction and Analysis Using Kaggle Dataset and Machine Learning

- This project presents a comprehensive analysis of heart attack data using Python, delivered through the Jupyter Notebook environment. It employs a range of machine learning algorithms, including logistic regression, decision trees, random forests, and support vector machines, to predict the likelihood of a heart attack based on the available data. 
- To improve model performance, I fine-tuned hyperparameters using grid and random search. The performance of these models is evaluated using metrics such as accuracy, ROC and AUC. 
- The findings from this analysis aim to provide actionable insights for healthcare professionals and researchers, potentially aiding in the development of targeted prevention strategies and interventions. 

## Details
- Exploratory data analysis(EDA) phase: I used histograms and pie charts to showcase the distribution of individual variables and explored the correlation between variables with FacetGrid, swarm, box plot, and heatmap. 

- Data preparation stage: I eliminated variables with low correlation to the target variable and handled outliers in the remaining variables using the z-score and interquartile methods. For categorical variables, I converted them into numerical representations using one-hot encoding to make the data more suitable for the algorithm.

- Modeling: I employed four different algorithms and applied cross-validation and hyperparameter optimization techniques to improve accuracy. The performance is evaluated by ROC and AUC.

**Results:**
- Logistic Regression model:  87% accuracy and an AUC of 88%.
- Decision Tree model: 83% accuracy and an AUC of 85%.
- Support Vector Machine model: 83% accuracy and an AUC of 89%.
- Random Forest model: 90.3% accuracy and an AUC of 93%.

Based on the evaluation of all model outputs, the Random Forest Algorithm emerged as the preferred choice due to its superior performance.

## Discussion:
This project enhanced my understanding of data processing and model-building processes. At the same time, I also hope to make some impact on disease prevention and early diagnosis. Admittedly, whether this model will perform well on other databases remains to be seen. However, this also highlights its applicability as a future area of work.