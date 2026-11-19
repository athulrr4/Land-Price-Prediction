#  Land Price Prediction using Linear Regression

## 📌 Project Overview

This project predicts the price of land based on its area (in square feet) using **Linear Regression**, a supervised machine learning algorithm.

The project explores the relationship between land area and price, visualizes the data, builds a regression model, and uses it to make predictions.

## 🎯 Objectives

- Understand and explore the land price dataset.
- Analyze the relationship between land area and price.
- Visualize the data using Matplotlib.
- Build a Linear Regression model using Scikit-learn.
- Predict land prices for a given area.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 📂 Project Structure

```text
Land-Price-Prediction/
│
├── data/
│   └── landpriceprediction.csv
│
├── 03_land_price_prediction.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

## 📊 Dataset

The dataset contains land area and corresponding land prices.

- **land:** Land area in square feet.
- **price:** Price of the land.

Place the dataset file `landpriceprediction.csv` inside the `data/` folder before running the notebook.

## ⚙️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/athulrr4/Land-Price-Prediction.git
```

### 2. Open the project folder

```bash
cd Land-Price-Prediction
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Run the Jupyter Notebook

```bash
jupyter notebook
```

Open `03_land_price_prediction.ipynb` and run the cells.

## 🤖 Machine Learning Model

This project uses **Linear Regression** to learn the relationship between land area and price.

The trained model can predict the estimated price for a given land area.

Example:

- Input: 1500 square feet
- Output: Predicted land price

## 📈 Future Improvements

- Add more land price data.
- Split the dataset into training and testing sets.
- Evaluate model performance using MAE, RMSE, and R² score.
- Experiment with other machine learning algorithms.
- Build a simple web application for predictions.

## 👨‍💻 Author

**ATHUL R.R**

GitHub: [@athulrr4](https://github.com/athulrr4)

## 📄 License

This project is created for educational and learning purposes.
