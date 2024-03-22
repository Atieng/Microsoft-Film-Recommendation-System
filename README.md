### MICROSOFT FILM ANALYSIS


![alt text](Poster.jpg)

### Project Overview
This analysis is for Microsoft and they want me to use this analysis to generate insights for the business stakeholder

### Business Problem
Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.This analysis will answer the following questions:

- Which is the most watched movie genre ?
- Which movie genres have the most votes?
- Which movie genres are doing the best at the boxoffice putting in consideration the Domestic gross and WorldWide gross

### Data Understanding
1.**Source of Data**

For the analysis I will be using movie datasets from:
- [Box Office Mojo](https://www.boxofficemojo.com)
- [IMDB](https://www.imdb.com/)
- [TheMovieDB](https://www.themoviedb.org/)
- [The numbers](https://www.the-numbers.com/)
- [Rotten Tomatoes](https://www.rottentomatoes.com/)



Because it was collected from various locations, the different files have different formats. 
2.**Description f data**

Some are compressed CSV (comma-separated values) or TSV (tab-separated values) files that can be opened using spreadsheet software
or pd.read_csv, while the data from IMDB is located in a SQLite database.This is the ERD for the
IMBD data as shown below

![movie data erd](https://raw.githubusercontent.com/learn-co-curriculum/dsc-phase-1-project-v2-4/master/movie_data_erd.jpeg)

3. **Visualizations results**

These shows the most watched movie genres
![alt text](image.png)


These shows movie genre according to the most votes from movie fans
![alt text](image-1.png)

This shows that that production budget has a high positive correlation with worldwide gross hence a high budgeted movie genre is likey to be highly profitable

![alt text](image-4.png)

These shows the most profitable movie according to my analysis on the domestic gross. That will help to know which is the most profitable movie genre
![alt text](image-2.png)

This shows the most profitable genre according to my analysis on the worldwide gross
![alt text](image-3.png)

### Conclusion
#### Recommendations
1.According to the most watched genre I will recommend Microsoft to focus on Drama, Comedy,Drama|Comedy then Drama,Myestry,Suspense.Films created related to the movie genre above are likely to do well.

2.According to votes count from movie fans I will recommend microsoft to focus on 
Action,Fantasy,war and Action, Adventure,Sci-FI and Adventure,Mystery, SciFi movie genres because they are the best three movie genres with the most votes from movie fans

3.My analysis on domestic gross I have come to conclusion that Star Ep VII: The Force Awakens then the Black Panther movie are doing well at the box office, So I will recommend Microsoft to Focus on the Movie genres related to he above movies

4.My analysis on Worldwide gross Avatar,Titanic,Avengers:Infinity War,Star Ep VII: The Force Awakens are doing well at the worldwide box office.I will recommend Microsoft to Focus on the genres related to the movies above

### Future Work
#### Further Analysis
- conduct analysis on related datasets to find other recommenations to make microsoft more successful after they have already started producing their own films
Examples of the next step will be:

1. Companies to co-operate with
2. The best month to produce movies
3.Movie Directors that Microsoft can Work with


