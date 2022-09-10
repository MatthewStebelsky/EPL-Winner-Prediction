This project attempts to guess the winner of an English Premier League game through using the data from prior seasons.
The project is split into two parts. The first is an online web scraper that collects the necessary statistics from data online and converts it to a csv file. The second part cleans the data and uses machine learning to create a probability as to the winner of the game.

The web scraping part of my project makes use of python libraries such as pandas, requests, and beautiful soup inside the framework of JupyterLab.

The machine learning part of my project uses the sklearn package with the RandomForestClassifier class (helps detect non-linearities in data). This part of the project also includes python library pandas and uses the method of rolling averages.

This project is very simple, and i'm hoping to extend it to make it more complex and hopefully more accurate (current accuracy is about 55%
