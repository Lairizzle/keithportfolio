+++
title = 'Development Begins'
date = 2024-10-15T21:17:52-04:00
draft = false
categories = ['game dev']
tags = ['unity', 'learning']
+++

In my quest to learn more about game development and C#, I recently started work on another game. PopIt! was a simple game which was great to use as a way to understand the process of getting a game ready for launch on Steam. Now that I am armed with the knowledge of how to do that, I can focus more on developing some more cool games.

## What is this new game i plan to make?
I think for now I will keep the scope small and realistic. Since I want to build up more foundational knowledge in regards to Unity and C#, I thought I would initially stick with some Arcadey type games that can be realistically executed. I want to actually produce some sort of end result and build a bit of a portfolio (even if it is simple games) as a way to stay motivated and avoid languishing in some sort of protyping/idea/scope creeping hellscape.

I started working on the new game about a week or so ago now and I am going with a working title of “Prototype”. It will be a space shoot ’em up that take takes place in an arena and will be reminiscent of something like Geometry Wars.

## What is done so far?
I wanted to try and approach things in a more methodical way, so I will purposely take things a bit slower and be more deliberate. I leveraged the project management systems available on Github (kind of like a Kan ban) to help plan things out. I currently have separated the tabs into Systems/Mechanics and Content. I figure I will flesh out all of the system and mechanics required to design the game and once that is done I will focus on content like art, effects, sound, music, etc.

Most of the core mechanics seem to be basically complete so I am making great progress. Now that they are complete, I can refactor them.

## What needs to be refactored?
Basically everything will see a refactor pass, as this is not only a best practice but also will be great for building my knowledge base. I recently refactored all the enemy AI scripts and leveraged inheritance for the first time which was super cool to do. I created a base enemy class (this contains all common elements that every enemy will have) and then I can create a script for each enemy type and inherit this and put any custom code needed in the new specific enemy script. This made it really easy to iterate with new enemy types.

So far this project seems to be chugging along, as always I will be streaming my progress on twitch and using this blog to document and comment on my personal development.

Cheers,
Keith
