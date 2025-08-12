🏠 PropIntel – AI-Powered Real Estate Analytics, Price Prediction & Recommendation

PropIntel is an AI-powered real estate platform that combines market analytics, price prediction, and personalized property recommendations into a single user-friendly application.
The system collects real estate listings through web scraping from 99acres.com, processes and analyzes the data, and provides insights and predictions via an interactive Streamlit dashboard.

Overview of Features

Analytics Dashboard

Spatial visualizations of property distribution and trends

Word clouds for location highlights and amenities

Scatter, box, and pie charts for exploring price patterns

Comparative analysis across locations, property types, and amenities

Price Predictor

Regression-based ML model trained on cleaned property data

Predicts property prices based on location, area (sq. ft.), number of bedrooms/bathrooms, property type, and facilities

Property Recommender

Content-based recommendation system with location and radius filters

Price range matching

Facility-based scoring (swimming pool, parking, security)

Personalized suggestions for buyers and investors

Tech Stack

Languages and Libraries:
Python, Pandas, Numpy, Matplotlib, Seaborn, Plotly, Scikit-learn, Streamlit, BeautifulSoup, Requests

Tools:
Jupyter Notebook, Git, GitHub

Project Structure

PropIntel/
data/ Raw & cleaned datasets
notebooks/ Jupyter notebooks for analysis
models/ Trained ML models
Pages/ Frontend pages / visualizations
scripts/ Web scraping and preprocessing scripts
app.py Main Streamlit application
requirements.txt Dependencies
README.md

Installation & Setup

Clone the repository
git clone https://github.com/Sourav07-D/PropIntel.git
cd "PropIntel – AI-Powered Real Estate Analytics & Price Prediction"

Create a virtual environment
python -m venv venv
source venv/bin/activate (Windows: venv\Scripts\activate)

Install dependencies
pip install -r requirements.txt

Run the Streamlit app
streamlit run app.py

Example Insights

Analytics: Identify cities with the highest price growth in the last year

Prediction: Estimate the price of a 3BHK flat in Kolkata with parking and swimming pool

Recommendation: Find properties under ₹80 lakhs within 5 km of Salt Lake, Kolkata

Model Details

Algorithm Used: Regression (Linear Regression, Random Forest, XGBoost – best performing model selected)
Evaluation Metrics: R² Score, MAE, RMSE
Recommendation System: Content-based filtering using property features and location proximity

Contributing

Fork this repository

Create your feature branch: git checkout -b feature/AmazingFeature

Commit changes: git commit -m "Add amazing feature"

Push to branch: git push origin feature/AmazingFeature

Open a Pull Request

License

This project is licensed under the MIT License

Contact

Author: Sourav Das
LinkedIn: linkedin.com/in/sourav-das-654234248
GitHub: github.com/Sourav07-D

If you want, I can also make this GitHub portfolio-optimized with bold titles, emojis, and maybe even a dashboard screenshot so it catches attention in seconds. That would make it recruiter-friendly.

Do you want me to prepare that version next?









Ask ChatGPT
