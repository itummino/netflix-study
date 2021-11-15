# [U.S. College Study](https://github.com/itummino/PortfolioProjects/blob/main/CollegeData.sql) ![image](https://user-images.githubusercontent.com/84094369/120266976-053e6400-c271-11eb-878b-386c5a803d44.png)
## *An Economic Take on College Career Paths, Post-Grad Unemployment Rates & Gender/Location Salary Differences*
![](/images/mapcollege.jpg)
### Sources/Procedure:
- Imported university post-grad salaries data from [Kaggle/Wall Street Journal](https://www.kaggle.com/wsj/college-salaries?select=salaries-by-college-type.csv)
- Imported university majors/careers 2012-2014 data from [American Community Survey](https://github.com/fivethirtyeight/data/tree/master/college-majors)
- Extracted and organized 4 different CSV spreadsheets worth of college data 
- Altered specific column names to match across different tables in order to perform various JOINs on primary keys
- Used SQL data cleaning to remove unneccessary data fields and customized queries to discover economic trends in different college types (Ivy league, Private, Public Universities) 
- Grouped together common college major categories (manipulated the datasets to view narrowed down options, too many majors on the CSVs originally)
#### 👉[Click here to view my SQL Code](https://github.com/itummino/PortfolioProjects/blob/main/CollegeData.sql)

### Points of Interest: 
- Calculated the unemployment rate for college grads based on employed/unemployed graduate numbers and created a new column to reflect the formula across every row
- Highlighted the top 5 major studies in each of the top 5 career path categories linked to the highest employment numbers (technical/scientific fields)
- College majors that have the highest average unemployment rates post-graduation (Liberal Arts studies fed this narrative unfortunately)
- Total figures of overall students employed and unemployed based on grouping by major category
- Identified male/female dominated fields and JOINed with employment data to see the correlation
- Analyzed the underrepresentation of women in STEM fields
- Compared avg starting salaries and mid-career salaries spanned across all majors and college types to see the long-term economic gain from varying academic paths 
- Created a location column based on the college name to see post-grad salaries based on different college locations (used this to create a map visualization)

### Data Visualizations:
- Created SQL views to store/condense the data in SSMS and then export into Tableau for data vizzes
- Built 2 detailed/condensed vizzes in Tableau Public for final analysis (linked below):

#### [Post-Grad Salaries Based on College Type, Location & Major](https://public.tableau.com/app/profile/isabel.tummino/viz/U_S_CollegeStudy/Dashboard1)
#### [Career Paths, Gender Differences, Unemployment Rates](https://public.tableau.com/app/profile/isabel.tummino/viz/U_S_CollegeStudy-CareerPathsGenderDifferencesUnemploymentRates/Dashboard1)
