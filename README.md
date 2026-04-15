# 📊 Student Performance Dashboard

A comprehensive, interactive web application designed to monitor and analyze student academic performance across multiple years (2023, 2024, and 2025). Built with Python, Streamlit, Pandas, and Plotly.

## 🌟 Features

- **Multi-Year Analysis**: Seamlessly aggregates data from multiple CSV/Excel sheets across different academic years to provide long-term insights.
- **Dynamic Filtering Engine**: Sidebar filters allow slicing data by specific Year, School, and Individual Student.
- **High-Level KPIs**: View quick metrics like Average Score, Highest Score, Lowest Score, and Total Students.
- **Rich Visualizations (Powered by Plotly)**:
  - **Score Distribution**: Histogram with box plots to visualize the spread of scores.
  - **Class-wise & School-wise Analysis**: Bar charts analyzing performance grouped by classes and schools.
  - **Age Group Demographics**: Pie charts showcasing prominent student age groups.
- **Individual Student Journeys**: Select a specific student to see their individual performance trend over the years, mapped against the class average.
- **Automated AI-like Insights**: Generates automated text insights on student performance (e.g., "Trending Up", "Exceeding Expectations").

## 🛠️ Tech Stack

- **[Streamlit](https://streamlit.io/)**: For processing the data into a fully interactive web interface quickly.
- **[Pandas](https://pandas.pydata.org/)**: For robust data ingestion, cleaning, transforming, and calculating metrics.
- **[Plotly Express](https://plotly.com/python/plotly-express/)**: For generating interactive, beautiful, and responsive charts.

## 📂 Project Structure

```text
dataAnalysis/
├── data/
│   ├── SOSResults2023.csv  (or .xlsx)
│   ├── SOSResults2024.csv  (or .xlsx)
│   └── SOSResults2025.csv  (or .xlsx)
├── dashboard.py            # Main application script
├── requirements.txt        # Project dependencies
└── README.md               # Project documentation

Here are the exact commands you need. You can copy and paste them into your terminal one by one:

Step 1: Install the requirements

pip install -r requirements.txt

Step 2: Run the dashboard

streamlit run dashboard.py

