# Keanu

#### AKA Conversational Programming

## The problem is (probably) the code

I'm amazed by programming. You see, I'm a designer, but from a family of programmers. My dad in fact programmed on cards on some of the first computers there were. So massive street cred somehow.

The problem is that I just can't get my head around it. I learned HTML and CSS way back when in the 90's (not really programming anyhow) and still know and use them today in fits and spurts and some cut and paste Javascript. That's about it. Over the past two plus decades, there has been a mind-boggling, horribly slapdash slog through everything from ActionScript (RIP), to Director (RIP), to Processing, to MaxMSP to Ruby. All have come and gone like the tides. I just can't get my head around how they works. I'm not alone either.

[Here is a super long screed on visual programming](https://divan.dev/posts/visual_programming_go/) which, if you've ever tried it, attempts at making all the difficult math-like grammar of the above example, more legible, and legibility, being able to read and understand is key. I'm still fascinated with visual programming, but it's never really caught on at any sort of scale. Also, it's still super complicated, but at least you can sort of see what is going on, this connects to that and this thing changes that.

All of this leads me to believe the problem with "Learning How To Code" as we understand it is not who's learning it. Not how it's taught even. But how we make it.

## Where AI steps in

Recently (late 2022), great leaps and bounds have been made in the AI field, in particular with coding. You can give something like [ChatGPT](https://openai.com/blog/chatgpt/) (OpenAI) something like "animate a ball" and it does all the example above does more or less. And of course, way easier.

I’m very interested in the design of tools, and now in particular AI tools, and making them usable. I'm also interested in programming as a practice. So I thought why not design something that does both for a creative tool interface? You can observe what's going on in the background while it does stuff for you. There is observability, trust and theoretically more understanding. More importantly, someone who is code-curious can see the translation of their intent in real time into workable code. They can speak what they want, how they want, and then see it translated into something like Javascript. This also gives the novice a way to see how it should turn out for what they want. They can see the grammar constructed for them while they form their thoughts through doing, and thus begin to learn and appreciate it, without struggling for months to create something and giving up after running into the wall too many times.

## What it could look like

The UI is very simple. You have three boxes. The two on the left are equally functional in that the user types into them and then the display on the right shows the output.

The user starts with a prompt to create a red circle.

![](https://github.com/jkosem/keanu/blob/main/main-1-create.png)

The user can then just keep adding prompts to produce more and more things, which would be displayed in (close to) real-time as the 'programme' is running. In this case, they are animating the red circle.

![](https://github.com/jkosem/keanu/blob/main/main-2-animate.png)

Sometimes it takes a designer/animator/artist a while to get the right speed or movement right and fiddling with numbers isn't the best way of doing it. The user would then give a prompt to be given UI control to fine tune the speed. This slider is not part of the output but sits on top of it. It is also accesible in the prompt window as well, as indicated by the icon.

![](https://github.com/jkosem/keanu/blob/main/main-3-slider.png)

![](https://github.com/jkosem/keanu/blob/main/main-4-slider.png)

There would be a history of prompts the user could scrub up and down through. This would give them an indestructible command history they could work with and change as needed. They could then make more complex animations and procedures and be able to go back a couple of steps to see where things might have gone wrong. This idea gives the user a tool not commonly seen in prompt-command interfaces, which is the ability to work in work additively, bit by bit, and correctively as needed while seeing the results graphically and in code (JS).

![](https://github.com/jkosem/keanu/blob/main/main-4-scrub.png)

## Roadmap

* GIFs or some animation/video showing what this would look like for real...which would ideally be able to export from this [CodePen](https://codepen.io/jkosem/pen/PoagPJg)
* Awesome logo
* Continue looking for something out there that already exists for years that already does this
* 3d mode designs with AI texture generation prompt
* Soliciting brutal feedback from developers and Processing users

## Credit

The design makes heavy use of [IBM's Carbon Design System](https://carbondesignsystem.com), where credit is due. It's pretty damn solid. Give it a whirl.
