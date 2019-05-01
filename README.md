# Board Game Review:game_die:
<img src='images\bg2.jpg'>

>A board game is a tabletop game that involves counters or pieces moved or placed on a pre-marked surface or "board", according to a set of rules. Some games are based on pure strategy, but many contain an element of chance; and some are purely chance, with no element of skill.  

>Games usually have a goal that a player aims to achieve. Early board games represented a battle between two armies, and most modern board games are still based on defeating opponents in terms of counters, winning position, or accrual of points.

#### :floppy_disk:Data Source:
[Board Game Geek](https://github.com/ThaWeatherman/scrapers/tree/master/boardgamegeek)
#### :mag_right:About this data:
80,000 board games with information such as `minimum players`, `maximum players`, `minimum playtime`, `maximum playtime`, etc. 

### Overview:
- Board games have been a great way to pass the time, from simple ones like The Game of Life to more complicated ones like Dungeons & Dragons. But before you become vested in a Game, what if you could find out how popular it really is:grey_question: What if it was rated to help you learn how fun it really is:grey_question: Well, now using this project you can:exclamation:

- In this project we will focus on predicting the reviews of over 80,000 different board games.The information that we will work on was scrubbed from a database of 80,000 board games and includes information such as minimum players, maximum players, minimum playtime, maximum playtime, etc. We will use the models to ensure that using all of this information, it gives an accurate prediction regarding the reviews.

- This project is developed on a Jupyter notebook using `Python` with Data Analysis libraries: `NumPy` and `Pandas` along with Data Visualization libraries: `Matplotlib` and `Seaborn`.

- Here we are generating board game review predictions by using a `linear regression` model and a `random forest` model.Here we import a data set over 80000 games and then use that information to train both a linear regression model and a random forest model to make predictions based off of board game information.
