# Final Project: State Crime

## Data Source(s)

- The following website was given as a potential site to obtain a topic from
[CORGIS Datasets Project](https://corgis-edu.github.io/corgis/csv/)
- I like to watch crime shows and try to solve them so I decided to do my project on State Crime with the data from 
[State Crime](https://corgis-edu.github.io/corgis/csv/state_crime/)

## Data Preparation/ Cleaning

- Since this is a lot of data to look at, I decided to narrow down the year. The year ranges from 1960-2019 on this data sheet. Since I like even numbers, I decided to go with the beginning of the 21st century, the year 2000. 
- I filtered the spreadsheet rows by the year 2000. This became 52 lines of information including the District of Columbia and the United States as a whole. Thus, I had to delete these two rows.
- I went on to compare the total values in each row and found the corresponding column with the highest total values per row but only in the columns that I defined that I needed.
- I then added a new column that contained that information (the column name) and labeled that Highest_Crime. 
- I then repeated the same comparison but with the numbers instead of the values. I created a new column for that as well and labeled that Highest_Value.
- The next step was to find the highest value in the Highest_Value column and then make it print the Highest Rated Crime Total in 2000, what it was, and where it was. 


## Assumptions

- I have made an assumption that the number reads like an integer and not in thousands or tens of thousands. When looking into the data set further, each column with the rates are per 100,000 population in each area. 
- I have also made the assumption that the data rates per crime and population of each state in the year 2000 do not correlate with the total crime rates per crime.
- There is also an assumption that these crimes happen all over the state and are not broken down into certain areas of each state. Most crime might happen in one area over the rest of the state. 


## Limitations

- With my assumptions made, I may have gotten the highest crime per State completely wrong as I only used the columns of the totals per the crimes.
- I didn't consider if the population or landscape have anything to do with crime totals.