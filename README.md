This project is a beginner-friendly AI/ML-based software tool that estimates the carbon footprint of daily human activities—such as transportation, energy use, food consumption, and electronics usage. It helps users understand the environmental impact of their habits and offers actionable tips to reduce emissions.

## 📦 Project Structure
CarbonFootprintEstimator/ 
│ ├── preprocessing/         # Fetches and prepares emission factor data 
│   └── emission_factors_api.py
│   └── daily_carbon_activities.csv
│   └── cleaned_data.csv
│   └── carbon_preprocessing.ipynb
│ ├── training_model/        # ML model training using historical data 
│   └── train_model.ipynb 
│   └── carbon_model.pkl 
│   └── test_model.ipynb
│ ├── source_code/           # Final app that takes user input and gives output 
│   └── app.ipynb 
│ └── README.md              # Project documentation


## 🚀 Features

- Estimates carbon emissions based on real-time user input
- Uses live emission factors from trusted sources
- Categorizes footprint as Good, OK, or Bad
- Provides personalized tips to reduce environmental impact

## 🧪 How to Run

1. Install dependencies:
  pip install pandas numpy scikit-learn requests streamlit

2. Run the app:
- Open `app.ipynb` in Jupyter Notebook  
- Or run the Streamlit app:
  ```
  streamlit run app.py
  ```

3. Enter your daily activity:
- Example:  
  - Category: Transportation  
  - Activity: Car – gasoline (commute)  
  - Daily Value: 30 km  
  - Emission Factor: 0.241

4. View your footprint:
  - Estimated CO₂ emissions
  - Rating (Good / OK / Bad)
  - Tips to reduce your footprint

## 📊 Example Output
🌍 Estimated Emission: 7.23 kg CO₂e/day 
⚠️ OK – You're doing alright, but there's room to improve. 
💡 Tips to reduce your footprint: 
 • Try carpooling or switching to electric vehicles 
 • Reduce meat consumption, especially red meat 
 • Turn off unused electronics and lights


## 📚 License

This project is open-source and free to use for educational and environmental awareness purposes.

