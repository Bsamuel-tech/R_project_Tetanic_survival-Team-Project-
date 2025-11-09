Titanic Survival Prediction In R Programing.

A data science project analyzing the Titanic disaster to predict passenger survival and understand what factors influenced who lived and died.
📊 Project Overview
This project analyzes 891 Titanic passengers to answer:

Who was most likely to survive?
What factors mattered most?
Can we predict survival with high accuracy?

Result: 83% prediction accuracy
🚀 Quick Start
What You Need

R (version 4.0+)
RStudio

Installation

Clone this repository:

bashgit clone https://github.com/yourusername/titanic-project.git
cd titanic-project

Install required R packages:

rinstall.packages(c("tidyverse", "ggplot2", "rpart", "rpart.plot", 
                   "scales", "knitr", "kableExtra"))

Open Titanic_Analysis.Rmd in RStudio
Click "Knit" to generate the report

📁 Files
├── Titanic_Analysis.Rmd    # Main analysis (run this!)
├── styles.css              # Report styling
├── train.csv               # Training data (891 passengers)
├── test.csv                # Test data (418 passengers)
└── README.md               # This file
🔍 Key Findings

Women survived 4x more than men (74% vs 19%)
Class mattered hugely: 1st class 63%, 3rd class 24%
Small families did best: 2-4 members had 60-70% survival
Children were prioritized: Under 12 years had 58% survival

🛠️ What We Did

Cleaned the data - Fixed missing ages and cabin information
Created new features - Family size, title from names, age groups
Made visualizations - 6 professional charts showing patterns
Built 3 models - Logistic regression and decision tree
Achieved 83% accuracy - Better than baseline

📈 Models
ModelAccuracyFeatures UsedBaseline78%Class, Sex, AgeImproved83%+ Family, Title, Fare, CabinDecision Tree81%Visual decision rules
📊 Sample Visualization
Our analysis includes charts showing:

Survival rates by gender and class
Age distribution of survivors vs non-survivors
Impact of family size on survival
Fare analysis by class
And more...

👥 Team

[Your Name 1]
[Your Name 2]
[Your Name 3]
[Your Name 4]

📝 Project Details
Course: Data Science Fundamentals
Date: November 2025
Dataset: Kaggle Titanic Competition
🎯 Technologies Used

R - Statistical analysis
tidyverse - Data manipulation
ggplot2 - Visualizations
rpart - Decision trees
R Markdown - Report generation

📄 License
Educational project for academic purposes.
🤝 Contributing
This is a school project, but feel free to fork and experiment!
