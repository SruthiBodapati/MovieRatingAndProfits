# MovieRatingAndProfits
 
1)	Obtained the data “Hollywoods Most Profitable Stories” on public.tableau.com, and we learn that this data is generated based on the dataset “Hollywood Budget” from InformationIsBeautiful.net.

2) The data includes a random sample of 74 movies released between 2007 to 2011, and genre, lead studio, audience score, rotten tomato score, profitability and worldwide gross.

Genre: There are 6 genres included in this dataset. Although some movies might be recognized with more than one genre, the genre recorded in this dataset is obtained from IMDB, a well-known online movie database.

Lead studio: The studio who mainly produce the movie. 12 studios are included, and some other are only classified as independent studio.

Audience Score and Rotten Tomato Score: The average audience rating for the movie and the average metascore of critic reviews respectively. These data are obtained from rotten tomato website. It is notable that there is a special “status” system of both audience score and critic reviews.

●	Audience Score: Rotten(less than 60% positive), Fresh(at least 60% of reviews positive)
●	Critic reviews: Rotten(less than 60% positive), Fresh(at least 60% of reviews positive) and Certified Fresh( 75% or higher). 

Worldwide gross: The worldwide total revenue of the movie in million$.

Profitability: How much a movie can profit when compared to its budget.
                      (i.e. Profitability = Worldwide gross / Budget) Therefore,
                      If profitability < 1, the studio is losing money.
                      If profitability = 1, the studio is neither losing money or earning money.
                      If profitability > 1, the studio is earning money.



3)We designed the study from the perspective of Film Studios. Since two of their main targets are to increase revenue and to create popular movies, so we decide to investigate factors related to worldwide gross and movie rating, including relationships between:

●	Genre and Worldwide Gross/Profitability
●	Audience score and Rotten Tomatoes score
●	Audience score and Profitability/Worldwide Gross
●	Audience score and Genre
