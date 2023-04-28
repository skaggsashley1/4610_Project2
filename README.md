# Movie Industry

## Group Name and Members

Group 21482_ 6

[Aaron Fritchley]

[Mason Layfield]

[Alexandra Shalikashvili]

[Simran Singh]

[Ashley Skaggs](https://github.com/skaggsashley1/4610_Project2)

## Dataset Information 

The dataset [‘Movie Industry’](https://www.kaggle.com/datasets/danielgrijalvas/movies) was obtained from the website Kaggle and contains 6820 movies with 15 attributes. The creator’s purpose of the dataset was to evaluate if the movie industry is dying out at a time when streaming giants like Netflix have become more popular. The dataset contains information about movies released over a span of four decades. The main content of the dataset includes information related to each movie’s name, budget, company, country, director, genre, gross revenue, rating, release date, runtime, score, votes, star, writer, and year of release. The purpose of the dataset is to show movie revenue and analyze the many factors that impact it. Each movie has the following attributes: <br />
| Column Name                  | Data Type                 |
| ---------------------------- | ------------------------- |
| Budget                       | Decimal                   |
| Company (production company) | String                    |
| Country                      | String                    |
| Director                     | String                    |
| Genre                        | String                    |
| Gross                        | Decimal                   |
| Name                         | String                    |
| Rating (R, PG, etc.)         | String                    |
| Released Date                | String                    |
| Runtime                      | Decimal                   |
| Score                        | Decimal                   |
| Votes                        | Decimal                   |
| Star                         | String                    |
| Writer                       | String                    |
| Year                         | Decimal (changed to Date) |

## Questions

**Question 1**<br />
For action comedy and horror movies, what is the correlation between runtime and the movie’s score from 2000 to 2009 compared to 2010 to 2019? <br />

**Explanation:** This question is culturally significant in detailing how attention spans have changed over the last decade across different genres. Each movie has a designated run time and also was assigned a score out of 10 from IMDB. This information can be cross-referenced when projecting future optimal runtimes<br />

**Question 2**<br />
How many movies have the countries with the highest average movie industry net income produced from 2010-2020? <br />

**Explanation:** This question is economically significant in showing what countries produced the most movies compared to their net income. This could also show which countries have the most net income per movie but produced few movies compared to countries that produced the most movies but also have high net income. We were able to create a calculated field from each movie's budget and gross revenue to build a heat map showing the highest average net income by country. We then used this information to select the top 5 highest net-income nations to construct a bar graph showcasing the number of movies produced by that countries. <br />


## Manipulations to Data
Some of the values for the budget attribute were null due to the data not being available for those movies. We decided to remove these values via a filter on the whole dataset so it would not interfere with our visualizations. We also decided to create a calculated field called net by subtracting the budget from the gross for each movie. This was done to show how much each movie made so we could then create a heat map to compare how much each country made in net income on average.


## Analysis and Results

