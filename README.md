# 🏠 RentHop Interest Predictor

A machine learning web application that predicts user interest in rental listings using property information and listing descriptions. Built with Python, Scikit-learn, and Streamlit, the application provides an interactive way to explore rental listing interest prediction.

## 🚀 Live Demo

**Try the application here:** [RentHop Interest Predictor](https://rentallistingprediction-ecomk8fjyzszzwtymnsyhv.streamlit.app/)

## 📌 Project Overview

Rental platforms contain numerous property listings, making it useful to understand which listings are more likely to attract user interest.

This project applies machine learning and natural language processing techniques to predict interest in rental listings based on relevant listing features. It aims to demonstrate how structured property data and textual descriptions can be used for predictive analysis.

## ✨ Features

* 🏡 **Interest Prediction:** Predict the interest category of a rental listing.
* 📝 **Text Analysis:** Use listing descriptions as input for prediction.
* 📊 **Feature Processing:** Handle numerical and textual listing information.
* 🤖 **Machine Learning:** Apply trained classification models to rental data.
* 🖥️ **Interactive Interface:** Enter listing details through a Streamlit application.
* ☁️ **Online Deployment:** Access the application through Streamlit Community Cloud.

## 🛠️ Technologies Used

* **Python** – Core programming language
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical computing
* **Scikit-learn** – Machine learning and model evaluation
* **TF-IDF** – Text feature extraction from listing descriptions
* **Natural Language Processing (NLP)** – Processing textual information
* **Streamlit** – Interactive web application
* **Joblib** – Saving and loading trained models
* **Git & GitHub** – Version control and project hosting

## 🧠 Machine Learning Approach

The project explores classification techniques to predict rental listing interest.

### Workflow

1. Load and explore the rental listing dataset.
2. Clean and preprocess the data.
3. Prepare numerical features and textual descriptions.
4. Convert text into numerical features using TF-IDF.
5. Train and evaluate classification models.
6. Select a trained model for predictions.
7. Deploy the prediction application using Streamlit.

## 📊 Model Evaluation

Machine learning models can be evaluated using the following metrics:

* **Accuracy:** Measures the proportion of correct predictions.
* **Precision:** Measures how many predicted instances of a class are correct.
* **Recall:** Measures how many actual instances of a class are identified.
* **Macro F1-score:** Evaluates classification performance across classes while giving each class equal weight.

The actual evaluation results depend on the trained model and test dataset.

## ⚙️ Run Locally

### 1. Clone the Repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd <YOUR_REPOSITORY_FOLDER>
```

Replace the placeholders with your actual repository details.

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch the Application

```bash
streamlit run app.py
```

Open the local URL displayed in the terminal, usually `http://localhost:8501`.

## 📂 Project Structure

```text
RentHop-Interest-Predictor/
│
├── app.py                    # Streamlit application
├── requirements.txt          # Project dependencies
├── *.joblib                  # Saved model files, if included
└── README.md                 # Project documentation
```

The filenames and model artifacts should be adjusted to match the actual repository.

## ☁️ Deployment

The application is hosted on Streamlit Community Cloud.

🔗 **Live Application:** https://rentallistingprediction-ecomk8fjyzszzwtymnsyhv.streamlit.app/

## 🎯 Learning Outcomes

* Understanding the machine learning classification workflow
* Preprocessing structured rental listing data
* Applying TF-IDF for text feature extraction
* Combining numerical and text-based features
* Evaluating models using classification metrics
* Building and deploying an interactive machine learning application

## 🔮 Future Improvements

* Improve classification performance through hyperparameter tuning.
* Add visualizations for rental listing characteristics.
* Compare different classification algorithms.
* Improve the user interface and prediction explanations.
* Analyze which listing features contribute most to predicted interest.

## ⚠️ Disclaimer

Predictions are estimates produced by a machine learning model and should not be treated as guaranteed measures of actual user interest.

## 👩‍💻 Author

Developed as a machine learning project focused on rental listing interest prediction and interactive web deployment.

---

⭐ If you find this project interesting, consider giving the repository a star!
