# 🌍 EcoSphereAI

EcoSphereAI is a Streamlit-based application leveraging the power of Gemini and traditional machine learning models to provide actionable insights for optimizing network infrastructure, resource allocation, and sustainability efforts.  It offers a suite of AI-powered tools designed to address various aspects of network management, from energy optimization to disaster preparedness and predictive maintenance.

## 🌟 Features

* **Interactive Dashboard:** Visualize key metrics, node locations, and regional analysis for a comprehensive overview of your network. Upload your own datasets for custom analysis.
* **AI-Powered Tools:** Leverage nine specialized AI tools, each designed for a specific task:
    * **Energy & CO₂ Optimizer:** Predicts energy usage and carbon emissions, offering optimization strategies.
    * **Maintenance Forecaster:** Predicts potential maintenance issues based on historical data and node characteristics.
    * **Disaster Assessor:** Assesses disaster risk levels based on environmental factors and infrastructure vulnerability.
    * **Traffic Forecaster:** Predicts future traffic load to inform capacity planning and resource allocation.
    * **Procurement Planner:** Optimizes procurement decisions by predicting costs, delivery times, and required quantities.
    * **Connectivity Insights:** Provides region-specific connectivity insights and recommendations.
    * **Deployment Strategist:** Plans network deployments by predicting costs and timelines.
    * **Network Node Monitor:** Monitors node performance, predicts data usage, peak usage, and downtime events.
    * **Sustainability Tracker:** Tracks and reports on key sustainability metrics, providing recommendations for improvement.
* **Gemini Integration:**  Each AI tool integrates with Google's Gemini for advanced natural language processing, providing insightful and actionable recommendations based on predictions.
* **Session Management:** Save and review past sessions for each AI tool, enabling tracking and analysis of historical predictions and insights.
* **Ticketing System:** Built-in ticketing system for reporting issues, providing feedback, and requesting support.
* **User Authentication:** Secure user login and signup functionality with password validation.
* **Customizable User Profiles:** Update user information, including full name, username, password, and avatar.


## Installation

1. Clone the repository: `git clone https://github.com/mmfarabi/EcoSphereAI.git`
2. Navigate to the project directory: `cd EcoSphereAI`
3. Install the required packages: `pip install -r requirements.txt`
4. Set up your Gemini API key:
    1. Obtain a Gemini API key from [https://ai.google.dev/gemini-api/docs/api-key](https://ai.google.dev/gemini-api/docs/api-key)
    2. Replace `"gemini_api_key"` in the code with your actual Gemini API key.
5. Run the app: `streamlit run app.py`

## Usage

1. **Login/Signup:** Create an account or log in with your credentials.
2. **Dashboard:** Explore the main dashboard for an overview of your network.
3. **AI Tools:** Navigate to the desired AI tool using the sidebar.
4. **Input Data:** Provide the required input data for the selected tool.
5. **Predict:** Click the "Predict" button to generate predictions and insights.
6. **Sessions:** Review past sessions and download data.
7. **Tickets:** Submit tickets for issues or feedback.
8. **Settings:** Manage your user profile and settings.


## Technologies Used

* **Streamlit:** For building the interactive web application.
* **Gemini:**  For advanced natural language processing and generation of insights.
* **FLAML:** For automated machine learning model training and selection.
* **Scikit-learn, XGBoost, LightGBM, CatBoost:** Machine learning libraries used for model training.
* **Pandas:** For data manipulation and analysis.
* **Joblib:** For saving and loading machine learning models.
* **Plotly, Folium, Streamlit-folium:** For data visualization.
* **Pillow:** For image processing.
* **SQLite:** For database management.
* **Other:** `numpy`, `ray[tune]`, `fsspec`


## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues.

## License

Apache License Version 2.0

