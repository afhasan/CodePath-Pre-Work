# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Anonna Hasan

Time spent: 3 hours spent in total

Link to project: https://glitch.com/edit/#!/shade-lush-iguanacolossus


## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

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

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![]GIF (Basic Version): http://g.recordit.co/0763vPoClP.gif
![]GIF (Added Features: Randomly Generated Sequence, Image on Button): http://g.recordit.co/0763vPoClP.gif


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I used websites like Stack Overflow and W3Schools to find different colors I wanted to use and to help me with adding other features, such as a randomly generated sequence. 

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
I had a hard time coding the additional features. I tried to code a random sequence for the pattern array and I wanted to have the button show an image when I clicked on it. The first additional feature was not too hard to code because it is very familiar to what I do in school and my current internship, but the second additional feature was much harder to code. When I approached the first additional feature, I had a clear idea of what my code would look like. However, I was not able to get it to work because I had spent too much time working on the second additional feature, so I ran out of time before the deadline. I believe my code did not work for the first additional feature because pattern is a global array, so my code was not able to change it. I believe I would have been able to fix this if I spent 30 minutes maximum on it. On the other hand, I am unsure how long it would have taken me to get the second additional feature down. After learning more about the <img> tag and other CSS topics, I believe I understand how to approach this problem conceptually. However, I think I would need more time to get the syntax down. Although I was not able to code either of the additional features correctly, I am proud of my progress because I understood the additional features on a conceptual level. I do not have the syntax down, but I have confidence I would be able to figure it out after doing some more research online. However, I think I left my code at a good starting point. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
1) How can you determine what will be the best layout for consumers? I was wondering this when I was choosing the color palette of the stylesheet. 
2) I noticed that as I changed the size of my screen, the buttons rearranged themselves to fit the screen. Is there any way we can write our code in such a way that the display remains constant relative to the screen? For example, if I wanted to keep the buttons laid out in a 2x2 square, is there any way I can adjust the size of the buttons based on the size of the screen? 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had a few more hours to work on this project, I would finish the additional features I started working on (generating a random sequence and displaying images on the buttons). Also, I would like to add another feature in which the sound is displayed for a certain amount of seconds and the user has to play the sound for the same amount of time. That would make the game harder and more interesting because you have to pay attention to both time and sequence. If I were to approach this problem, I would create a double array that keeps track of both time and button. Then, I would randomly assign time in seconds and the sequence. An example of the double array is [1,3,4] (buttons), [3,7,10] (seconds). To make the game more fair, I would give the use some leniency in terms of time. I think I would allow the game to continue if the user pressed the button within + or - 1.5 seconds. 



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
