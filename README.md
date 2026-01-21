Number guessing game 
 
 Branch Structure at Project Start

This repository demonstrates advanced Git workflows including branching, merging, rebasing, squashing, and cherry-picking through a Number Guessing Game application.

 feature1
This branch introduces several quality-of-life improvements to enhance the player experience:

 feature2
This branch implements a maximum attempts system to add challenge and structure to the game:

feature3
This branch adds a hint system to help players after multiple unsuccessful attempts:


1- the Differences between merge, rebase, squash, and cherry-pick Merge: Joins two branches together while preserving the history of all the commits made. Rebase: Taking commits from one branch and adding it onto another in order to have a clean linear history. Squash: Takes multiple commits made and bundles them into one, and that makes it more clean and understandable. I wold use it to group a number of small commits into one meaningful commit. Cherry-pick: Copies a commit from one branch to another, and especially used for hotfixes.

2- feature1 vs feature2 vs feature3 feature1:

Added ability to quit game with negative number input
Play-again loop functionality
Improve user feedback messages for guesses
Added version comment documenting quit feature. feature2:
Add maxAttempts constant and game over state
Implement max attempts logic and game over condition feature3:
Add hint system to show proximity after 3 attempts.