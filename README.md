# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Aniket Das**

Time spent: **3** hours spent in total

Link to project: [Link](https://glitch.com/edit/#!/light-and-sound-memory-game)

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

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![Walkthrough](http://g.recordit.co/UzmdY9KIkB.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. <br>
I wasn't sure how to implement the images on a button when clicked, so I looked it up on Google and used the site https://www.w3schools.com/cssref/pr_background-image.asp
to help me figure it out.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) <br>
Implementing Strikes took me the most time in creating the game. I wasn't sure about which function to call, or if to call a function at all. I realized the importance of the 
console.log() function, because it's essential to know the states of variables and the sequence of functions when debugging. After every modification, I learned about a mistake or 
bug in the code through testing the app and checking out the console. Thus, I kept improving on every iteration until I finally reached the solution, which was simply to print an alert
and then call playClueSequence().

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) <br>
Now that I know about the basic components of a website, I'm curious about complicated graphics and algorithms. For instance: <br>
- How do we store a relational database in a website?
- How do we make text and images flow, transform, or move with scrolling or clicking?
- How do we build a complex web video game? Can we do it with simply using HTML, CSS, and JS?
- How do we host our website and keep track of the users along with their usage.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) <br>
I think this Light and Sound memory game has great potential as an instrument training app. For instance, the buttons could be replaced with piano tiles, and the pattern could be chosen from specific songs and tones on
the piano such as Beethoven compositions or the Happy Birthday song. The user could pick the type of track and learn it by essentially playing the same light and sound memory game with a few modifications. This would 
require us to change the appearance of the buttons, their tones, and the pattern generator.



## License

    Copyright [Aniket Das]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.