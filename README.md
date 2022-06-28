# The low-tech timekiller 
![mainimgtk](https://user-images.githubusercontent.com/93250649/176152395-c17c26a2-4851-44d6-88e3-0c5d6bca0497.JPG)

The low-tech timekiller is an application that provides the user three simple games to choose from a menu. The three diffent games comes in the form of a rock/papper/scissors game, a quiz game and a ask the magic eightball. 

### Content
[Features](#section-1)

[Design](#section-2)

[Technologies Used](#section-3)

[Testing](#section-4)

[Deployment](#section-5)

[Credits](#section-6)


------

## <a name="section-1"></a> Features

### Main menu
The main menu provides the choice of four diffrent options and the player simply enters the number of the game they want to play or if they want to quit the application.   
![mainmenutk](https://user-images.githubusercontent.com/93250649/176152551-fa069f62-8a2f-44d9-9272-f9d47b41d41c.JPG)




### Rock/Paper/Scissors game 
The rock/paper/scissors is a take on the classic. The player gets to choose first and then the computer randomly picks one of the three options. The game compares the
input from the user with the computer and decides who wins and updates the score value accordingly. If the player and computer have made the same choice the 
game simply prints "draw" and the player gets to pick again.
![rpsimg](https://user-images.githubusercontent.com/93250649/176152802-f669f52e-d794-4654-b99a-4103555f5244.JPG)

### Know your Nintendo
Know your Nintendo is a small quiz game with questions taken from the world or Nintendo. If the player get the answer correct a score variable is updated and if 
the player get the answer wrong a the correct answer is presented to the player. At the end of the game the players total score is presented.
![nintendoimg](https://user-images.githubusercontent.com/93250649/176153035-fb69933f-8e45-4aa1-ba8b-dc08286bc45b.JPG)


### Magic eightball 
The Magic eightball game is a game where the player gets to ask the eightball any question and gets presented a random answer from a pre-written list. There is no win condition to this game, its simply a silly way to kill some time. 
![eightballimg](https://user-images.githubusercontent.com/93250649/176153236-ba4443ab-3d67-43ea-bb44-58ff2c9211fd.JPG)


## <a name="section-2"></a> Design
Since the application is a command line application there has been no consideration about the desing other then making the question and the information presented 
to the player logical and easy to follow.


## <a name="section-3"></a> Technologies Used
### Languages Used

-Python

### Frameworks, Libraries & Programs Used

Git: was used for version control by utilising the Gitpod terminal to commit to Git and Push to GitHub.

GitHub: is used as the respository for the projects code after being pushed from Git.



## <a name="section-4"></a> Testing
Testing done via http://pep8online.com/
![testing2](https://user-images.githubusercontent.com/93250649/176155099-3871948e-1d33-4923-8968-8625121d40f6.JPG)



## <a name="section-5"></a> Deployment
The project was deployed using Code Institute's mock terminal for Heroku.
 
An account was created at Heroku and linked with this github repository.

Under the settings option a config vars a option of PORT with a value of 8000 was added

Two additional buildpacks was added inform of Python and NodeJS

After the settings was updated the project was built and deployed via the deploy option. 

When the app is successfully deplyode we are presented with a link to the application.

 
Link to the page: https://low-tech-time-killer.herokuapp.com/
## <a name="section-6"></a> Credits

### Code
https://www.youtube.com/c/TechWithTim
Game logic and inspiration for the rock/paper/scissors game 


