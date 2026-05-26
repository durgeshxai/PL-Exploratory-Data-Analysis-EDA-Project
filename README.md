# IPL Exploratory Data Analysis (EDA) Project

## Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on the Indian Premier League (IPL) dataset using Python. The analysis helps uncover meaningful insights such as team performance, winning patterns, toss decisions, player achievements, venue analysis, and seasonal statistics.

The project uses data visualization and statistical analysis techniques to understand IPL match trends and team performances across multiple seasons.

---

# Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

# Dataset Information

The project uses two IPL datasets:

1. Matches Dataset

   * Contains overall match information such as:

     * Season
     * Teams
     * Toss winner
     * Match winner
     * Venue
     * Man of the Match
     * Winning margins

2. Deliveries Dataset

   * Contains ball-by-ball information such as:

     * Runs scored
     * Boundaries
     * Sixes
     * Innings details
     * Batsman performance

---

# Project Workflow

## Step 1: Importing Required Libraries

In the first step, all necessary Python libraries are imported for data handling and visualization.

### Libraries Used

* Pandas → Data manipulation
* NumPy → Numerical operations
* Matplotlib → Data visualization
* Seaborn → Statistical plotting

### Screenshot to Add

* Screenshot of library import section.

---

## Step 2: Reading the Dataset

The IPL datasets are loaded into Pandas DataFrames using `read_csv()`.

### Operations Performed

* Loaded matches dataset
* Loaded deliveries dataset
* Displayed dataset contents

### Screenshot to Add

* Dataset loading output
* First few rows using `.head()`

---

## Step 3: Understanding the Dataset

Basic dataset exploration is performed to understand the structure and contents.

### Analysis Performed

* Shape of dataset
* Column names
* Count of records
* Summary statistics
* Sorting values

### Functions Used

* `.shape`
* `.columns`
* `.count()`
* `.describe()`
* `.sort_values()`

### Screenshot to Add

* Dataset shape output
* Describe table
* Column names output

---

## Step 4: Data Visualization

Visualizations are created to understand IPL trends and patterns.

### Visualizations Included

* Season-wise match count
* Team performance charts
* Venue analysis
* Winning statistics
* Toss decision analysis
* Boundary analysis

### Libraries Used

* Matplotlib
* Seaborn

### Screenshot to Add

* Countplot graphs
* Bar charts
* Seasonal visualizations

---

## Step 5: Data Cleaning

Data cleaning is performed to improve dataset quality.

### Cleaning Operations

* Checked missing values
* Inspected dataset information
* Removed duplicate records

### Functions Used

* `.isna().sum()`
* `.info()`
* `.duplicated()`
* `.drop_duplicates()`

### Screenshot to Add

* Missing value output
* Duplicate removal output

---

## Step 6: Statistical Analysis

Important IPL statistics are calculated using Python.

### Analysis Performed

* Total innings played
* Total IPL seasons
* Total matches played
* Maximum winning runs
* Minimum winning runs
* Maximum wickets wins
* Minimum wickets wins

### Screenshot to Add

* Statistical outputs
* Winning margin results

---

# Questions Solved in the Project

## 1. Which season had the highest number of matches?

The analysis identifies the IPL season with the maximum matches played.

### Screenshot to Add

* Season-wise match visualization

---

## 2. Which is the most successful IPL team?

The project compares all teams based on total match wins.

### Screenshot to Add

* Team win comparison chart

---

## 3. Top Players of Winning Matches

The analysis identifies players who frequently won the “Man of the Match” award.

### Screenshot to Add

* Top players graph

---

## 4. Matches According to Venue

Venue-wise match distribution analysis is performed.

### Screenshot to Add

* Venue count chart

---

## 5. Number of Matches Played by Each Team

The project calculates how many matches each team played.

### Screenshot to Add

* Team match count visualization

---

## 6. Winners in Each IPL Season

Season-wise IPL winners are identified.

### Screenshot to Add

* Winners table or chart

---

## 7. IPL Finals Venues and Winners

The analysis shows final match venues and winning teams.

### Screenshot to Add

* Finals analysis output

---

## 8. Number of Seasons Won by Each Team

The project identifies the teams with the highest IPL titles.

### Screenshot to Add

* Championship count graph

---

## 9. Toss Winner vs Match Winner Analysis

The project analyzes whether winning the toss affects match results.

### Screenshot to Add

* Toss decision visualization

---

## 10. Man of the Match Analysis

The project identifies players with the highest awards.

### Screenshot to Add

* Man of the Match chart

---

## 11. Toss Decision Analysis

The project analyzes whether teams preferred batting or fielding after winning the toss.

### Screenshot to Add

* Toss decision countplot

---

## 12. Probability of Winning After Toss Win

The probability of winning after securing the toss is calculated.

### Screenshot to Add

* Probability output

---

## 13. Total Runs from Fours by Teams

The project calculates:

* Total fours hit
* Total runs scored from boundaries

### Screenshot to Add

* Boundary analysis chart

---

## 14. Players with Most Fours

The analysis identifies players who hit the highest number of fours.

### Screenshot to Add

* Top batsmen visualization

---

## 15. Number of Fours Hit Each Season

Season-wise boundary analysis is performed.

### Screenshot to Add

* Seasonal fours chart

---

## 16. Total Runs from Sixes by Teams

The project calculates:

* Total sixes hit
* Total runs scored through sixes

### Screenshot to Add

* Six analysis chart

---

## 17. Number of Sixes Hit Each Season

The analysis identifies six-hitting trends across seasons.

### Screenshot to Add

* Seasonal sixes visualization

---

## 18. Top 10 Leading Run Scorers in IPL

The project identifies the highest run scorers in IPL history.

### Screenshot to Add

* Top run scorers chart

---

# Conclusion

This IPL EDA project successfully analyzes historical IPL data to uncover meaningful insights regarding:

* Team performance
* Match-winning strategies
* Toss impact
* Venue analysis
* Player achievements
* Boundary statistics
* Seasonal trends

The project demonstrates strong skills in:

* Data cleaning
* Data visualization
* Exploratory Data Analysis
* Statistical analysis
* Python programming

---

# Folder Structure

```bash
IPL-EDA-Project/
│
├── data/
│   ├── matches.csv
│   └── deliveries.csv
│
├── screenshots/
│   ├── season_analysis.png
│   ├── team_wins.png
│   ├── toss_analysis.png
│   └── top_players.png
│
├── IPL_EDA_Project.ipynb
├── README.md
└── requirements.txt
```

---

# How to Run the Project

## Step 1

Clone the repository:

```bash
git clone <your-github-repository-link>
```

## Step 2

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

## Step 3

Open Jupyter Notebook:

```bash
jupyter notebook
```

## Step 4

Run the notebook cell by cell.

---

# Future Improvements

* Create an interactive dashboard using Power BI or Tableau
* Build machine learning models for match prediction
* Deploy the project using Streamlit
* Add advanced player performance analytics

---

# Author

## Durgesh Mitha

* MSc in Big Data Analytics
* Data Science Enthusiast
* Python & Machine Learning Learner

