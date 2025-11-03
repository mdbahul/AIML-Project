## How to Run the Code
### Easiest Way is to copy collab notebook and run in collab online
[Collab Notebook](https://colab.research.google.com/drive/1V_WZ-fFInVq9iSdbVFXVrKHs7pAEyFKI?usp=sharing)

## To run locally
1. **Clone the repository (or download the files):**
   ```
   git clone https://github.com/mdbahul/AIML-Project.git
   cd stress-level-detection
   ```
2. **Install required dependencies:**

```pip install pandas numpy seaborn matplotlib plotly scikit-learn```

3. **Ensure the dataset file is in the same directory:**
Kaggle link to dataset : [Sleep-Health-and-Lifestyle](https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset/data)

```
Sleep_health_and_lifestyle_dataset.csv
```

4. **Run the Python file or Jupyter Notebook:**
```
jupyter notebook stress_level_detection.ipynb
```
5. **To predict your own stress level:**
Run the last block again. 
```
user_input = get_user_input()
predicted_stress_level = random_forest.predict(user_input)
print("Predicted Stress Level:", predicted_stress_level[0])
```
