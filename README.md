# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Ana Camba**

Time spent: **7** hours spent in total

Link to project: (https://glitch.com/edit/#!/knowing-confirmed-desk)

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://i.imgur.com/5kOXJWp.gif)
![](https://i.imgur.com/YnjDEOZ.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

[N/A]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

[Developing a clear and well-defined program logic is a crucial step in designing a programming project. While creating this submission I encountered many challenges along the way. Understanding the game logic behind the “function guess (btn)”  was one of those challenges. The guess function had a parameter representing which button was pressed. Inside the function I first had to check whether the game was active. If not, I had to break out of this function using the return command. 

After figuring out the first section I then proceeded to do a nested conditional statement to consider each possible case for the user's guess. I guided myself from the flow chart in the instructions. In here I had to consider each possibility: 

1) If the guess was wrong the game will automatically finished and show the user the message “GAME OVER”

2) If the guess was correct then there were two possibilities:

      a) If the turn was not over the guess counter had to increment 

      b) If the turn was over I had to check if it was the last round: 

- If it was the last round, the user will automatically win the game and the game will display a message “GAME OVER: You won” 

- If the game is not over the next sequence will be played.]


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

[After doing the submission and being familiar with the game I wonder what steps are the ideal to  take to optimize the site’s loading time? Having familiarity with different websites I know the more features it has the more difficult it is for a website to support them. So, since our program is a game I wanted to know what would be the best way to optimize the website so that if I were to add more features the website could handle the data.
Also, as a computer engineering student passionate about creating accessible resources through technology, I wanted to know what is the best way to approach web accessibility? What is the best way to make sure one’s websites and applications are accessible to all kinds of users?
]


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

[
If I had more time to work on this project I will add a timer on the screen and I will make the buttons move and change colors through each round to make the game more interesting and challenging to the user. I will also instead of using a pitch I would like to incorporate pieces of popular songs so the user could guess them. I would also like to incorporate a maximum of 3 lives per day and if the user wants to play more they will have to share their special link with families and friends to gain more lives.
]



## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/a15d64ea7f05411f82559189a5f8d063)


## License

    Copyright [Ana Camba]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
