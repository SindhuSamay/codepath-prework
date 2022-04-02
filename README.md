# Pre-work - *Memory Game*

**Light and sound memory game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Sindhu Samayamantula**

Time spent: **About 5** hours spent in total

Link to project: (https://glitch.com/edit/#!/light-and-sound-memory-game-sindhu-s?path=README.md%3A1%3A0)

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "End" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] Pop-up tips/messages to guide the player in the game.

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

![1](http://g.recordit.co/8VIY59bT41.gif)
![2](http://g.recordit.co/PMUNhd2y45.gif)

[Third gif](http://g.recordit.co/S1Eraa01uE.gif)

[Long gif converted into a video](https://www.loom.com/share/2e26b63fa9084d8495199dbd7a2c9d79?sharedAppSource=personal_library)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[Google color picker, HTML br tag in W3Schools, and CSS box-shadow property in W3Schools.]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[I encountered a challenge when coding the game logic in 
the guess function. To check if the turn was over or not, 
I checked if btn == progress insted of checking if 
guessCounter == progress. This didn't let the program give the
next clue. To figure out the problem, I tried to reread my code and
think of what exactly the computer would do behind each line. This and
looking at the provided solution for this function help me fix the issue.
One thing that took some long time in the submission was generating a gif
and pasting the link for it int he file. One of the softwares provided
in the prework.md would just never finish processing the gif, so I inserted multiple
short gifs in this file to just show the features incompletely. I have also added
a long gif turned into a video in case the grader would like to see the whole game. Additionally, this is my
first time working with a github readme file, so it took me a while to figure out how the
content in it shows up.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[I want to know how to include a text bubble or a tip at a certain time
in the runnig of a program. For example, after pressing on the start button,
the button changes to end/stop, so when this happens, it would be cool
to have a tip appear around the button saying "Click here to stop the game."]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[I would definitely work on adding the optional features mentioned in the prework.md. After completilng those, 
I would try to change the tunes and see if the sounds can be changed, not just the frequency.
I might try to give each button a note from a happy birthday tune fore example. Like 
previously mentioned, I would also add tips or messages when certain timestamps are met.]



## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/8302d6af1c5444d985dab351eba87528?sharedAppSource=personal_library)


## License

    Copyright [Sindhu Samayamantula]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
