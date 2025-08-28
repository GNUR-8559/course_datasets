# GNUR 8559 Datasets
This public repository makes it easier for students to access datasets we will be using for analysis in this course. 

Use the example code below to read a dataset from a GitHub URL in R:

```r
library(readr)

url <- "https://github.com/GNUR-8559/course_datasets/raw/main/SBP.csv"

# Read CSV directly from the URL
df <- read_csv(url)

head(df)
