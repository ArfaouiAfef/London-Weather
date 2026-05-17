# 🌤 London Weather Temperature Prediction

A complete end-to-end Machine Learning project that predicts the **daily mean temperature** of London based on historical meteorological parameters:

- Cloud Cover (oktas)
- Sunshine (hours)
- Global Radiation (W/m²)
- Max / Min Temperature (°C)
- Precipitation (mm)
- Pressure (Pa)
- Snow Depth (cm)
- Exact Date (Year, Month, Day)

The project combines:

✅ Advanced Data Cleaning & Imputation  
✅ Feature Engineering (Temporal Extraction)  
✅ Machine Learning Regression Models  
✅ Evaluation Metrics Optimization  
✅ Flask Web Application (with Glassmorphism UI)  
✅ Dynamic Data Visualization (Chart.js)  

---

# 🚀 Technologies Used

## Python & Machine Learning
- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib (Model Serialization)
- Regression Algorithms (Linear Regression, Random Forest, Gradient Boosting, XGBoost)

## Frontend & Visualization
- HTML5 / CSS3 (Custom Glassmorphism Design)
- Bootstrap 5 (Responsive Layout)
- Font Awesome 6 (Modern UI Icons)
- Chart.js (Dynamic Frontend Line Charts)

## Web Application Backend
- Flask
- Jinja2 Templates

---

# 📊 Project Features

## Machine Learning & Backend
- **Data Preprocessing:** Handling of missing weather values using robust imputation techniques.
- **Feature Engineering:** Extracted temporal features (Year, Month, Day) to capture seasonal weather cycles.
- **Model Training & Selection:** Compared multiple regression models using R² Score, MAE, and RMSE to track down the most reliable predictor.
- **Persistence:** Efficient model serialization using Joblib for real-time inference pipeline integration.

## Flask Web UI
Users can:
- Input real-time meteorological parameters into a sleek, glass-textured form.
- Use a **Toggle Dark Mode** switch for a comfortable viewing experience.
- Instantly view the predicted mean temperature in Celsius (°C).
- Watch an automated **Dynamic Progress Bar** scale instantly based on the temperature output.
- Interact with a live **Chart.js Line Graph** showcasing the temperature scaled across climate thresholds (Cold, Mild, Warm, Hot).
- Reset parameters seamlessly with an automated form-clearing handler.

---

# 🧠 Machine Learning Regression Pipeline

The best predictive model was optimized and selected based on key performance regression metrics:
- **R² Score** (Coefficient of Determination)
- **MAE** (Mean Absolute Error)
- **RMSE** (Root Mean Squared Error)

---

# 📂 Project Structure

