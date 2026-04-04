# SpaceX Falcon 9 First Stage Landing Prediction
!imag:[]

## 🚀 Project Overview

This project predicts the success of SpaceX Falcon 9 first-stage landings. By analyzing historical launch data, geographical factors, and technical specifications, we developed a machine learning pipeline capable of determining if a booster will successfully land, potentially saving SpaceX up to $30 million per launch.

## 📊 Key Features

#### 1.Data Collection: Automated data retrieval via SpaceX API and web scraping of Wikipedia.

#### 2. EDA with SQL: Deep-dive analysis into payload trends and mission outcomes using SQLite.

#### 3. Interactive Visualizations: * Folium Maps: Geospatial analysis of launch site proximities to coastlines and infrastructure.

#### 4. Plotly Dash: A real-time dashboard for filtering success rates by site and payload mass.

#### 5.Predictive Modeling: Comparison of Logistic Regression, SVM, Decision Tree, and KNN models to identify the most accurate classifier.

## 🛠️ Tech Stack
  1. Languages: Python 3.x
  2. Libraries: Pandas, NumPy, Matplotlib, Seaborn, Folium, Scikit-learn
  3. Dashboarding: Plotly, Dash
  4. Database: SQL (SQLite)
  5. Tools: VS Code, Jupyter Notebooks

## 📈 Methodology & Results
  1. Exploratory Data Analysis (EDA): Discovered that success rates have increased over time, correlating strongly with "Flight Number."

  2. Geospatial Analysis: Confirmed all launch sites are located near coastlines to maximize landing safety.

  3. Model Performance: * The Logistic Regression, SVM, and KNN models all achieved a test accuracy of 83.3%.

  4. The Decision Tree model showed signs of overfitting with a lower test accuracy of 77.8%.

## 💻 How to Run the Dashboard

  1. Clone the repository.
     
  2. Install dependencies: pip install dash pandas plotly.
     
  3. Run the application: python spacex_dash_app.py.
     
  4. Access via your browser at http://127.0.0.1:8050/.

## 📌 Conclusion

The project successfully demonstrates that booster landing success is not random but predictable based on payload weight, launch site, and historical experience. This tool provides a framework for evaluating the financial and operational risks of future orbital missions.









