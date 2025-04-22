# Health-Risk-Classification_202401100300154

This project is designed to predict a person’s health risk category (**Low**, **Medium**, or **High**) based on their **BMI**, **exercise hours per week**, and **junk food consumption frequency**. It also includes clustering to group individuals with similar health profiles.

---

##  Author Information

- **Name**: Mohammad Fahim  
- **Roll No.**: 202401100300154
- **Branch**: B.Tech CSE (AI)  
- **College**: KIET Group of Institutions  

---

##  Problem Statement

To classify individuals into Low, Medium, or High health risk categories using machine learning techniques and group similar individuals using clustering algorithms.

---

##  Dataset

The dataset used includes the following features:
- **bmi**: Body Mass Index
- **exercise_hours**: Hours of exercise per week
- **junk_food_freq**: Frequency of junk food consumption per week
- **risk_level**: (Target) Health risk level - low, medium, or high

---

##  Tools and Technologies Used

- Python  
- Google Colab  
- Pandas  
- Scikit-learn  
- Seaborn  
- Matplotlib  

---

##  Features of the Project

1. Reads data from a CSV file.
2. Converts categorical target to numeric for model training.
3. Splits data into training and testing sets.
4. Trains a **Random Forest Classifier** to predict risk levels.
5. Evaluates model using:
   - Accuracy
   - Precision
   - Recall
   - Confusion Matrix (with Heatmap)
6. Performs **KMeans Clustering** to group individuals.
7. Shows clustering results using scatter plots.
8. Calculates **Silhouette Score** for clustering evaluation.

---

##  How to Run the Project

1. Upload the dataset (`health_risk.csv`) to your Google Drive.
2. Open the notebook in Google Colab.
3. Mount your Google Drive using:

```python
from google.colab import drive
drive.mount('/content/drive')
```

4. Set the file path to your CSV file:

```python
file_path = '/content/drive/MyDrive/health_risk.csv'
```

5. Run all cells in the notebook to see results including evaluation metrics and graphs.

---

##  Example Output

**Classification Results**:  
- Accuracy: 92%  
- Precision: 91%  
- Recall: 90%  

**Confusion Matrix**: Heatmap shown in output  
**Clustering Result**: Scatter plot colored by cluster groups  
**Silhouette Score**: 0.61

(*Results may vary based on dataset*)

---

##  Screenshots

You can add screenshots here from Colab output:
- Confusion matrix heatmap
- Clustering scatter plot
- Metrics output

---

##  Credits
- **Libraries**: scikit-learn, pandas, seaborn, matplotlib  
- **Platform**: Google Colab

---

## License

This project is for educational purposes only.
