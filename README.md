🏡 House Price Prediction with XGBoost 🚀

This project utilizes XGBoost to predict Airbnb listing prices based on various property attributes such as location, amenities, and property details.

📌 Features

👉 Machine Learning Model – Uses a pre-trained XGBoost model for price prediction.👉 Feature Selection – Implements Variance Thresholding to remove low-variance features.👉 Data Preprocessing – Handles missing values, categorical encoding, and ensures feature consistency.👉 Scalable & Modular – Designed for easy dataset expansion and model updates.

🛠 Installation & Setup

1⃣ Clone the repository

git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction

2⃣ Create a virtual environment (optional but recommended)

python -m venv venv
source venv/bin/activate  # On Mac/Linux
venv\Scripts\activate     # On Windows

3⃣ Install dependencies

pip install -r requirements.txt

🚀 Running the Model

To predict Airbnb listing prices using new data:

python src/app.py

The script will:

Preprocess the data – handle missing values, encode categorical features.

Apply feature selection – ensure consistency with training features.

Predict prices – using the trained XGBoost model.

📝 Notes

📌 Ensure that new_airbnb_listings.csv is inside the data/ directory before running predictions.📌 If you encounter a feature shape mismatch error, check if the training and prediction datasets have matching features.📌 The script automatically handles missing features by adding placeholders.

🔥 Future Enhancements

👉 Improve feature engineering for better accuracy.👉 Optimize preprocessing pipeline for efficiency.👉 Add a Flask API to serve predictions via a web interface.

🐜 License

This project is licensed under the MIT License.Feel free to contribute, improve the model, and build on top of it! 😊

