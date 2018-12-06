# rottenPotato


2D Array Assignment
AP Computer Science
You are making an online movie ratings database called Rotten Potato and you plan to
store movie ratings using a 2D array. The column number will represent a particular movie in
2018, and the row number will represent a particular reviewer. The values of the individual cells
will be the rating for that particular movie by that particular reviewer, marked out of 10. For
example:
To make sure this setup is clear, let's assume that movie 0 is "Rampage" and movie 1 is
"Avengers: Infinity War". Let us also assume that reviewer 0 is Dwight and reviewer 1 is
Michael. Therefore:
• A column represents all the ratings for one movie. In our example, column zero
represents all the ratings for Rampage (4, 7, and 6), and column 1 represents all the
ratings for Infinity War (6, 9, and 9).
• A row represents all the ratings by a particular reviewer. So, row 0 represents all of
Dwight's ratings (4, 6, 2, 5) and row 1 represents all of Michael's ratings (7, 9, 4, 8).
Just to test yourself that you understand what's going on here. Ask yourself:
1. What rating did Dwight give Rampage? How about Infinity War?
2. What rating did Michael give Rampage? How about Infinity War?
Answers are on the next page.
Answers: Dwight gave Rampage a 4 and Infinity War a 6, while Michael gave Rampage a 6 and
Infinity War a 9.
You will have to provide your own fake data to test your assignment. There is a shortcut way to
do this. To make the above grid as a 2D int array, use the following code:
int[][] ratings = { {4,6,2,5},
 {7,9,4,8},
 {6,9,3,7} };
Question 1: Write the method movieAverageRating() that takes a Rotten Potato database (2D
int array) as a parameter and another int that represents a particular movie. Return the average
rating for that movie.
public int movieAvgRating(int[][] ratings, int movie)
Question 2: Write a method that takes a Rotten Potato database (2D int array) as a parameter
and another int that represents a particular movie reviewer. Return the average rating for that
particular reviewer.
public int reviewerAvgRating(int[][] ratings, int reviewer)
Question 3: Write a method that takes a Rotten Potato database (2D int array) as a parameter.
Return the average movie rating for all movies and all reviewers in the database.
public int avgRating2018(int[][] ratings)
Question 4: Write a method that takes a Rotten Potato database (2D int array) as a parameter.
Return the index of the hardest reviewer (the reviewer with the lowest average ranking).
public int hardestRater2018(int[][] ratings)
Question 5: Write a method that takes a Rotten Potato database (2D int array) as a parameter.
Return the index of the worst movie (the movie with the lowest average ranking).
public int worstMovie2018(int[][] ratings)
