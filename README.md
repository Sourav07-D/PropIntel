🏠 PropIntel – AI-Powered Real Estate Analytics, Price Prediction & Recommendation

PropIntel is an AI-powered real estate platform that combines market analytics, price prediction, and personalized property recommendations into a single, user-friendly application.
It collects real estate listings via web scraping from 99acres.com, processes and analyzes the data, and delivers insights and predictions through an interactive Streamlit dashboard.

🚀 Features

📊 Analytics Dashboard

Spatial visualizations of property distribution and market trends

Word clouds showcasing location highlights and amenities

Scatter, box, and pie charts to explore pricing patterns

Comparative analysis across locations, property types, and facilities

💰 Price Predictor

Regression-based ML model trained on cleaned property datasets

Predicts prices based on location, area (sq. ft.), bedrooms/bathrooms, property type, and facilities

🏡 Property Recommender

Content-based recommendation system with location and radius filters

Price range matching for budget-oriented searches

Facility-based scoring (e.g., swimming pool, parking, security)

Personalized property suggestions for buyers and investors

🛠 Tech Stack

Languages & Libraries:
Python, Pandas, Numpy, Matplotlib, Seaborn, Plotly, Scikit-learn, Streamlit, BeautifulSoup, Requests

Tools:
Jupyter Notebook, Git, GitHub

📂 Project Structure

PropIntel/
│── data/ Raw & cleaned datasets
│── notebooks/ Jupyter notebooks for analysis
│── models/ Trained ML models
│── Pages/ Frontend pages and visualizations
│── scripts/ Web scraping and preprocessing scripts
│── app.py Main Streamlit application
│── requirements.txt Dependencies
└── README.md

⚙️ Installation & Setup

1 Clone the repository
git clone https://github.com/Sourav07-D/PropIntel.git
cd "PropIntel – AI-Powered Real Estate Analytics & Price Prediction"

2 Create a virtual environment
python -m venv venv
source venv/bin/activate (Windows: venv\Scripts\activate)

3 Install dependencies
pip install -r requirements.txt

4 Run the Streamlit app
streamlit run app.py

💡 Example Insights

Analytics: Identify cities with the highest price growth over the past year

Prediction: Estimate the price of a 3BHK flat in Kolkata with parking and swimming pool

Recommendation: Discover properties under ₹80 lakhs within 5 km of Salt Lake, Kolkata

📈 Model Details

Algorithms Used: Linear Regression, Random Forest, XGBoost (best performing model selected)
Evaluation Metrics: R² Score, MAE, RMSE
Recommendation System: Content-based filtering using property features and location proximity

🤝 Contributing

1 Fork this repository
2 Create your feature branch
git checkout -b feature/AmazingFeature
3 Commit changes
git commit -m "Add amazing feature"
4 Push to branch
git push origin feature/AmazingFeature
5 Open a Pull Request

📬 Contact

Author: Sourav Das
LinkedIn: linkedin.com/in/sourav-das-654234248
GitHub: github.com/Sourav07-D
