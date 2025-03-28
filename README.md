# Team-12-Roadmap
# Student Career Analytics Dashboard
Empowering SLU Students & Career Services with Data-Driven Insights

## Project Description
HR professionals and recruitment consultants often struggle to keep their hiring strategies in syncwith evolving market trends. They face challenges such as addressing skill shortages and offering competitive compensation to attract top talent. The Employability Analytics Application is designed to tackle these issues by providing actionable insights based on job market trends, professional profiles, salary benchmarks, and industry demand reports. With this tool, HR professionals can make better-informed decisions that not only strengthen recruitment strategies but also help align talent acquisition with their organization’s broader goals.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dashboard](#dashboard)
- [Project Structure](#project-structure)
- [Dataset Columns Description](#dataset-columns-description)
- [Authors](#authors)

## Features

### ✅ Must Have
- Skill-to-job matching
- Dedicated dashboards for Students and SLU Career Services
- Robust data validation and cleaning using R
- Centralized student data management

### ✅ Should Have
- Certification recommendations
- Detailed career pathways
- Interactive features (chat, filters, dropdowns)
- Aggregated insights for SLU Career Services

### 💡 Could Have
- OCR resume parsing
- Course recommendations
- LinkedIn profile integration
- Notifications for relevant events
- Progress tracking for students


## Installation

### Requirements
- [R](https://cran.r-project.org/)
- [RStudio](https://posit.co/download/rstudio-desktop/)
- [Tableau]

### Setup (Still in progress)
1. Clone the repository:
```bash
git clone https://github.com/CMSTeam12/student-career-dashboard.git
cd student-career-dashboard
```

2. Open RStudio and set your working directory:
```r
setwd("path/to/your/student-career-dashboard")
```

3. Install required R packages:
```r
install.packages(c("dplyr", "stringr", "readr"))
```

4. Run the data validation script:
```r
source("scripts/data_validation.R")
```

## Usage

Run data integrity validation:
```r
source("scripts/data_validation.R")
```

This script will:
- Detect missing values
- Validate categorical fields (Education, Work Mode, etc.)
- Check logical data consistency (relocation preferences)
- Print validation results in RStudio's console

## Dashboard

Explore the interactive dashboard here: [Tableau Dashboard](coming soon...)

## Project Structure
```
student-career-dashboard/
├── data/
│   └── Final_data.csv
├── scripts/
│   └── data_validation.R
├── dashboard.pbix (optional)
└── README.md
```

## Dataset Columns Description

The following columns in our data contain *Yes/No* values

- C++
- Java
- Python
- JavaScript
- R_Language
- AI_Machine_Learning
- Cloud_DevOps
- Networking_Security
- GIT
- Data_Structures_Algorithms
- Database_Management
- Data_Backup_Recovery
- Big_Data
- Operating_Systems
- Data_Analytics_Visualization
- Data_Collaboration
- Data_Governance_Quality
- Data_Science
- Cybersecurity
- Web_Development
- Business_Analyst
- Project_Management_and_Collaboration_Tools
- Enterprise_Systems
- IT_Support_Helpdesk
- IT_Security_Compliance
- Testing_Quality_Assurance
- Development_Tools

## Authors
Team 12:
- Vishal Rao Gone
- Pooja Vilekha Burujula
- Tejaswini Bathula
- Siva Rama Krishna Gutha
- Madhuri Gundapaneni

Saint Louis University
