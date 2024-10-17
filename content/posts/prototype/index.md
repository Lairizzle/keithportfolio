+++
title = 'Prototype'
date = 2024-10-16T21:17:52-04:00
draft = false
categories = ['Gaming']
tags = ['prototype']
+++

## Refactor, refactor and refactor
Development is going well on the new game for which I am using the working name ‘Prototype’, very creative I know. I have been able to leverage the project management tools in Github to great effect. It really helps keep my ADHD brain on track and keeps me focused on specific tasks instead of getting distracted by the next shiny object, although this still does happen from time to time.

I have been focused on getting the main systems and mechanics completed so that there is a somewhat functional game loop which can be tested and played with. So far I have been able to complete the following systems/mechanics:

Player movement
Enemy base class
Basic Enemy
Running Enemy
Observing Enemy
Portal Enemy
Turret Enemy
Player Powerups (Basic shot, multishot, heat seeking, shield, laser and mines.)
Enemy Spawn Manager System
Power Up Spawn Manager System
Basic Points and Power Up timer tracking on the UI
Player Death
Replay Button
Though a lot of these systems may seem simple, it allows me to create a typical arcade game loop which I expect will be somewhat close to the final product that I scoped for.

Many of these systems I had written in pieces, and improved upon by refactoring and attempting to reduce redundancies as much as possible. Could it be better? Most likely, but learning to min/max those efficiencies will come in time.

Next up on the chopping block will probably enemy health.

Cheers,
Keith
