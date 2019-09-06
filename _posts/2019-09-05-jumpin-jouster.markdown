---
layout: post
title:  "The Jumping Jouster"
date:   2019-09-05 09:48:35 -0400
categories: creative godot
---

I've become quite fond of the [Godot][godot] game engine. Something about the Godot scene hierarchy implementation clicks with my brain a lot more than Unity. Years ago, when I first started making my own games and prototypes, I worked a lot with Cocos2d, primarily in Objective-C. Godot seems similar to Cocos2d and the ease of using GDScript makes it a great tool for prototyping.

Each year for Christmas, my in-laws give me a tear-off calendar of New Yorker cartoons. When I saw this March 19th entry, by [Seth Fleishman][seth], it immediately struck me that the concept would make a fun simple game. 

![cartoon](/assets/2019-09-05-cartoon.png)

So, for the past several months, in my spare time, I've been poking away at The Jumping Jouster. It's a game where you joust and pole vault. A little more poking and I'll release it for all to play. Incidentally, it's difficult to get screenshots of the action in the game, since playing requires repeated pressing of several keys on the keyboard. Here's a look, though:

![jumpin-jouster](/assets/2019-09-05-jumpin-jouster.png)

One learning from the project, so far, has been the degree to which I need to develop procedural systems for the game. For example, when I started the project, I imagined there would be grass levels, snow levels, and mud levels, each with different gameplay dynamics. That would have required the creation of environmental art for each of those levels. I completed the snow and mud terrain elements and implemented a system that would create terrain zones and transition between them. I realized, however, that different gameplay dynamics likely would only increase player frustration with a game that already is a bit challenging. Eventually, I stripped out the other zones and the game now only uses the grass zone.

In hindsight, I should have focused on the core gameplay first before working on expansions to it. This, of course, is a common trap in game development, not only for hobby projects, but also for large studios. When you function as your own artist, producer, programmer, and QA team, it's easy to get lost in the conflicts of interest and spend time spinning your wheels on features unimportant to core gameplay. Lesson learned for next time! (I hope!)

I'll post a followup when its available.

[godot]: https://godotengine.org
[seth]: http://sethwork.com