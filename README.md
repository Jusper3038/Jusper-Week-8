# Jusper-Week-8
#  COVID-19 Global Data Tracker

This project provides an interactive data analysis notebook that explores global COVID-19 trends using real-world data.

##  Project Structure

.
├── COVID19_Data_Tracker.ipynb # Jupyter Notebook with analysis and visualizations
├── COVID.csv # Input dataset (not included in this repo, see below)
└── README.md # Project documentation

markdown
Copy
Edit

##  What’s Inside

The notebook includes:

- Data Loading & Cleaning
- Visualizations:
  - Top 10 countries by total cases
  - Total deaths in top countries
  - Total tests conducted
  - Death rate analysis (deaths / cases)

##  Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
Install the required libraries:

bash
Copy
Edit
pip install pandas matplotlib seaborn
Add the dataset:

Place your COVID.csv file in the project directory. The file should include at least the following columns:

country

Cases

Deaths

Tests

Recovered

population

continent

day (date column)

Run the notebook:

Open COVID19_Data_Tracker.ipynb using JupyterLab or VS Code and run each cell.

 Notes
The dataset is not included in the repository. Make sure to provide your own COVID.csv.
