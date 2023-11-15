# PHP2550_Project2

# Introduction
Severe bronchopulmonary dysplasia (sBPD) poses a complex challenge in neonatal care, necessitating nuanced decision-making regarding tracheostomy placement. The lack of clear indications and optimal timing prompted this collaboration with Dr. Chris Schmid from the Biostatistics Department. The main aim of this project is to develop a predictive model capable of predicting the likelihood of tracheostomy based on demographic variables, birth variables and respiratory variables measured at different time points (36 and 44 weeks PMA), such that it results in potentially improving patient outcomes and informing counseling practices.

# Data Overview
The dataset originates from the BPD Collaborative Registry, a multi-center consortium of interdisciplinary BPD programs across the United States and Sweden. It includes infants with gestational age below 32 weeks and diagnosed with sBPD according to the 2001 NHLBI criteria. Standard demographic and clinical data are collected at four critical time points: birth, 36 weeks postmenstrual age (PMA), 44 weeks PMA, and discharge. The dataset, covering the period between January 1 and July 19, 2021, was queried for patients with sBPD and complete growth data. Ten BPD Collaborative centers contributed data meeting the study's inclusion criteria.

The data analyzed here contained different types of variables, and consisted of 996 observations of 30 variables. Patient ID and center number were included. The demographic variables included were maternal race and ethnicity (1 = Hispanic/Latino, 2 = Not Hispanic or Latino). The birth variables included were birth weight, obstetrical gestational age, whether the infant was small for gestational age, birth length, birth head circumference, delivery method (1 = Vaginal Delivery, 2 = Cesarean Section), whether prenatal corticosteroids were administered, whether complete prenatal steroids were administered, whether maternal chorioamnionitis was present, gender, and whether the infant received any surfactant at any point in the first 72 hours. The weight of the infant, and respiratory support variables such as ventilation support (0 = No respiratory support or supplemental oxygen, 1 = Non-invasive positive pressure, 2 = Invasive positive pressure), fraction of inspired oxygen, peak inspiratory pressure, positive end exploratory pressure, and whether medication for pulmonary hypertension was administered, were recorded at both 36 and 44 weeks. In addition, data on the infant’s gestational age at the time of discharge and whether tracheostomy (0 = No, 1 = Yes) or death had occurred at this point were recorded.

### Files

`PHP 2550_Project 2_Final.Rmd` is an R Markdown file containing the code and report pertaining to this analysis.

`PHP 2550 Project 2.pdf` is a pdf file containing the code and report pertaining to this analysis.

`PHP_2550_Project_2_Code.R` is an R script file containing the code used in this analysis.
