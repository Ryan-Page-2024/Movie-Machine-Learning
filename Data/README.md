# Table of Contents

## File Name: Movies List
The original dataset consists of 50 movies and is used to initialize the data and define the 'Movies' variable referenced in the `compare_movies` function. Initially, each movie is assigned a default ***Re-Watch Desire*** score of 5, along with 0 ***Wins***, 0 ***Losses***, and 0 ***Ties***. <br><br> In the `compare_movies` function, users are prompted to input their movie preferences, which updates the respective movies ***Re-Watch Desire***, ***Wins***, ***Losses***, and ***Ties***, with results clipped between 0 and 10. <br><br> The results are captured in the Movie Comparisons and Comparison Results files.

## File Name: Movie Comparisons
This file stores the results of each movie comparison, tracking updates to ***Re-Watch Desire***, ***Wins***, ***Losses***, and ***Ties***. Based on user input, a movie's ***Re-Watch Desire*** increases by 0.1 for a win and decreases by 0.1 for a loss, with scores clipped between 0 and 10. <br><br> Ties do not affect the ***Re-Watch Desire*** but are recorded alongside the other metrics. I included the option to treat a movie as a tie, though I chose not to.
