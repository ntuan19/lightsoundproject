# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Tuan Nguyen**

Time spent: **4** hours spent in total

Link to project: (insert your link here, should start with https://rowan-legendary-metal.glitch.me/ )
or :
- https://glitch.com/~rowan-legendary-metal

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
- [ ] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [x] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of timec to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![image](https://user-images.githubusercontent.com/61070900/112346429-4b26fb00-8d09-11eb-9e05-335149d8c681.gif)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.
   - https://getbootstrap.com/docs/4.0/components/buttons/
   - https://www.w3schools.com/js/DEFAULT.asp - helped me learn Javascript quickly.

2) What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)

- My challenge is to understand Javascript thoroughly. When learning React, I learned JSX fastly and only touched some parts of Javascript.
  Therefore, it takes me a while to comprehend and implement the code. My strategy was to list out all lines of code that I did not understand.
  I try to go step by step to explain different snippets of code and link the snippets of code together to fully understand how those lines of code work.
- Besides, I googled and read on stack overflow. While reading the code, I tried different things on one line of code to see the change in the logic and website’s behavior.
  By doing so, I gradually and intuitively understand the code and understand how and when to use specific things.
  When there was a bug that the display of the button was not as I expected, I tried to comment out different lines of code and began from the beginning. By doing so, I made sure that after specific lines of codes are correct and I did not need to focus on them. I just need to continue to work on the rest.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)

- How can we incorporate an authentication process to personalize the game for different users?
  How can we store users’ information and users' progress in the game if they want to stop the game while playing?
  How can I make the game more interesting rather than including the basic sounds? How can we randomize the pattern of the sounds or the game?
  Is there a way to apply separation of concerns to this web app? Instead of writing the same code for different buttons, is there any way I can write skeleton code and customize the code later for different buttons? How can we manage databases, and which framework can we use to manage databases created from users

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)

- If I had more than 10 hours to work on the project, I would first add a function that authenticates users. Users can create accounts, and only that user can see their game. It requires authentication features such as log-in function, sign-up function, and a lot of work to manage databases. Also, to secure our database, we can use hashing functions to encode each customer's password.
- If I only had a few hours, then for each customer, I would focus on the button pattern. It would be different each time the user clicks the “Start” button. Therefore, I need to create a function that helps to randomize the button pattern. As for the sound, I want to randomize the sound each time the user clicks on the “Start” button. Buttons’ sounds can be different sounds of a song rather than solely one sound.
- Also, the logic of code would be changed, especially the function guess. Each time the user makes a mistake, the counter would increase by 1. If the number of errors surpasses certain allowed mistakes, then the user loses the game. The picture revealed once the button is clicked would only be revealed after certain correct answers from users.

## License

    Copyright [Tuan Nguyen]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
