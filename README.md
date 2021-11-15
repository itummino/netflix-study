# [Netflix Study](https://github.com/itummino/PortfolioProjects/blob/main/NetflixData.sql) 
## *The Evolution of Netflix Originals - Movies Edition*
![image](/images/smallnetflix.jpg)


### Sources/Procedure:
- Imported Netflix original movies and IMDB ratings data from 2014-2021 into one CSV from [Kaggle](https://www.kaggle.com/luiscorter/netflix-original-films-imdb-scores) which was downloaded from this [Wikipedia source](https://en.wikipedia.org/wiki/Lists_of_Netflix_original_films)
- Used SQL data cleaning to remove unneccessary data fields, and removed data that was collected at the end of 2014 and the current year (2021) that had incomplete data to achieve consistency
- Wrote a series of CASE statements to group together common movie genres into more broad categories (manipulated the datasets to view narrowed down options, there were too many similar movie genres on the original dataset) and created a new table to reflect the grouped genres after testing results with a CTE table
- Created a new column that divides movie ratings into 4 different performance categories based on a CASE statement, so that I could use this to group together weak/strong ratings that correlate with genres
#### 👉[Click here to view my SQL Code](https://github.com/itummino/PortfolioProjects/blob/main/NetflixData.sql)

### Points of Interest: 
- Calculated how many Netflix original movies have received poor ratings (less than 3 stars) from 2015-2020 and also the latter to find the highest reviews
- Analyzed how many bad/average/good/great reviews there were for each movie genre, and compared the data by year to see the progression and volume over time
- Discovered that since 2015, Netflix has greatly expanded their genre selection for their originals and there have been increasingly higher overall reviews
- Calculated the average rating per genre, as well as the max(highest) and min(lowest) rating of all time
- Used a filter on the years I extracted from the Release Date to navigate through movie trends over time (created a year splitter in Power BI)

### Data Visualizations:
- Created SQL views to store/condense the data in SSMS and then exported into Microsoft Power BI and Tableau for data visualization as final analysis (linked below):

[Power BI - Netflix Study](https://app.powerbi.com/reportEmbed?reportId=e1e8cc0d-89df-456a-8363-a5adab85367e&autoAuth=true&ctid=2c94bed6-d675-4d3d-a53b-7b461fd6acc2&config=eyJjbHVzdGVyVXJsIjoiaHR0cHM6Ly93YWJpLXVzLW5vcnRoLWNlbnRyYWwtcmVkaXJlY3QuYW5hbHlzaXMud2luZG93cy5uZXQvIn0%3D)
- If you do not have a Microsoft Power BI account or are unable to view the above link (access issue) here is a non-interactive lower quality PDF of the dashboard that you can view:
#### [Power BI - Netflix Study](https://raw.githubusercontent.com/itummino/PortfolioProjects/main/images/Nextflix%20Study.PNG)

[Tableau - Netflix Study](https://public.tableau.com/app/profile/isabel.tummino/viz/NetflixStudy/Dashboard1)
