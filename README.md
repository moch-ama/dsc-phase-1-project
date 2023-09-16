# Arnold Mochama Phase 1 Project

## Introduction
The business question was ;
Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

## Data Pre processing
csv files were loaded from my local machine and read into a pandas dataframe. This was done after the necessary libraries were imported.
The data was then explored using functions and methods such as .describe(), .shape(), .info(), .duplicated and .sum()

## Data Cleaning
After exploring the data, the data was cleaned. There were no duplicates values. However there were missing values. The missing values were dealt with in 2 ways namely;
    a.)filled in missing values for example, missing data from the runtime_minutes column.
    b.)dropping rows with missing columns.

Ouliers in the Gross incomes were also checked.
Necessary additional columns were added for example, total_movie_gross

## Data Visualisations
Various visualisations were made starting with a box plot of runtime_minutes to check for the outliers.
the outliers were then dropped and a histogram created to show the dirstribution of the runtime_minutes.

Afterwards, a genre distribution Treemap was created to show the number of movies in various genres.
The following Bar graphs were also plotted:
    1.Top 5 Movie genres
    2.Top 5 movie by total gross
    3.Top 5 movie by domestic gross
    4.Top 5 movie by foreign gross
    5.Top 5 rated movie genres
    6.Top 10 movies by Net Income
    7.Top 10 movie genres with highest Net Income

### Findings
Most movies ran for just under 90 min, (but above 80 min) as seen on the histogram.

-Top 5 genres (most genres in the dataset): 1.Documentary 2.Drama 3.Comedy 4.Horror 5.Comedy, Drama

-Top 5 movies with highest Total Gross Income: 1.Marvel's The Avengers 2.Avengers:Age of Ultron 3.Black Panther 4.Harry Potter and Deathly Hallows Part 2 5.Star Wars:The Last Jedi

-Top 5 movies with highest Domestic Gross: 1.Star Wars:The force awakens 2.Black Panther 3.Avengers:Infinity War 4.Jurassic World 5.Marvel's The Avengers

-Top 5 movies with highest Foreign Gross: 1.Harry Potter and Deathly Hallows Part 2 2.Avengers:Age of Ultron 3.Marvel's The Avengers 4.Jurassic World:Fallen kingdom 5.Frozen

## RESULTS FROM SAMPLED DATAFRAMES.
                
-Top 5 Highly Rated Movie Genres: 1.Comedy, Documentary, Fantasy 2.Documentary, Family, Musical 3.History, Sport 4.Music, Mystery 5.Game-show

-Top 5 Movies by Net Income: 1.Black Panther 2.Jurassic World:Fallen Kingdom 3.Frozen 4.Minions 5.Avengers:Age of Ultron

-Top 5 Movie Genres by Net Income: 1.Fantasy,Romance 2.Adevnture, Drama, Sport 3.Biography, Documentary, Sport 4.Ducmentary, Drama, Sport 5.Sci-Fi

### Conclusion
From the analysis, the movie studio by Microsoft is a good business venture. Microsoft has to fit itself into the movie Industry and make data-driven decision to be able to make profit and come to be one among the top. Below are the recommendations.

### Recommendations
1.Microsoft movie studio should launch their studio by producing movies under the genres that were highly rated so as to captivate a lot of new audience.

2.Since it's a business, after settling in and putting it's name out there, Microsoft movie studio should then look into producing movies under the genres with highest Net Income.

3.From my findings, superhero movies do well so Microsoft movie studio should maybe start a Microsoft Superhero Series of movies. They should also do comics about the heroes so as to boost movie ratings.

4.Microsoft should also research on which novels are bestselling and form partnerships to produce movies of such books. From the analysis a Harry Potter film has made it to the list of high earning gross income.

5.Microsoft should look into animation(under fantasy) and produce some animations. Animated movies are doing relatively well with Frozen being among Highest Foreign gross earners, and Frozen and Minions being among Highest Net income earners.

6.Microsoft movie studio should make their movies around 90 minutes since most movies are about 90 minutes long.

