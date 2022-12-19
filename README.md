# Keanu

#### AKA Conversational Programming

## The problem is the code

I'm amazed by programming. You see, I'm a designer, but from a family of programmers. My dad in fact programmed on cards on some of the first computers there were. So massive street cred. The problem, if you couldn't deduce by the first sentence's allusion, is that I just can't get my head around it. I learned HTML and CSS way back when in the 90's and still know and sort of use them today in fits and spurts. But anything beyond some cut and paste Javascript and absolutely mind-boggling horribly slapdashery with everything from ActionScript (RIP), Director (RIP), Processing, attempts at Ruby have come and gone like the tides. Like I said, I, and many others, just can't get my head around how it works.

[Here is an example of exactly the wrong way](https://guide.nannou.cc/tutorials/draw/animating-a-circle.html/) of having to animate by programming if you ask me.

[Here is a super long screed on visual programming](https://divan.dev/posts/visual_programming_go/) which, if you've ever tried it, attempts at making all the difficult math-like grammar of the above example, somewhat legible. Often this doesn't help.

This leads me to believe the problem with "Learning How To Code" as we understand it is the code itself. Not who's learning it. Not how it's taught even. But how we make it.

## Where AI steps in

Recently (as of December 2022), great leaps and bounds have been made in the AI field, in particular with coding. You can give something like [ChatGPT](https://openai.com/blog/chatgpt/) (OpenAI) something like "animate a ball" and it does all the example above does more or less.

I’m interested in making AI tools usable for people, and I'm interested in programming as a practice, so I thought why not design something that does both for a creative tool interface? You can observe what's going on in the black box while it does stuff for you. There is observability and trust.

## What it could look like

The UI is very simple. You have three boxes. The two on the left are equally functional in that the user types into them and then the display on the right shows the output.

![](https://github.com/jkosem/keanu/blob/main/main-1-create.png)

The user can then just keep adding prompts to produce more and more things, which would be displayed in (close to) real-time as the 'programme' is running.

![](https://github.com/jkosem/keanu/blob/main/main-2-animate.png)

Sometimes it takes a designer/animator/artist a while to get the right speed or movement right and fiddling with numbers isn't the best way of doing it. The user would then give a prompt to give a UI control which is not part of the output but sits on top of it.

![](https://github.com/jkosem/keanu/blob/main/main-3-slider.png)

![](https://github.com/jkosem/keanu/blob/main/main-4-slider.png)

There would be a history of scrubble prompts which would give the user an indestructible command history so they can make more complex animations and procedures and be able to go back a couple of steps to see where things might have gone wrong.

![](https://github.com/jkosem/keanu/blob/main/main-4-scrub.png)