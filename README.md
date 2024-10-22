# Michele Carlin's Second Deliverable

## Repo name: 
DACSS-690R/Second_Deliverable

## File containing R code for reading in datasets: 
index.Rmd

## Datasets cleaned and formatted in repo:
1. Social Media and Mental Health 
  Cleaning
    a. Column names were very long (full question text), so I renamed the columns to short abbreviations
    b. Some recoding was needed for Gender variable
    c. A mispelling was corrected and NAs fixed in OrgAffil variable
 Formatting
    a. Nominal variables (e.g., Gender, RelStatus, OrgAffil) - created new columns that are factors
    b. Ordinal variables (e.g., AmtTime and likert scale items) - created new column AmtTime variable that is ordered factor, and coerced likert scale items to be ordered factors

2. UMassChanClerkship Grades
   Cleaning
     a. When importing, first row needed to be skipped
     b. Created new letter grade columms and recoded some values (e.g., Final_Letter2, SPE_Letter2)
     c. Cleaned numeric variables by replacing some bad characters (e.g., parentheses and commas) with NAs
   Formatting
     a. Changed all letter grade values to uppercase
     b. Changed all letter grade variables to ordered factors
