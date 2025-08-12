🏠 PropIntel – AI-Powered Gurugram Real Estate Analytics, Price Prediction & Recommendation

PropIntel is an AI-powered real estate platform that combines market analytics, price prediction, and personalized property recommendations into a single, user-friendly application.
It collects Gurugram real estate listings via web scraping from 99acres.com, processes and analyzes the data, and delivers insights and predictions through an interactive Streamlit dashboard.

🚀 Features

📊 Analytics Dashboard

Spatial visualizations of property distribution and market trends in Gurugram

Word clouds showcasing location highlights and amenities

Scatter, box, and pie charts to explore pricing patterns

Comparative analysis across localities, property types, and facilities in Gurugram

💰 Price Predictor

Regression-based ML model trained on cleaned Gurugram property datasets

Predicts prices based on location, area (sq. ft.), bedrooms/bathrooms, property type, and facilities

🏡 Property Recommender

Content-based recommendation system with location and radius filters within Gurugram

Price range matching for budget-oriented searches

Facility-based scoring (e.g., swimming pool, parking, security)

Personalized property suggestions for buyers and investors in Gurugram

🛠 Tech Stack

Languages & Libraries:
Python, Pandas, Numpy, Matplotlib, Seaborn, Plotly, Scikit-learn, Streamlit, BeautifulSoup, Requests

Tools:
Jupyter Notebook, Git, GitHub

📂 Project Structure

bash
Copy
Edit
PropIntel/
│── data/              # Raw & cleaned Gurugram datasets
│── notebooks/         # Jupyter notebooks for analysis
│── models/            # Trained ML models
│── Pages/             # Frontend pages and visualizations
│── scripts/           # Web scraping and preprocessing scripts
│── app.py             # Main Streamlit application
│── requirements.txt   # Dependencies
└── README.md
⚙️ Installation & Setup

Clone the repository

bash
Copy
Edit
git clone https://github.com/Sourav07-D/PropIntel.git
cd "PropIntel – AI-Powered Gurugram Real Estate Analytics & Price Prediction"
Create a virtual environment

bash
Copy
Edit
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the Streamlit app

bash
Copy
Edit
streamlit run app.py
💡 Example Insights (Gurugram)

Analytics: Identify localities in Gurugram with the highest price growth over the past year

Prediction: Estimate the price of a 3BHK flat in DLF Phase 3, Gurugram with parking and swimming pool

Recommendation: Discover properties under ₹80 lakhs within 5 km of Cyber Hub, Gurugram

📈 Model Details

Algorithms Used: Linear Regression, Random Forest, XGBoost (best performing model selected)

Evaluation Metrics: R² Score, MAE, RMSE

Recommendation System: Content-based filtering using property features and location proximity within Gurugram

🤝 Contributing

Fork this repository

Create your feature branch

bash
Copy
Edit
git checkout -b feature/AmazingFeature
Commit changes

bash
Copy
Edit
git commit -m "Add amazing feature"
Push to branch

bash
Copy
Edit
git push origin feature/AmazingFeature
Open a Pull Request

📬 Contact
Author: Sourav Das
LinkedIn: linkedin.com/in/sourav-das-654234248
GitHub: github.com/Sourav07-D
