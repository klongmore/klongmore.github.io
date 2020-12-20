---
title: Progress Update 1
date: 2020-12-20 17:03:00 +1100
categories: [Blog, Progress Update]
tags: [progress update]     # TAG names should always be lowercase
---
**_So,_** the first week has been pretty successful.

To make this a bit nicer on the eyes, I'll put headings for each 'thing' I was able to make progress on this week. Hopefully there will be some images/gifs too if I'm not too lazy.

![Desktop View](/assets/img/image3.png){: width="240" .right}
## Imported a character sprite

Starting (very) small, I created my project, and imported a nice, basic character sprite that I found on [opengameart.org](http://opengameart.org). I also added the animations in from the spritesheet given, so that they'd be selectable in the animator when required.

![Desktop View](/assets/img/image4.png){: width="240" .right}
<br />

## Created some basic pixel art

I decided to put my photoshop pencil tool skills to the test, and create some pixel art that I could use in a tilemap, as our world. I created some grass variations, some maintained grass variations, water, and water shorelines for our starting area, **Otthon**.

<br />
<br />
<br />

![Desktop View](/assets/img/image1.gif){: width="260" .right}
## Added movement

Added the ability for the player to move the character. Made a test environment out of the tile palette I created, and then tested that the player moved around it correctly. Mapped walking animations to accurately relate to the direction the player moved, and for the animations to stop (but be facing the correct direction) when the player stopped moving. I also added a camera, which smoothly tracks the player's movements.


## Experimented with colliders and triggers

Did a bit of messing around, trying to learn how to use colliders. Learnt somewhat how to use polygon colliders, edge colliders, box and circle colliders, etc. Also had a poke around with making a collider a trigger, and how I can go about using that trigger in code. I imported a sprite for a basic NPC, and added a circle collider around him that I could use for dialogue.

## Created a basic dialogue system
![Desktop View](/assets/img/image2.gif){: width="260" .right}

This is what took most of my time this week. I created a basic dialogue system - ie. you can walk up to an NPC, press a key (space currently), and they'll talk to you. You can press space to skip to the next line of their speech, and if there are no lines left, the dialogue box closes. In this, I also added some basic animations to push and pull the dialogue box in and out of frame, as well as to animate each letter of the text out. Once this was working as I wanted it to, I modified it so that these lines of speech (as well as NPC names), are found in external files, to make future changes and translations easier if need be. This dialogue also locks the player from moving while it is open.


<br />
<br />
And yeah, that's about it. My next goals include:

*   Finalising a main character sprite, as well as drawing frames for animations.
*   Make an inventory system, with the ability to pick up, receive, and store items.
*   Implement basic sounds for things like walking and dialogue.
*   Clean up the unity project (as it's a bit messy at the moment, oops), so it's much easier to navigate and work inside of.
*   Probably more…

_-Kai_
