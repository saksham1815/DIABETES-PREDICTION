
# Diabetes Prediction App 🎯  
This is a **Streamlit-based web application** that predicts whether a patient is diabetic or not based on their medical input parameters. The app leverages pre-trained machine learning models for prediction, including:  
- Logistic Regression  
- Random Forest  
- Gaussian Naive Bayes  

The app features:  
- 📊 **Multiple ML Model Selection**: Choose from three pre-trained models.  
- 🖥 **User-Friendly Interface**: Input fields for key medical data (e.g., glucose, BMI, age).  
- 🎨 **Custom Styling**: Includes an interactive design with a GIF background for visual appeal.  


### 🚀 Getting Started
1. Clone the repository:  
   ```bash
   git clone https://github.com/<your-username>/diabetes-prediction-app.git
   cd diabetes-prediction-app
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the app:  
   ```bash
   streamlit run app.py
   ```

### 🛠 Models Used
- **Logistic Regression**: For simple linear classification.  
- **Random Forest**: For robust ensemble-based predictions.  
- **Gaussian Naive Bayes**: For probabilistic predictions.  

All models were trained on diabetes datasets and serialized using `pickle`.


### 💡 Features
- **Live Predictions**: Results are displayed in real-time based on user input.  
- **Responsive Design**: Works seamlessly across devices.  
- **Easy Integration**: Extendable codebase for further customization.  

---

### 📁 Repository Structure
- `app.py`: Main application file.  
- `model_diabetes.sav`: Logistic Regression model.  
- `model_diabetes_random_forest.sav`: Random Forest model.  
- `model_diabetes_gaussian.sav`: Gaussian Naive Bayes model.  
- `requirements.txt`: List of dependencies.  


### 📜 License
This project is licensed under the MIT License.  
Feel free to contribute and improve the app! 🎉  

