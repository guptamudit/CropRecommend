# 📌 Crop Recommendation Model

The **Crop Recommendation Model** utilizes machine learning algorithms to suggest the most suitable crops for farmers based on environmental and soil factors. By analyzing data such as soil nutrients, temperature, humidity, pH, and rainfall, the model provides tailored crop recommendations to ensure optimal growth and productivity. The model uses seven classification algorithms, with **Random Forest** achieving the highest accuracy of 99.55%. This helps farmers make informed decisions on crop selection, ensuring better yields and efficient farming practices.

## Dataset

This dataset consists of **2200 rows** in total.
**Each row has 8 columns representing Nitrogen, Phosphorous, Potassium, Temperature, Humidity, PH, Rainfall and Label**
NPK(Nitrogen, Phosphorous and Potassium) values represent the NPK values in the soil. Temperature, humidity and rainfall are the average values of the sorroundings environment respectively. PH is the PH value present in the soil. **The Label column tells us the type of crop that's best suited to grow based on these conditions.
Label is the value we will be predicting**


## Model Architecture
 
For the Crop Recommendation Model, seven classification algorithms were utilized to predict suitable crop recommendations. These algorithms include:

- Decision Tree
- Gaussian Naive Bayes
- Support Vector Machine (SVM)
- Logistic Regression
- Random Forest (achieved the best accuracy)
- XGBoost
- KNN
  
Each algorithm was trained on a dataset comprising various factors such as soil nutrients, climate conditions, and historical data to provide accurate crop recommendations to farmers.

## Integration

These two models are integrated into the Smart Crop Recommendation System with Plant Disease Identification. This system provides farmers with comprehensive support, offering both crop recommendations based on various factors and precise identification of crop diseases through image analysis. By combining these models, the system enables farmers to make informed decisions, optimize crop selection, and effectively manage plant diseases for sustainable agriculture and enhanced productivity.

## Results

- Seven classification algorithms were evaluated for crop recommendation tasks.
- The accuracy of each algorithm was assessed, with the Random Forest algorithm achieving the highest accuracy of 99.54%.
- Table 1 below illustrates the accuracy achieved by each algorithm:

**Table 1: Accuracy vs Algorithms**

| Algorithm            | Accuracy   |
|----------------------|------------|
| Decision Tree        | 90.0       |
| Gaussian Naive Bayes| 99.09      |
| Support Vector Machine (SVM) | 10.68 |
| Logistic Regression  | 95.23      |
| Random Forest        | 99.55      |
| XGBoost              | 99.09      |
| KNN                  | 97.5       |

## 👨‍💻 CONTRIBUTERS
- Mudit Gupta
- Anisha Asnani
- Kashish Khanna
