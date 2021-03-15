# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Joshua Chung

Time spent: **#** hours spent in total: 2

Link to project: https://github.com/joshyeram/simon

## Required Functionality

The following **required** functionality is complete:

* [yes] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [yes] "Start" button toggles between "Start" and "Stop" when clicked. 
* [yes] Game buttons each light up and play a sound when clicked. 
* [yes] Computer plays back sequence of clues including sound and visual cue for each button
* [yes] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [yes] User wins the game after guessing a complete pattern
* [yes] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [yes] Buttons use a pitch (frequency) other than the ones in the tutorial
* [yes] More than 4 functional game buttons
* [yes] Playback speeds up on each turn
* [yes] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [yes] List anything else that you can get done to improve the app!
  - Could implement a global leaderboard
  - Could implement different mods: fastest clicks, longest clicks, and moving tiles
## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://imgur.com/sqHaAID)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[none]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
The most significant challenge that I encountered while creating this submission was learning the layout of the index.html file as I was confused about the parenthesis and angled brackets match closings. I thought it was similar to other programming languages that I know like Python and Java where most statements are in parenthesis like () or {}. However, in this case, the statement was also inside the brackets but also outside the brackets which confused me greatly. And having a lot of experience in Java and C, it was difficult to code in pseudo-code as these languages are strict. 
I was able to overcome this trouble by understanding the pattern of the button body and format. If it is outside the <div>, a group you artificially created, you need the make your button like a <div> to behave as its own group. On the other hand, if the buttons are grouped, the information of the button should be enclosed before button declaration or the declaration process. Overall the project was simple to understand but the formatting and syntax made it difficult to implement additional features. I hope to add some other features before the due date such as moving tiles but that may need additional libraries and learning before I take on the challenge.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I am still wondering what the syntax is for HTML and do not get how you can just create your own button with <button>. Is it a special class that HTML already implemented or is it a feature you need to download through libraries? What happens if there are multiple files with the same file type like index2 HTML? Does that mean you can switch between websites or are they still static? How would you go about deploying this project on your own web address? Do you have to get your own domain of sort? Will this same program run on different versions of HTML?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
Personally, I would love to implement a moving box feature so that the user has to know the colors and the movement for the blocks to achieve a higher score. Although it may be more code to account for collisions and may need to render a real-time if I am using a 3D object, adding this game mode would introduce more variability in the score and this makes the game more fun in the long run. It would be interesting to do a scoring system where the scores you add on exponentially decrease as time goes on. I will try to add it one as time goes but if time does not allow, I already implemented 2 more blocks and a decaying time system.



## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
