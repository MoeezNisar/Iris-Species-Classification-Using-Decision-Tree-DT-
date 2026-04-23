# 🌸 Iris Flower Species Prediction 

Is project ka maqsad **Decision Tree Classifier** ka istemal karte hue Iris phoolon ki teen mukhtalif aqsaam (Species) ki darja-bandi (Classification) karna hai. Isme humne data analysis se lekar model deployment tak ka poora amal shamil kiya hai.

## 📊 Dataset Overview
Humne mashhoor **Iris Dataset** ka istemal kiya hai, jisme 150 samples hain. Har sample ke 4 features hain:
- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)
**Target Classes:** Iris-setosa, Iris-versicolor, Iris-virginica.

## 📂 Project Components
1. **`Iris_flower_Prediction_Using_DT.ipynb`**: Poori implementation (Python code).
2. **`Iris flower.csv`**: Raw dataset file.
3. **`decision_tree_model.joblib`**: Trained aur optimized model, jo production ke liye tayyar hai.

## 🛠️ Technical Workflow
Project ko darj-zail marahil (stages) mein divide kiya gaya hai:

### 1. Exploratory Data Analysis (EDA)
- **Pandas** ka istemal karte hue data ki statistics check ki gayin.
- **Seaborn** aur **Matplotlib** ke zariye Heatmaps aur Pairplots banaye gaye taake features ke darmayan correlation ko samjha ja sake.

### 2. Model Development
- Data ko Training aur Testing sets mein split kiya gaya.
- **Scikit-Learn** ka Decision Tree algorithm apply kiya gaya.
- Model ko **Pruning** (Tree depth control) ke zariye optimize kiya gaya taake overfitting na ho.

### 3. Model Saving
- `joblib` library ka istemal karte hue final model ko serialize kiya gaya, taake ise kisi bhi web app ya software mein direct load kiya ja sake.

## 🚀 How to Run
Project ko local machine par chalane ke liye:
1. Repository clone karein.
2. Niche di gayi libraries install karein:
   ```bash
   pip install pandas seaborn matplotlib scikit-learn joblib
