# FantansyCricketLeague

# Table of content
* Introduction
* Feature
* Point System
* Installation and System requirement
* Getting Started

# Introduction
It is an game where you create a virtual team of real cricket players and score points depending on how your chosen players perform in real life matches. The data of the player is stored in the database which is retrived and show on the GUI based on the action of button clicked or etc.

# Feature
1. Opening screen of the application. You can see the players of each category by selecting the category. To begin with, the selection is disabled until a new team is created from the Manage Teams menu. A pop up asking the name of the team appears.

![alt text](https://github.com/ashwani8958/FantansyCricketLeague/blob/master/MainWindow.png)

2. The toolbar menu options which allow you to create a new team, open an existing team, save your team and finally evaluate the score of a saved team.
3. After clicking New Team, the left box is populated with player names. As you select a different category, the corresponding list of players is displayed.
![alt text](https://github.com/ashwani8958/FantansyCricketLeague/blob/master/New%20team.png)

4. On double-clicking each player name, the right box gets populated. Points available and used are displayed accordingly.
![alt text](https://github.com/ashwani8958/FantansyCricketLeague/blob/master/Team%20saved.png)

5. Message if the game logic is not followed.
![alt text](https://github.com/ashwani8958/FantansyCricketLeague/blob/master/Game%20logic%20error.png)

6. Pop-up on clicking Evaluate Score. You can select your team here and the match for which the players' performance is compared.
7. The final score for your fantasy team based on the match selected.
![alt text](https://github.com/ashwani8958/FantansyCricketLeague/blob/master/Evaluate.png)


# Point System
## Sample of Rules
### Batting
* 1 point for 2 runs scored
* Additional 5 points for half century
* Additional 10 points for century
* 2 points for strike rate (runs/balls faced) of 80-100
* Additional 4 points for strike rate>100
* 1 point for hitting a boundary (four) and 2 points for over boundary (six)

### Bowling
* 10 points for each wicket
* Additional 5 points for three wickets per innings
* Additional 10 points for 5 wickets or more in innings
* 4 points for economy rate (runs given per over) between 3.5 and 4.5
* 7 points for economy rate between 2 and 3.5
* 10 points for economy rate less than 2

### Fielding
* 10 points each for catch/stumping/run out

# System requirement and Installation

## System requirement
1. Python 3
2. SQlitestudio(SQlite3)
   - Download link:- https://sqlitestudio.pl/index.rvt?act=download
3. Python aware editer ex:- ATOM
4. pyqt5

## Installation
* install PyQt5 python library using pip
> pip install PyQt5

**or**

> pip3 install PyQt5

# Getting Started
> git clone https://github.com/ashwani8958/FantansyCricketLeague

* install the required tools
* fork or download the repo
* run the following command in terminal
> python3 2_fantasy_cricket.py
