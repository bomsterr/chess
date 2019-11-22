# chess

Background:
Chess is a two-player board game. Chess has existed for many centuries and is still played widely today; there are even websites like Chess.com that organizes games for individuals from different parts of the country to log in, challenge and play each other. Chess is a fair game but there are controversies surrounding the first move advantage. This advantage suggests that white players get immediate inherent benefit of going first and setting up the board for an earlier attack. Often overlooked though is the potential disadvantage if the first move ends up being a blunder. Confirming if such an advantage or disadvantage exists with the first move would help in acknowledging such a bias is present and implementing some rules to ensure that players gains equal opportunity to play white and black during intense competitions.

Methods:
Data were obtained from a set of 16,155 chess games collected from the Lichess API (kaggle.com/datasnaek/chess). While this dataset does not contain all the information of all chess games ever played (this would contain millions of rows), this does have a great sample size to ensure normality.

Results & Discussions:
Of the 16,155 chess games played, there was roughly the same percentage of wins for the white and black players for the three types of victories (out of time, checkmate and resign). The roughly equal winning percentages between two players (Figure 1) suggests that while white do win ~ 2% more games on average than black, the difference is not statistically different to say that someone being white or black determine a player’s chance of winning (p > 0.05).
While there are three kinds of victories, the checkmate is often a sign of a true victory. Checkmating someone ensures that the player either did not foresee such a trap or saw the predictable loss but did not want to resign. Regardless, an analysis of the top five opening moves suggests that black and white players win through different opening strategies. White players often win using “Scanadinavian Defense: Mieses-Kotroc Variation”, while black players often win when their opponents begin with “Van’t Kruijs Opening”. The “Van’t Krujis Opening” is a distinct outlier in the winning opening move for black players, racking up twice as much wins relative to the other moves (Figure 2). This in-depth look suggests that if a white player starts off with “Van’t Krujis Opening”, he has a much higher chance of losing than if he had started with a different move.

Conclusion
The present study suggests that while there is a slight winning advantage for white players who go first, there are also disadvantages if white players start with a detrimental first move that puts their pieces in jeopardy. The Van’t Krujis is an opening move where the pawn moves one space forward to free up bishop’s ability to move (Figure 3). However, this move hinders Queen’s chance to progress to center of the stage, a hindrance as Queen is the most versatile piece with the ability to move in so many different directions. This opening is not very common due to this exact reason and explains why this move can cost the game for the white players. However, this analysis does challenge the inherent benefit of first moves and highlights a shortcoming of going first. This move is rarely used though, especially among top performing chess-players due to its apparent weakness so for now, we can just confirm that white players do get a very minuscule benefit but not significant enough of an advantage for black piece players to say that was the reason for their defeat.
