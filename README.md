# Fraud-detection-system


#	Navigate to your local repo folder
cd path/to/your/repo

#Open README.md in a text editor
nano README.md

#Or use VS 
code README.md

#Commit and push the changes
git add README.md
git commit -m "Add full README content"
git push origin main



#	1.	Data Loading & Exploration:
#Loads the data, explores fraud distribution, and visualizes transaction patterns.
#	2.	Preprocessing:
#Removes non-informative columns, encodes categorical features numerically, and splits the data into training and test sets.
#	3.	Model Training & Evaluation:
#Trains K-Nearest Neighbors, Random Forest, and XGBoost classifiers. Each is evaluated using precision, recall, F1-score, confusion matrix, and ROC-AUC.
#	4.	Ensemble Learning:
#Combines all models using a soft voting classifier, with extra weight on Random Forest to boost recall.
#	5.	Performance Insight:
#Each model has strengths, but the ensemble achieves the best balance between fraud recall and precision.
