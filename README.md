# Data-Management-and-Exploratory-Data-Analysis

**Analysis of Learner Engagement and Performance in the "Cyber Security: Safety At Home, Online, and in Life" Course.**

Investigating trends in accuracy, engagement, and sentiment for improved course design and learner support.

\
**Brief Project Overview**

This project explores learner engagement, performance, and satisfaction within Newcastle University's cybersecurity course, offered through FutureLearn. Using the CRISP-DM methodology, the analysis aims to uncover insights on accuracy by team role, patterns in submission activity, and weekly sentiment trends. Findings will inform strategies for enhancing learner outcomes and course design.

\
**Repository Overview**
CyberSecurity_Analysis/
│
├── README.md                       # Main documentation for the project
│
├── documentation/                  # Project documentation files
│   ├── CyberSecurity_Project_Summary_Document.pdf
│   ├── CyberSecurity_Data_Cleaning_Plan.txt
│   └── CyberSecurity_Data_Dictionary.xlsx
│
├── data/                           # Data files used in the project
│   ├── README.txt
│   ├── cycle1_cleaned_data.csv     # Cleaned data after Cycle 1
│   └── cycle2_cleaned_data.csv     # Cleaned data after Cycle 2
│
├── analysis/                       # Analysis scripts and outputs
│   ├── README.txt                  # Instructions specific to analysis
│   ├── scripts/                    # R scripts for each stage of analysis
│   │   ├── data_preparation.R      # Data cleaning and preparation script
│   │   ├── feature_engineering.R   # Feature creation and transformation
│   │   ├── modeling.R              # Modeling and analysis script
│   │   └── visualization.R         # Visualization script
│   │
│   └── output/                     # Output files generated from analysis
│       ├── plots/                  # Plots generated during analysis
│       └── results_summary.csv     # Summary of analysis results
│
└── config/                         # Configuration files for reproducibility
└── renv.lock                   # Project-specific package versions
\

**Applicable Instructions**

Tools Required:
R and RStudio for analysis
Required R packages: dplyr, ggplot2, lubridate, ProjectTemplate
Optional: Install renv for managing package versions

\

How to Use:
Clone the repository and navigate to the project directory.
Open RStudio and set the working directory to the project root.
Run create.project() to initialize ProjectTemplate settings.
Execute each R script in the scripts/ folder in order, starting with data_preparation.R.

\
**Additional Resources**

CRISP-DM Documentation:
Overview of the CRISP-DM methodology for structuring data science projects.

\
FutureLearn Course:
FutureLearn - Cyber Security: Safety At Home, Online, and in Life - Original course page providing context for the dataset.
