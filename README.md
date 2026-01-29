#Machine Failure Prediction Predict machine failures from time-series sensor data to reduce downtime and optimize maintenance. 
#🔍 Project Overview This project trains supervised machine learning models on historical sensor readings to forecast imminent equipment failures and estimate remaining useful life.
It supports both classical and deep learning approaches, and includes a simple interface for serving predictions. 
## 📁 Repository Structure
├── app.py                # Inference and serving interface
├── train.py              # Data preprocessing and model training
├── model.pkl             # Saved trained model
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation
└── data/
├── sample_data.csv
└── sensor_data_large.csv
## ⚙️ Features

- **Preprocessing**: Handles missing values, normalization, and temporal slicing
- **Models**: Random Forest, XGBoost, RNN, and 1D-CNN for sequence prediction
- **Evaluation**: Precision, Recall, F1, ROC-AUC, and time-to-failure metrics
- **Reproducibility**: Clean scripts and dependency management

## 🚀 How to Use

### 1. Install dependencies
```bash
pip install -r requirements.txt
###2. Train the model
python train.py

## 3. Run inference
python app.py

## 4. Explore the data
Open data/sample_data.csv or sensor_data_large.csv using pandas or a spreadsheet viewer.

🎯 Expected Outcome
The system generates actionable failure predictions with timestamps and confidence scores, enabling proactive maintenance scheduling and reduced operational costs.

🧠 Tech Stack
Python, pandas, scikit-learn, XGBoost, PyTorch

FastAPI (for serving)

Git, GitHub Pages
