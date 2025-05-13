# Global-Covid-19-Tracker

# 📌 Overview
This project analyzes global COVID-19 data, including:
✔ Cases & Deaths (total and daily trends)
✔ Vaccination Progress (by country)
✔ Death Rates & Case Density (per million population)
✔ Interactive Choropleth Maps (global visualization)

Built with Python (pandas, matplotlib, seaborn, plotly).

# 🚀 Installation & Setup
1. Clone the Repository
git clone https://github.com/yourusername/covid-19-tracker.git  
cd covid-19-tracker  
2. Install Dependencies
   pandas>=1.3.0
   numpy>=1.21.0
   matplotlib>=3.4.0
   seaborn>=0.11.0
   plotly>=5.0.0
   jupyter>=1.0.0
3. Run the Analysis
Open in Jupyter Notebook/Lab
Execute all cells (Kernel > Restart & Run All)
(Alternatively, run as a Python script if adapted.)

#📊 Key Features
1. Data Cleaning & Preprocessing
Filters country-level data (excludes continents/income groups)
Handles missing values via forward-filling
Computes derived metrics:
Death Rate (total_deaths / total_cases)
Cases per Million ((total_cases / population) * 1e6)
Vaccination Rate (people_vaccinated / population)

2. Exploratory Data Analysis (EDA)
Time-series trends for cases, deaths, and vaccinations
Comparative analysis across countries (US, India, Brazil, UK, Kenya, South Africa)
7-day moving averages for smoothing daily fluctuations

3. Interactive Visualizations
Line charts (Matplotlib/Seaborn)
Bar plots (death rates, vaccination progress)
Choropleth maps (Plotly) for global case/vaccination distribution

#🛠️ Dependencies
Package	& Purpose
pandas - Data manipulation
numpy	- Numerical operations
matplotlib -	Static visualizations
seaborn	- Enhanced statistical plots
plotly	- Interactive maps/charts
jupyter	- Notebook environment

#📜 License
This project is licensed under the MIT License.

#📬 Contact
For questions or improvements:
Email: calmikew@gmail.com
GitHub: @CodeWithCal-W




   


