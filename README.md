# COVID-19 Global Data Tracker

## Description
The COVID-19 Global Data Tracker is a data analysis project that explores global COVID-19 trends using the Our World in Data dataset. It analyzes cases, deaths, recoveries, and vaccinations across countries, providing visualizations and insights through a Jupyter Notebook. The project includes time trend analysis, country comparisons, and a choropleth map to visualize global case distribution.

## Objectives
- Import and clean COVID-19 global data.
- Analyze time trends for cases, deaths, and vaccinations.
- Compare metrics across countries (e.g., Kenya, USA, India).
- Visualize trends using line charts, bar charts, and a choropleth map.
- Summarize findings in a well-documented Jupyter Notebook.

## Tools and Libraries
- **Jupyter Notebook**: For interactive data analysis and visualization.
- **Python Libraries**:
  - `pandas`: Data manipulation and cleaning.
  - `matplotlib`: Plotting line and bar charts.
  - `seaborn`: Enhanced visualization styling.
  - `plotly.express`: Interactive choropleth map.
- **Dataset**: Our World in Data COVID-19 dataset (`owid-covid-data.csv`).

## How to Run/View the Project
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/<your-username>/covid-19-global-data-tracker.git
   cd covid-19-global-data-tracker


Install Dependencies:Ensure Python 3.8+ is installed. Install required libraries using pip:
pip install pandas matplotlib seaborn plotly


Download the Dataset:

Download owid-covid-data.csv from Our World in Data.
Place the file in the project directory.


Run the Jupyter Notebook:Launch Jupyter Notebook:
jupyter notebook

Open covid_data_tracker.ipynb in the browser and run all cells to view the analysis and visualizations.

View Results:

The notebook contains code, visualizations, and markdown cells with insights.
To export as PDF, use Jupyter's "File > Download as > PDF via LaTeX" (requires LaTeX installed).



Insights and Reflections

Data Challenges: Missing vaccination data for some countries posed challenges, requiring careful handling (e.g., filling with zeros).
Key Findings: The United States showed the highest case growth, while India led in vaccination rollout speed. Kenya's early stabilization of death rates suggests effective containment.
Visualization Impact: The choropleth map effectively highlighted global case disparities, making complex data accessible.
Reflection: This project underscored the importance of data cleaning and the power of visualizations in storytelling. Future iterations could incorporate real-time API data or additional metrics like hospitalization rates.


