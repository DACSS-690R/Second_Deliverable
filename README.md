# Michele Carlin's Second Deliverable

## Repo name: 
DACSS-690R/Second_Deliverable

## File containing R code for reading in datasets can be found here: 
[index.Rmd](https://github.com/DACSS-690R/Second_Deliverable/blob/main/index.html)

## Datasets cleaned and formatted in repo:
1. Social Media and Mental Health<br>
  CLEANING<br>
    a. Column names were very long (full question text), so I renamed the columns to short abbreviations<br>
    b. Some recoding was needed for Gender variable<br>
    c. A mispelling was corrected and NAs fixed in OrgAffil variable<br>
 FORMATTING<br>
    a. Nominal variables (e.g., Gender, RelStatus, OrgAffil) - created new columns that are factors<br>
    b. Ordinal variables (e.g., AmtTime and likert scale items) - created new column AmtTime variable that is ordered factor, and coerced likert scale items to be ordered factors<br><br>

2. UMassChanClerkship Grades<br>
   CLEANING<br>
     a. When importing, first row needed to be skipped<br>
     b. Created new letter grade columms and recoded some values (e.g., Final_Letter2, SPE_Letter2)<br>
     c. Cleaned numeric variables by replacing some bad characters (e.g., parentheses and commas) with NAs<br>
   FORMATTING<br>
     a. Changed all letter grade values to uppercase<br>
     b. Changed all letter grade variables to ordered factors<br>
