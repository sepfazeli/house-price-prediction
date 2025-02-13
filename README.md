🏡 House Price Prediction with XGBoost

Welcome to the House Price Prediction repository! 🚀 This project leverages XGBoost to predict Airbnb listing prices based on various features such as location, amenities, and property details.

📌 Features
 
Machine Learning Model: Uses a pre-trained XGBoost model for price prediction.
Feature Selection: Implements Variance Thresholding to remove low-variance features.
Data Preprocessing: Handles missing values and categorical encoding.
Modular & Scalable: Designed for easy dataset expansion and model updates.
📂 Project Structure

📦 house-price-prediction
├── 📁 data
│   ├── airbnb_listings.csv  # Original dataset
│   ├── new_airbnb_listings.csv  # New data for predictions
├── 📁 models
│   ├── airbnb_price_xgb.pkl  # Trained XGBoost model
│   ├── feature_selector.pkl  # Variance threshold feature selector
├── 📁 src
│   ├── app.py  # Main script to load, preprocess, and predict
│   ├── utils.py  # Utility functions (if needed)
├── requirements.txt  # Python dependencies
└── README.md  # You’re reading it now!
🛠 Installation & Setup

Clone the repository
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction
Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Mac/Linux
venv\Scripts\activate  # On Windows
Install dependencies
pip install -r requirements.txt
🚀 Running the Model

To predict prices on new Airbnb listings:

python src/app.py
The script will preprocess the data, apply feature selection, and predict prices using the trained XGBoost model.

📝 Notes

Ensure that new_airbnb_listings.csv is in the data/ directory before running predictions.
If you encounter a feature shape mismatch error, check whether the features in your training and prediction datasets align.
The app.py script automatically handles missing features by adding placeholders.
📌 Future Enhancements

✅ Improve feature engineering for better model accuracy.
✅ Optimize preprocessing pipeline for efficiency.
✅ Add a Flask API to serve predictions via a web interface.
📜 License

This project is licensed under the MIT License. Feel free to contribute and improve the model! 😊

