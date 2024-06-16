# Trends-in-the-Movie-Industry-using-Tableau
#### Table of Contents
- [Overview](#overview)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Research Questions](#research-questions)
- [Findings](#findings)
- [Limitations](#limitations)
- [Future Work](#future-work)
  
#### Overview
The "Trends in the Movie Industry" dashboard project analyses and visualizes various factors affecting the movie industry over time. The project utilises data from 1980 to 2022 and aims to help stakeholders understand the evolution of the industry and make informed decisions.

#### Objectives
- Analyze trends: This dashboard helps to examine and analyze trends using key metrics like budget, movie genre, gross earnings, IMDB score etc
- Identify relationships: This project aims to identify the relationships among different variables.
- Preferences: It will also analyze how the user preferences have changed over time based on various factors.
   
#### Dataset
The dataset for this project has been obtained from Kaggle.
- [Download](https://www.kaggle.com/datasets/danielgrijalvas/movies/data)
- The key variables of the data are:
   - Movie Name
   - Movie Rating
   - Movie Genre
   - Release Year
   - Release Date
   - Movie Score
   - Number of Votes
   - Director
   - Writer
   - Star
   - Country
   - Budget
   - Gross Earnings
   - Company
   - Movie Runtime
- The dataset contains 7669 unique entries from 1980 to 2022.
  
#### Methodology
- #### Data Cleaning:
  There are some missing values in the data. Instead of having those spaces have a value of 0, we just set them as null cells, so they would not impact measurements such as mean.
  
- #### Extracting Month column:
  The data consisted the release date of the movie in the form of month, day and year. So, to get only the release month, we created a new column using flash fill tool of Excel.
  
- #### Visualizatio tools:
  Used tableau to construct visualizations. The various visualizations used in this project include Bubble charts, Bar charts, Pie charts, Line charts, Circle views, Scatterplot, Comparison charts.

- #### Assumptions:
  Throughout this project, we used project votes to represent trends in the number of movie watchers. It was an assumption we made that they would follow the same trends.

#### Research Questions
1) Overall, what has been the evolution of the movie industry, specifically in measured values such as budget, gross earnings, viewership, and runtime?

2) What is the relationship between movie budget and movie gross? Does that relationship change when adding genre as an additional factor?

3) Which movie stars are most likely to result in a high grossing movie?

4) Is there a relationship between how many viewers a movie is getting and the movie rating? How has views for each rating changed over time?

5) Is there a time during the year that people are more likely to go to a theater to watch a movie? What are some explanations for these results?

#### Findings
1) Evolution: Both the budget and gross earnings are increasing overtime. The gross earnings are raising more rapidly.
2) Genre Impact:  Genres like animation and family movies having a much larger gap between the movie budget and its gross earnings.
3) Star Impact: Stars certainly had some impact on the movie warnings. But this is not only a single factor influencing the movie earnings.
4) Viewership and Movie ratings:  G rated movies had drastic changes in viewership.
5) Seasinal trends: The months with the most movie viewership are the summer months of May, June, and July as well as the winter months around Thanksgiving and Christmas in November and December.
   
#### Limitations
#### Future Work
