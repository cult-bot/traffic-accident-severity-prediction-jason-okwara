# Traffic Accident Severity Prediction
**Course**: DSA 1080A Programming for Data Science 
**Student**: Jason Trevor Okwemba Okwara
**Semester**: Fall 2025

## 🎯 Project Goal
Predict the severity level (1–4) of traffic accidents in the US using weather, time, and road condition data.

## 📂 Dataset
- **Source**: [US Accidents (2016–2023) by Sobhan Moosavi](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents) 
- **Note**: The raw dataset is **not included** in this repo due to size (>2GB). Please download it from Kaggle.

## 🛠️ Methodology
1. **Data Loading**: Selected 15 relevant features from the full dataset.
2. **Cleaning**: Handled missing values and invalid timestamps.
3. **Feature Engineering**: Extracted `Hour`, `DayOfWeek`, `Month`, and `Duration(min)`.
4. **Modeling**: Trained a Random Forest classifier on a 100,000-row sample.
5. **Evaluation**: Used accuracy, precision, recall, and F1-score.

## 📊 Key Findings
- The model achieves strong performance on Severity 2 (most common class).
- Time of day and weather conditions are key predictors.
- Class imbalance remains a challenge for rare severity levels (1 and 4).

## ▶️ How to Run
1. Download the dataset from Kaggle.
2. Place `US_Accidents_March23.csv` in this folder.
3. Open `US_Accidents_Severity_Prediction_atlas4.ipynb` in Jupyter.
4. Run all cells sequentially.
