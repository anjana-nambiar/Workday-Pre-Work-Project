# Pre-work - _Memory Game_

Look & Listen-Memory Game is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: Anjana Nambiar

Time spent: 12.5 hours spent in total

Link to project: https://glitch.com/edit/#!/sweet-orchid-soybean

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each light up and play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern
- [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [x] Buttons use a pitch (frequency) other than the ones in the tutorial
- [ ] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [x] computer picks a different pattern each time the game is played
- [x] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
(https://i.imgur.com/uJZojue.gif)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

   W3docs.com - to create the milticolor background
   https://www.w3docs.com/snippets/css/how-to-create-a-multicolor-text-in-html-and-css.html
   MDN Web Docs - to debug my Math.random() function
   https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random
   
2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)

   
   A challenge I encountered during the creation and submission process was when I attempted to implement a function to allow the user multiple
   chances before losing the game. I understood the main algorithm and began to write the first few lines. I immediately ran into the problem that 
   I was unsure of where to place the code, as it was not fitting where the loseGame() function was being called. After minor adjustmentents, the 
   code failed again. I realized that in order to debug the code efficiently, I had to walk through the steps of my code and think about what each line 
   would do. I started at the very top,  I had a global variable to mark the number of tries the user already had, but then I recognized that I had to 
   initialize the counter every time and that I would then be able to change the loseGame() function itself, to check for the number of user mistakes 
   counter. The solution in the end was simple, but I was able to reinforce and practice debugging, by reading through the code and understanding the 
   purpose and action of each line. 


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)

   Upon completion of the project and in the process of submission, I am curious to know how the same project could be revised from the 
   standpoint of a front end developer. I have made my best attempt to create this game, however I would like to know how it may be 
   improved to directly influence user experience. On the same note, how would that perspective of a  full-stack developer change 
   the program? From my understanding, full-stack development takes into account both frontend, user-oriented, and backend, engineer-oriented. 
   Therefore I presume that the functions and element handling would be more efficient,  however would the user experience be affected?
   To further dive into this question, I am curious to understand how the mechanics between backend and frontend development work together
   in circumstances where one may have to compromise for the other. In my project, I had to compromise the efficiency of my code in order to
   create the multi-colored background and I made that choice based on user experience, how would that change as I continue learning web development?


4) If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. 
   (recommended 100 - 300 words)

   Given the opportunity to continue working on this project, I would alter its visual characteristics
   by changing each button's background to be an animated image in a GIF style. I would implement this in a similar format as the background text I have
   for the heading. I would also heighten the difficulty by adding levels that progressively entail more buttons and less time. Using the same process to 
   add buttons and adding an adjustable timer. To add to the challenge, the colorized button shifts in a clockwise direction every round, using a function 
   that is called after each round and using the position properties in style.css.

## License

    Copyright Anjana Nambiar

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
