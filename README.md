# Crop Recommendation System 🌾
This project is a Crop Recommendation System built using Logistic Regression, a simple yet effective machine learning algorithm. It helps farmers and agricultural enthusiasts determine the most suitable crop to cultivate based on soil and environmental parameters.

## 🚀 Features
- **Logistic Regression Model:** Accurate and interpretable predictions using a well-tuned logistic regression algorithm.
- **Easy Input System:** Users can provide parameters like soil composition and climate conditions.
- **Customizable Dataset:** Add or modify data to improve the model's accuracy.
- **Lightweight and Efficient:** Perfect for deployment on resource-constrained systems.

## 📋 Prerequisites
Ensure the following are installed on your system:
- `Python 3.7+`
  
*Required Python libraries:*
- `numpy`
- `pandas`
- `scikit-learn`

## 🛠️ How to Run
1. Clone the repository:
``` bash
git clone https://github.com/shashmitha46/Miniproject-crop-recommendation.git
```
2. Navigate to the project directory:
```
cd Miniproject-crop-recommendation
```
3. Install dependencies:
```
pip install -r requirements.txt
```

## 📊 Dataset
The system utilizes a dataset with the following features:

- Nitrogen (N), Phosphorus (P), Potassium (K) levels
- Temperature
- Humidity
- pH
- Rainfall
The model is trained using this data to predict the most suitable crop for given conditions.

## 🤖 Machine Learning Model
The recommendation system uses a Logistic Regression model due to its simplicity and interpretability. This algorithm predicts the probability of a crop being suitable based on input features. The model has been fine-tuned for optimal performance using:

- Feature normalization
- Hyperparameter optimization

## 📈 Performance Metrics

The Logistic Regression model was evaluated using both a classification report and 5-fold cross-validation. Below are the summarized results:

### Cross-Validation Metrics:
- **Mean Accuracy**: 95.47%
- **Standard Deviation**: 0.90%

### Classification Report Metrics:
- **Accuracy**: 95.2%
- **Weighted Avg Precision**: 95%
- **Weighted Avg Recall**: 95%
- **Weighted Avg F1-Score**: 95%

These metrics indicate that the model performs reliably and consistently across different data splits and classes, ensuring accurate crop recommendations for diverse scenarios.

## 🤝 Contributing
Contributions are welcome! Please fork the repository, create a new branch, make changes, and submit a pull request. Follow the contribution guidelines in the repository.

## 📝 License
This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this project in accordance with the license terms.

## 🙌 Acknowledgments
- Machine Learning Community for resources and support.
- Data Providers for supplying the crop and soil datasets.
- Thanks to contributors for their efforts in building and maintaining this project.

