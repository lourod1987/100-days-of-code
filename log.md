# 100 Days Of Code - Log

### Day 0: May 14, 2018

**Today's Progress**: Began Memory game project, set up basic file structure and most of the html.

**Thoughts:** I'll need to do some additional planning and examination of what exactly I need to accomplish before I push forward with any code tomorrow. It is nice to have a footing to start from. Always makes moving forward with the project easier.

**Link to work:** [Concentration App](https://github.com/lourod1987/concentration)


### Day 1: May 15, 2018

**Today's Progress**: Finished the basic html structure and began work on JavaScript file.

**Thoughts:** Today I got my html basic structure completely finished. Got the card flipping functionality working. I will need to create a mechanism to check flipped cards and reset them if they are not a match or lock them in place if matched. Something will need to keep track of cards that are matches. Getting the card stack to randomize is proving tricky. I set up some basic css in order to make working on the script easier.

**Link to work:** [Concentration App](https://github.com/lourod1987/concentration)


### Day 2: May 16, 2018

**Today's Progress**: Most of the logic for the concentration game is now complete. Began theming of content.

**Thoughts:** Most of the JS logic now complete. A few quirks to work out. What is missing is a timer as well as pushing the congrats and  score to a modal rather then alert. For some reason I am not capturing my score content correctly (I am sure it something simple that I am overlooking).

**Link to work:** [Concentration App](https://github.com/lourod1987/concentration)


### Day 3: May 17, 2018

**Today's Progress**: I worked on css animations, fixed several code css & js issues, and worked on artwork for the project.

**Thoughts:** I fixed the move counter today. Got new animations working and fixed some other ones to function as intended. Made a few additional css and JS code fixes. I spent a lot of time working on art for the project today. I got my hour of code work in but feel like I could have done more.

**Link to work:** [Concentration App](https://github.com/lourod1987/concentration)


### Day 4: May 18, 2018

**Today's Progress**: I attempted a to fix a few issues with my code today, ran into a lot of dead ends.

**Thoughts:** I was attempting to fix several issues before I moved onto implementing the missing features. One fix I was attempting was to add empty stars after I remove full ones when the score decreases. Except I kept adding the empty stars infinitely. I figured out why that was happening and a solution to remedy the issue. I will have to restructure how the scoreCheck function operates. Today was a day of dead ends. I learned for sure.

**Link to work:** [Concentration App](https://github.com/lourod1987/concentration)


### Day 5: May 19, 2018

**Today's Progress**: I was at a hackathon but did not get any coding in :(.

**Thoughts:** I was at hackathon and unfortunately for me my group decided to focus on solely idea development and not prototyping a working tech solution for the problem for which we had already created a rough blueprint of the requirements. I was too burned out when I got home to do anything but a few cli heroku tutorials.

**Link to work:** N/A


### Day 6: May 20, 2018

**Today's Progress**: I began working on the timer for my card game, as well attempting to improve how my win condition is checked.

**Thoughts:** I'll have to make tradeoffs for performance versus how I want the win condition to trigger. Previously I have the function for checking the win conding running on an interval which allowed the final two correct cards to be filled with color and animated before the win alert popped up. Now I have the win check condition being called only when the two cards are properly matched but no anim or color fill. The timer work has just begun. I believe I have everything I'll need to have it function but I will need to test it tomorrow.

**Link to work:** [Concentration App](https://github.com/lourod1987/concentration)


### Day 7: May 21, 2018

**Today's Progress**: Timer completed. Modal implemented with final time displayed on it and also finally got the score to push correctly onto the win state!

**Thoughts:** I am pumped! I got the timer fully functional. With the score coming up on the win state. Modal has been implemented. Code cleanup, css adjustments, finalizing presentation, and art are what remain for the project now. After those are done I will cook up, plan, and implement additional features.

**Link to work:** [Concentration App](https://github.com/lourod1987/concentration)


### Day 8: May 22, 2018

**Today's Progress**: Worked on issues related with modal in both js and css. Made some changes to html for modal.

**Thoughts:** Getting the modal to style as I wanted proved to be more time consuming then I thought it would. Fixed some JS modal output issues as well. Now that I have everything where I want it, I need to finalize presentation (css styles) and go back over JavaScript code and refactor for performance/readability (organization and structure).

**Link to work:** [Concentration App](https://github.com/lourod1987/concentration)


### Day 9: May 23, 2018

**Today's Progress**: CSS Presentation work is completed along with some presentation modifications done through JS.

**Thoughts:** I finished the presentation work I wanted to and the project finally has the cohesive look I was aiming for. Their is some tinkering I want to do but it is overall done. I was about to start refactoring my code for performance/readability when I was testing and run into an annoying win state bug. I've been pounding my head against it for nearly two hours. Definitely time to take a break. When I do manage to iron out the win state kink, I'll move on to refactoring and responsiveness for the Concentration game.

**Link to work:** [Concentration App](https://github.com/lourod1987/concentration)


### Day 10: May 24, 2018

**Today's Progress**: Fixed win state bug. Added audio, audio calls, mute/sound icon, and funcionality for mute/sound. Fixed scaling issues with svg files. Began testing for performance issues.

**Thoughts:** Today I felt my project come together. Felt like all the pieces finally fit. I shared out my project on my live site so others could play and test theh game. I knocked out the win state bug by working on other stuff for the game while I felt stuck. This helped me think of a way to simplify what I doing which cleared the bug! There are performance issues on the Chrome and Brave browsers. Not to mention I am sure I can improve the overall performance of my project in general. I will work toward that tomorrow. Also still some other issues/trivial presentation things I want to get done. 

**Link to work:** [Concentration App](https://github.com/lourod1987/concentration)


### Day 11: May 25, 2018

**Today's Progress**: Added a few additional audio cues. Reduced svg file sizes down to a third total of what they were. Added in an empty star and improved the condition on which you lose stars. Fixed a win state bug where you could lose a star but still get the 5 star win state screen. Player can no longer click more then two cards at a time. Improved code readability and performance.

**Thoughts:** Today I did a lot more then I thought I would. I am really happy with the progress made. The performance and readability changes I made today go a long way to making the project ready to turn in. Their are still some performance enhancements that can be done to scale down system/browser cost. I am aiming to finish what's left of performance changes tomorrow. As well as knock out some responsive sizing. Also I can't believe I've spent nearly 2 weeks on this project, time flew. There have been challenges but I've learned a lot and it has been fun.

**Link to work:** [Concentration App](https://github.com/lourod1987/concentration)
