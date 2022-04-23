# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Aryan Parikh

Time spent: 10 hours spent in total

Link to project: https://glitch.com/~nervous-peppered-hunter

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
* [x] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] I also added one more pattern so the total amount of patterns was 9 instead of 8.

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![LightandSoundMemoryGame](https://user-images.githubusercontent.com/92760614/164836715-952ec3be-62bf-49e7-b324-aa3e811ce88d.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I did not use any outside resources to complete my submission, but used the links provided such as https://developer.mozilla.org/en-US/docs/web/javascript/reference/global_objects/math/random and https://www.w3schools.com/. 

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
I definitely faced some challenges when creating this submission. One big challenge I faced was with optional feature number 6: adding a ticking clock. After I had created the main function part of this code, I had to go through every function to make sure that the time would reset after the person won, the person lost, the person made three mistakes, or if the person ran out of time. I did this by adding console.log statements and figuring out where my code was going wrong. I didn’t take all the possibilities into account first, but after I figured that out I went through the whole code inserting timeleft=0 where it needed to be. I also had a similar challenge when I came across functions I didn’t know how to implement in javascript. I didn’t know how to use Math.random so I used the mozilla website which helped me realize that I needed Math.floor(Math.random() * (max - min) + min) to get the correct random range of values. I also was not used to having to utilize let in the for loop as I haven’t worked a ton in javascript. I also utilized an array and a for loop to randomly generate the pattern at the beginning of the game. The last similar challenge I faced was the optional feature where I had to spruce up my buttons. I had to utilize the w3schools website for this since I didn’t have much knowledge in the exact line of code I would need so that each image is hidden except when the user is pressing the appropriate button. Utilizing w3schools, I figured out that in the css file, I needed to add background-image:url(“actual url”); and background-size: 200px 200px; to complete this task. All of these challenges I mentioned were fairly similar and just required me to go through the code and actually understand what I was implementing and how I would go about doing that. My main process was defining the problem, planning the solution, coding the program, and then testing the program with the actual game and console.log statements. Utilizing all of the resources provided, I was able to complete this assignment and overcome the obstacles. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
After completing this assignment, I didn’t have many deep questions about web development. One vague question that came to mind was what the key responsibilities would be of a web developer and what major languages should a web developer know. The reason that these two questions came to mind was because this project has left me really interested in this space. Utilizing css, js, and html was extremely fun and time flew. A question that involves a bit of a deeper understanding was what steps do you take to optimize your site's loading time? This was a question that came up because I felt like there are many ways one could go about doing this. Other than this, I don’t currently have many in depth questions about web development.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
The first thing I would have probably implemented is different sounds. The one additional feature I didn’t implement was a game button sound that was more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones). I also was thinking about how instead of the bar that I used to limit how much time the player has to make their guesses, I would do something differently. I would try to instead add a display that would countdown the amount of time given before the end of the game. This would be easier for the player to gauge how many seconds they have left. I also think it would be beneficial to add a display on the HTML page to show the user how many lives they have left before the game ends. Aside from this, I also had the idea of potentially removing the light aspect 4-5 guesses in. The total amount of guesses needed is 9 and I thought that maybe 4-5 guesses in, I could make it more challenging by not letting the button change anymore. This would be possible if I made sure to change the sounds to fairly different noises since the player should have good knowledge of the sounds by the 4th or 5th guess. I know this would be harder to implement, but it was an idea that I really wanted to figure out.



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright Aryan Parikh

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
