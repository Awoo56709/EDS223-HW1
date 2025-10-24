# EDS223-HW1: Environmental Injustice in Los Angeles County

![LA County Particulate Matter](figs/la_county_part.jpg)

# Purpose
The purposes of this repository is to hold files and the analysis for EDS 223 Homework #1.

# Description


- This repository includes:
  - A git ignore that ignores the "data" files when pushed
  - A data folder that houses all the data used for the analysis
  - An RData file that houses all the data we needs for this assignment's analysis
  - An .Rhistory file that notes all the changes done to the files in the repository
  - An EDS223-HW1.Rproj file that is used to access the project from R Studio
  - An ej-screen.qmd file where the mapping and analysis take place
  - A README.md file
  - A "figs" folder with a jpg file of LA County for README.md rendering purposes.
  
# Repository Structure

EDS223-HW1

├── data/                                 
│     └── EJSCREEN_2023_BG_COLUMNS.xlsx               
│     └── EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb              
│     └── ejscreen-tech-doc-version-2-2.pdf                       
│
├── figs/                 
│     └── la_county_part.jpg                           
│                
│── .gitignore                   
│── .RData                        
│── .Rhistory                     
│── EDS223-HW1.Rproj
│
│── ej_screen.qmd
│── README.html       
└── README.md
  
# Data Access Details
  - The data for this analysis was sourced from a google drive but originally sourced from the EPA's ![EJScreen: Environmental Justice Screening and Mapping Tool](https://www.epa.gov/ejscreen)
  - This zip file was then imported into a repository in RStudio and read in
  - This data was used to visualize the potential environmental injustice related to particulate matter, cancer risk in predominately minority block groups in LA County

# Contributors
  - The contributors of this data include the ![US EPA](https://www.epa.gov/)
  
# Citation

- United States Environmental Protection Agency. “EJSCREEN: Environmental Justice Screening and Mapping Tool.” EPA, 2023, https://www.epa.gov/ejscreen. Accessed 2 Oct. 2025
