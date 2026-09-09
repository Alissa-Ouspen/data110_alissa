###What goes where

Data Folder
 raw/ → original data (do not modify)
 processed/ → final datasets used for analysis
Ingestion Folder
 Loading and cleaning data
 Example:
  -Reading CSV files/Fixing missing values
  
EDA (Exploratory Data Analysis)
 Graphs, summaries, early insights
 Example:
  -Histograms/Correlation plots
  
Analysis Folder
 Final modeling and results
 Example:
o Statistical models/Machine learning

Models Folder
 Saved models or outputs
Reports Folder
 Presentations and final deliverables
 Includes:
o Project plan
o Final report

###Where Your Code Goes (IMPORTANT)
Put your .qmd , .Rmd or .ipynb files in:
ingestion/notebooks/
eda/notebooks/
analysis/notebooks/
Scripts (Reusable Code)
Put .R or .py files in: scripts/ [inside the appropriate section (ingestion, eda, or analysis)]

###Naming Convention
Use clear, consistent file names:
1.0-initial-data-cleaning.qmd
1.1-eda-summary.ipynb
2.0-final-model.R
Format: [number]-[short-description]

Best Practices
 Do NOT modify files in data/raw/
 Keep your folders organized at all times
 Write clear file names (no random names like “final_final_v2”)
 Add comments in your code
 Push your work regularly (you will learn this next)

