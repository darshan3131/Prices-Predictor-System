
Prices-Predictor-System

A machine learning pipeline for predicting prices based on structured data. This project includes data preprocessing, feature extraction, model training, and deployment.

📌 Features
	•	Exploratory Data Analysis (EDA)
	•	Data Cleaning & Preprocessing
	•	Feature Engineering & Transformation
	•	Model Training & Evaluation
	•	MLflow for Experiment Tracking
	•	Deployment Script for Serving Predictions

📂 Project Structure

Prices-Predictor-System/  
│── analysis/             # Exploratory Data Analysis (EDA) and insights  
│── data/                 # Raw and processed datasets  
│── explanations/         # Documentation and explanation of model outputs  
│── extracted_data/       # Features and transformed data ready for ML  
│── mlruns/0/             # MLflow tracking for experiments  
│── pipelines/            # Model training and prediction pipelines  
│── src/                  # Core source code for data processing and modeling  
│── steps/                # Step-wise execution scripts  
│── config.yaml           # Configuration file for model parameters  
│── requirements.txt      # Dependencies and package requirements  
│── run_pipeline.py       # Main script to execute the ML pipeline  
│── run_deployment.py     # Deployment script for serving predictions  
│── sample_predict.py     # Sample inference script  
│── LICENSE               # Open-source license  
│── README.md             # Documentation file (You are here!)  

🚀 Installation

1️⃣ Clone the Repository

git clone https://github.com/darshan3131/Prices-Predictor-System.git
cd Prices-Predictor-System

2️⃣ Set Up a Virtual Environment

python3 -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate     # On Windows

3️⃣ Install Dependencies

pip install -r requirements.txt

🎯 Usage

Run the full pipeline:

python run_pipeline.py

Make predictions on new data:

python sample_predict.py --input data/sample_input.csv

📊 Model Tracking with MLflow

This project uses MLflow to track model training and experiments.
Start the MLflow UI with:

mlflow ui

Then, open http://localhost:5000 in your browser.

🤝 Contributing
Contributions are welcome! Feel free to fork the repo and submit a pull request.

📝 License

This project is licensed under the MIT License.

📩 Contact

For any queries, reach out to:
📧 darshansiddarth05@gmail.com

