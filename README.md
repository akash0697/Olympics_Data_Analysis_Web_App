# Olympics_Data_Analysis_Web_App
# Olympics Data Analysis Web App

This is a **Streamlit-based web application** for analyzing Olympic Games data, providing insights on medal tallies, country-wise and athlete-wise performance, and overall trends.

## Features
- **Medal Tally:** View Olympic medal counts filtered by year and country.
- **Overall Analysis:** Explore statistics on Olympic editions, host cities, sports, events, participating nations, and athletes.
- **Country-wise Analysis:** Analyze medal trends, top athletes, and dominant sports for a specific country.
- **Athlete-wise Analysis:** Study age distributions, height vs. weight correlations, and gender participation trends.

## Tech Stack
- **Python** (Data Processing & Analysis)
- **Pandas** (Data Manipulation)
- **Matplotlib & Seaborn** (Visualizations)
- **Plotly** (Interactive Graphs)
- **Streamlit** (Web App Framework)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/olympics-analysis.git
   cd olympics-analysis
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   streamlit run app.py
   ```

## Dataset
The application uses **athlete_events.csv** and **noc_regions.csv** datasets for analysis. Ensure these files are in the project directory before running the app.

## Functionality Overview
- Uses a **preprocessing module** (`preprocessor.py`) to clean and merge data.
- Implements a **helper module** (`helper.py`) for specific data analysis functions.
- Utilizes **interactive visualizations** (heatmaps, line charts, and scatter plots) for deeper insights.

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License.



