# Traffic Trojan Detector

This project focuses on detecting **Traffic Trojan Malware** using binary classification techniques. It implements multiple machine learning algorithms to classify network traffic and identify potential trojan malware activities.

## Features

- **Binary Classification Models**: Utilizes multiple machine learning models such as:
  - Decision Tree
  - Random Forest
  - Logistic Regression
  - Support Vector Machines (SVM)
  - k-Nearest Neighbors (k-NN)
  - Naive Bayes
  - Gradient Boosting
  - XGBoost

- **Data Preprocessing**: Cleanses and transforms network traffic data for model input.
- **Model Evaluation**: Compares models based on accuracy, precision, recall, and F1-score.
- **Traffic Analysis**: Detects malicious trojan activity in network traffic.

## Tech Stack

- **Programming Language**: Python
- **Libraries**: 
  - scikit-learn
  - pandas
  - NumPy
  - matplotlib
  - seaborn

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/AryanDaksh/Traffic-Trojan-Detector.git
   cd Traffic-Trojan-Detector

## Dataset

The dataset used in this project contains network traffic data with labeled entries for normal and trojan-infected traffic. The data is split into training and testing sets to evaluate model performance.

## How It Works

- **Data Preprocessing**: The raw traffic data is preprocessed to remove noise, handle missing values, and normalize features.
- **Model Training**: Various machine learning models are trained on the preprocessed dataset.
- **Model Evaluation**: The models are evaluated based on their accuracy and confusion matrix. The Decision Tree model achieved the best results with 100% accuracy.
- **Traffic Classification**: The trained model is used to classify new traffic data as either normal or trojan-infected.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you want to contribute to the project.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE.txt) file for more details.